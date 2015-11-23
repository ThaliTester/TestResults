#### Test 503880196b4ec73_thali04_samsung-SM-G900F Logs


```
--------- beginning of main
I/ServiceManager(  329): Waiting for service AtCmdFwd...
--------- beginning of system
V/AlarmManager(  834): waitForAlarm result :4
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  834): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/LightsService(  834): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 834) 
D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  834): Plugged
I/MotionRecognitionService(  834): setPowerConnected  = true
D/LightsService(  834): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/SecContentProvider2(  834): uri = 14 selection = getSealedState
D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
E/LightSensor(  834): Light old sensor_state 0, new sensor_state : 512 en : 1
D/SensorManager(  834): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/BatteryService(  834): turn on LED for fully charged
D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -2
V/ApplicationPolicy(  834): isApplicationStateBlocked userId -2 pkgname com.android.systemui
D/WindowManager(  834): showStatusBarByNotification() mOpenByNotification=false
D/PowerManagerService(  834): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10058 pid=1182
I/PowerManagerService(  834): !@[ps] Screen__On wl: PowerUI.Notification
I/PowerManagerService(  834): Waking up from sleep (uid 10058)...
D/PowerManagerService(  834): [PWL] sb acquire: PowerManagerService.Broadcasts
V/KeyguardServiceDelegate(  834): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@2f033dec)
D/KeyguardViewMediator( 1182): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1182): notifyScreenOnLocked
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/PowerManagerService(  834): [s] UserActivityState : 0 -> 1
D/PowerManagerService(  834): [PWL] sb acquire: PowerManagerService.Display
D/Launcher( 1497): onRestart, Launcher: 806022262
I/DisplayPowerController(  834): Blocking screen on until initial contents have been drawn.
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/SContextService(  834): 	.registerCallback : 1, client=
D/AutomaticBrightnessController(  834): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
D/DisplayPowerController(  834): getFinalBrightness : 0 -> 0
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/AutomaticBrightnessController(  834): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
W/CAE     (  834): setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
D/AutomaticBrightnessController(  834): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
D/PowerManagerService(  834): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/MISC PowerHAL(  834): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
I/AutomaticBrightnessController(  834): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 1
D/MISC PowerHAL(  834): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
I/AutomaticBrightnessController(  834): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
I/CAE     (  834): setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
I/CAE     (  834): setCAProperty(ContextAwareService.java:469) - result : true
W/CAE     (  834): setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  834): sendProperty() : service = Auto Rotation
W/CAE     (  834): registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
D/SensorManager(  834): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/PowerManagerService(  834): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 9ms
I/QCOM PowerHAL(  834): Got set_interactive hint
V/CAE     (  834): start(ContextProvider.java:126)
V/CAE     (  834): clear(AutoRotationRunner.java:182)
D/SurfaceFlinger(  259): Set power mode=2, type=0 flinger=0xb6a62000
D/qdhwcomposer(  259): hwc_blank: Unblanking display: 0
I/DisplayManagerService(  834): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
E/Sensors (  834): Acc old sensor_state 512, new sensor_state : 513 en : 1
V/CAE     (  834): enable(AutoRotationRunner.java:158)
I/CAE     (  834): sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
D/SensorHubManager(  834): SendSensorHubData: send data = -79, 7, 0, 0
D/SensorManager(  834): registerListener :: 0, MPU6500 Acceleration Sensor, 200000, 0,  
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
D/PowerManagerService(  834): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 12ms
D/Sensorhubs(  306): sendContextData: -79, 7, 0, 0
D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/CAE     (  834): getFaultDetectionResult(AutoRotationRunner.java:195) - true
I/CAE     (  834): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
D/CAE     (  834): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
I/CAE     (  834): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
D/CAE     (  834): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
I/CAE     (  834): showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@81065c4, Service : AUTO_ROTATION(1)
W/CAE     (  834): registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  834): addSContextService() : service = Auto Rotation
D/SContextService(  834): ===== SContext Service List =====
D/SContextService(  834): Listener : android.hardware.scontext.SContextService$Listener@27953cad, Service : Auto Rotation
D/SContextManager(  834):   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@2cdc4cd8, service=Auto Rotation
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/InputManager-JNI(  834): setDeviceInteractive: 1
D/KeyguardViewMediator( 1182): handleNotifyScreenOn
D/InputManager-JNI(  834): sysfs_write +: /sys/class/input/event1/device/enabled: 1
D/StatusBarKeyguardViewManager( 1182): onScreenTurnedOn()
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/Launcher( 1497): onStart, Launcher: 806022262
D/InputManager-JNI(  834): sysfs_write +: /sys/class/input/event2/device/enabled: 1
D/Launcher.HomeView( 1497): onStart
D/Launcher( 1497): onResume, Launcher: 806022262
D/SettingsProvider(  834): name = kids_home_mode
D/SettingsProvider(  834): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  834): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  834): selectionArgs: false
D/SettingsProvider(  834): selectionArgs: 10008
D/SecContentProvider(  834): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  834): ret = -1
D/Launcher.HomeView( 1497): onResume
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2100): [237392/6] Surface widget resume on instance = 1
D/accuweather( 2100): [KK AccuPhone]>>> SWW:209 [0:0] [SWW] onResume : instance = 1
D/StatusBar.NetworkController( 1182): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/Launcher( 1497): setSystemUiTransparency.SettingNotFoundException : set as TRUE
D/Launcher( 1497): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
D/NfcService( 1477): call the applyRotuiing
D/SamsungIME( 1857): showDlgMsgBox : false true true
V/KeyguardServiceDelegate(  834): **** SHOWN CALLED ****
D/StatusBarKeyguardViewManager( 1182): callback.onShown()
D/StatusBar.NetworkController( 1182): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/DisplayPowerController(  834): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
I/DisplayPowerController(  834): Unblocked screen on after 170 ms
D/DisplayPowerState(  834): !@ ColorFade exit
D/BatteryMeterView( 1182): onDraw batteryColor : -1
I/SurfaceFlinger(  259): id=12 Removed ColorFade (8/8)
I/SurfaceFlinger(  259): id=12 Removed ColorFade (-2/8)
E/libEGL  (  834): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
V/UserPresentBroadcastReceiver( 1558): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/MenuAppsGridFragment( 1497): onResume
D/ActivityManager(  834): handle home activity for 0
I/WallpaperManagerService(  834): switchPersonaWallpaper is called for personaId-0
D/ActivityManager(  834): post active user change for 0
D/KnoxTimeoutHandler(  834): postActiveUserChange for user 0
D/daemonapp( 1337): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
E/SMD     (  294): DCD ON
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/MicrophoneInputStream( 1570): mic_starting gfk@11b2a60
D/StatusBarManagerService(  834): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
V/AudioPolicyManager(  300): getInput() inputSource 1999, samplingRate 16000, format 8, channelMask 1, session 0, flags 0x10
V/AudioPolicyManager(  300): getDeviceForInputSource()input source 1999, device 80000004
V/audio_hw_primary(  300): adev_open_input_stream: enter
E/audio_hw_primary(  300): adev_open_input_stream : jack_config 0
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
E/audio_hw_primary(  300): can not make /data/snd/hal_input.pcm 
E/audio_hw_primary(  300): can not make /data/snd/hal_input_before_ns.pcm 
E/audio_hw_primary(  300): can not make /data/snd/hal_input_after_ns.pcm 
E/audio_hw_primary(  300): adev_open_input_stream input is null, set new input stream
V/audio_hw_primary(  300): adev_open_input_stream: exit
I/AudioFlinger(  300): AudioFlinger's thread 0xaf055000 ready to run
V/audio_hw_primary(  300): in_standby: enter
V/audio_hw_primary(  300): in_standby: exit:  status(0)
I/HotwordRecognitionRnr( 1570): Starting hotword detection.
V/audio_hw_primary(  300): in_standby: enter
V/audio_hw_primary(  300): in_standby: exit:  status(0)
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/Timeline( 1497): Timeline: Activity_idle id: android.os.BinderProxy@13379dbf time:79600
I/EDMNativeHelperService(  834): isMicrophoneEnabled
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
V/AudioPolicyManager(  300): startInput() input 30
V/AudioPolicyManager(  300): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  300): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  300): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  300): DeviceVector::getDevicesFromType() for type 80000004 found 0xb295b3c0
D/InputManager-JNI(  834): sysfs_write -: /sys/class/input/event2/device/enabled: 1
V/audio_hw_primary(  300): in_set_parameters: enter: kvpairs=input_source=6;keyIsHotword=true;routing=-2147483644
V/audio_hw_primary(  300): in_set_parameters: exit: status(11)
V/AudioPolicyManager(  300): setInputDevice() createAudioPatch returned 11 patchHandle 0
V/AudioPolicyManager(  300): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 1570): mic_started gfk@11b2a60
D/GalleryCacheReady( 5343): Receive : home resume
D/daemonapp( 1337): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
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
D/audio_hw_primary(  300): select_devices: in_snd_device(122: vr-main-mic)
D/ACDB-LOADER(  300): ACDB -> send_audio_cal, acdb_id = 53, path =  1
D/ACDB-LOADER(  300): ACDB -> send_adm_topology
D/ACDB-LOADER(  300): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  300): ACDB -> send_asm_topology
D/ACDB-LOADER(  300): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  300): ACDB -> send_audtable
D/ACDB-LOADER(  300): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/        (  300): ACDBFILE_MGR:Read the devices count as zero, please check the acdb file
D/ACDB-LOADER(  300): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  300): ACDB -> send_audvoltable
D/ACDB-LOADER(  300): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  300): ACDBFILE_MGR:Read the devices count as zero, please check the acdb file
D/        (  300): Failed to fetch the lookup information of the device 00000035 
E/ACDB-LOADER(  300): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  300): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  300): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  300): enable_snd_device: snd_device(122: vr-main-mic, vr-main-mic)
D/audio_route(  300): ++++ audio_route_update_mixer ==============
D/audio_route(  300): Setting mixer control: DEC2 Volume
D/audio_route(  300): Setting mixer control: value: 106
D/audio_route(  300): Setting mixer control: SLIM TX7 MUX, value: 9
D/audio_route(  300): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  300): Setting mixer control: value: 1
D/Mms/UIEventReceiver( 5223): ui event
D/audio_route(  300): Setting mixer control: DEC2 MUX, value: 1
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
I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 1
E/qdexternal(  259): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  259): hwc_blank: Done unblanking display: 0
D/SurfaceControl(  834): Excessive delay in setPowerMode(): 272ms
D/lights  (  834): lcd : 8 +
D/lights  (  834): lcd : 8 -
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
D/PowerManagerService(  834): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  834): SecHardwareInterface.setBatteryADC : true
D/PowerManagerService(  834): [input device light] setInputDeviceLightOn is called : 1
D/PowerManagerService(  834): [input device light] handleInputDeviceLightOn
D/lights  (  834): button : 1 +
D/lights  (  834): button : 1 -
W/BroadcastQueue(  834): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1497, uid=10008) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
D/accuweather( 2100): [KK AccuPhone]>>> RM:150 [0:0]  onFirstUpdate :: mFU = false
D/accuweather( 2100): [KK AccuPhone]>>> SWW:223 [0:0]  onResume :: isFirst = false, cnt = 0
D/accuweather( 2100): [KK AccuPhone]>>> SWW:230 [0:0] onResume : size = 1
D/accuweather( 2100): [KK AccuPhone]>>> SWW:512 [0:0]  registerTTReceiver ! 
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6714): MountEmulatedStorage()
E/Zygote  ( 6714): v2
I/libpersona( 6714): KNOX_SDCARD checking this for 10093
I/libpersona( 6714): KNOX_SDCARD not a persona
I/ActivityManager(  834): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6714 uid=10093 gids={50093, 9997} abi=armeabi-v7a
D/accuweather( 2100): [KK AccuPhone]>>> WR:139 [0:0] onResume orientation = 1, from res = Port fHD
D/accuweather( 2100): [KK AccuPhone]>>> SM:523 [0:0] onResume : false, rsStep = 2
I/ServiceManager(  329): Waiting for service AtCmdFwd...
D/AndroidRuntime( 6697): 
D/AndroidRuntime( 6697): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
E/LightSensor(  834): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/LightsService(  834): [SvcLED]  onSensorChanged::light value = 0
D/SensorManager(  834): unregisterListener ::   
D/lights  (  834): led_pattern : 5 +
D/AndroidRuntime( 6697): CheckJNI is OFF
D/AndroidRuntime( 6697): setted country_code = Poland
D/AndroidRuntime( 6697): setted countryiso_code = PL
D/AndroidRuntime( 6697): setted sales_code = XEO
D/AndroidRuntime( 6697): readGMSProperty: start
D/AndroidRuntime( 6697): readGMSProperty: already setted!!
D/AndroidRuntime( 6697): readGMSProperty: end
D/AndroidRuntime( 6697): addProductProperty: start
D/lights  (  834): led_pattern : 5 -
D/LightsService(  834): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/HotwordWorker( 1570): onReady
I/SELinux ( 6714): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6714): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6714): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/daemonapp( 1337): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6728): MountEmulatedStorage()
I/libpersona( 6728): KNOX_SDCARD checking this for 10070
E/Zygote  ( 6728): v2
I/libpersona( 6728): KNOX_SDCARD not a persona
I/ActivityManager(  834): Start proc com.sec.android.widgetapp.ap.hero.accuweather for content provider com.sec.android.widgetapp.ap.hero.accuweather/.provider.accuweather.AccuContentProvider: pid=6728 uid=10070 gids={50070, 9997, 3003, 1028} abi=armeabi-v7a
D/InputManager-JNI(  834): sysfs_write -: /sys/class/input/event1/device/enabled: 1
I/SELinux ( 6728): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6728): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
V/ActivityManager(  834): Display changed displayId=0
E/SELinux ( 6728): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
V/ActivityManager(  834): Display changed displayId=0
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/TimaKeyStoreProvider( 6714): TimaSignature is unavailable
D/ActivityThread( 6714): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
V/BitmapFactory( 1182): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_battery_full.png
D/PalmMotion(  834): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
D/PalmMotion(  834): SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/LightsService(  834): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 834) 
D/LightsService(  834): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService(  834): [SvcLED]  onSensorChanged::light value = 0
D/SensorManager(  834): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/SensorManager(  834): unregisterListener ::   
D/LightsService(  834): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/WallpaperManagerService(  834):  force update = false; persona id = 0; current user =0; current persona = 0
D/SSRM:a  (  834): DeviceInfo:: 000000000000
D/SSRM:a  (  834): SettingsAirViewInfo:: 000000000
D/KnoxTimeoutHandler(  834): handleActiveUserChange for user 0
D/TimaKeyStoreProvider( 6728): TimaSignature is unavailable
D/ActivityThread( 6728): Added TimaKeyStore provider
V/BitmapFactory( 1497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_mic.png
D/LightsService(  834): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 834) 
D/LightsService(  834): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService(  834): turn off LED
D/LightsService(  834): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/lights  (  834): led_pattern : 0 +
D/SLocation(  834): handleMessage got exceptionjava.lang.NullPointerException: Attempt to invoke virtual method 'void com.samsung.location.currentloc.SCurrentLocationManager.handleSCurLocScreenOn()' on a null object reference
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'void com.samsung.location.currentloc.SCurrentLocationManager.handleSCurLocScreenOn()' on a null object reference
W/System.err(  834): 	at com.samsung.location.lib.h.handleMessage(Unknown Source)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/lights  (  834): led_pattern : 0 -
D/LightsService(  834): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at com.samsung.location.SLocationService.run(Unknown Source)
W/System.err(  834): 	at java.lang.Thread.run(Thread.java:818)
D/ResourcesManager( 6714): creating new AssetManager and set to /system/app/DigitalClock/DigitalClock.apk
W/ResourcesManager( 6714): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
V/BitmapFactory( 1182): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_battery_full.png
I/CAE     (  834): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
I/CAE     (  834): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
I/CAE     (  834): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager(  834): SendSensorHubData: send data = -76, 13, -47, 0
D/Sensorhubs(  306): sendContextData: -76, 13, -47, 0
D/InputMethodManagerService(  834): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
D/ResourcesManager( 6728): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 6728): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/Zygote  ( 6751): MountEmulatedStorage()
E/Zygote  ( 6751): v2
I/libpersona( 6751): KNOX_SDCARD checking this for 10102
I/libpersona( 6751): KNOX_SDCARD not a persona
D/KnoxNotification( 1182): ----- inflateViews : modified publicViewLocal -----
W/ResourcesManager( 6728): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6728): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
I/ActivityManager(  834): Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6751 uid=10102 gids={50102, 9997, 3003} abi=armeabi-v7a
D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_SCREEN_ON
I/WifiNative-HAL(  834): startHal
E/wifi    (  834): getStaticLongField sWifiHalHandle 0x958df7fc
D/wifi    (  834): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x70194a
I/WifiNative-HAL(  834): Could not start hal
D/WifiStateMachine(  834): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  834): handleScreenStateChanged Exit: true
E/WifiStateMachine(  834): setSuspendOptimizations: 4 false
E/WifiStateMachine(  834): mSuspendOptNeedsDisabled 4
D/NotificationService(  834): ACTION_SCREEN_ON
D/LightsService(  834): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 834) 
D/LightsService(  834): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
E/MotionRecognitionService(  834):  handler : SCREEN_ON end
D/LightsService(  834): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  834): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
I/SELinux ( 6751): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6751): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6751): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/audio_hw_primary(  300): adev_set_parameters: enter: screen_state=on
V/voice   (  300): voice_set_parameters: enter: screen_state=on
V/voice   (  300): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  300): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  300): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  300): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  300): adev_set_parameters: exit
E/AffinityControl( 6697): AffinityControl: registerfunction enter
I/SecExternalDisplayIntents_Java(  834): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
D/IpRemoteDisplayController(  834): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController(  834): Bridge Server is not available
D/KnoxNotification( 1182): ----- inflateViews : modified KnoxViewLocal -----
D/TimaKeyStoreProvider( 6751): TimaSignature is unavailable
D/PersonaManager( 1182): PersonaID is invalid or persona doesn't exists. : 0
D/ActivityThread( 6751): Added TimaKeyStore provider
D/PhoneStatusBar( 1182): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@158fa3ec
D/SecContentProvider2(  834): uri = 14 selection = getSealedState
D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
D/AndroidRuntime( 6697): Calling main entry com.android.commands.am.Am
I/PhoneStatusBar( 1182): Icon Only
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/comsamsunglog( 6728): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 6728): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 6728): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): There is/are notification(s) 
D/comsamsunglog( 6728): [KK AccuPhone]>>> ==============================================================================================
D/PersonaManagerService(  834): ACTION_SCREEN_ON onReceive
E/PersonaManagerService(  834): inState():  stateMachine is null !!
D/PersonaManagerServiceHandler(  834): MSG_ACTION_SCREEN_ON called
D/ResourcesManager( 6751): creating new AssetManager and set to /system/app/DualClockDigital/DualClockDigital.apk
V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ResourcesManager( 6751): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6751): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
I/ActivityManager(  834): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
,D/ResourcesManager(  834): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ActivityManager(  834): mDVFSHelper.acquire()
D/FocusedStackFrame(  834): Set to : 0
D/Launcher.HomeView( 1497): onPause
D/Launcher( 1497): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/AndroidRuntime( 6697): Shutting down VM
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/comsamsunglog( 6728): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 6728): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 6728): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 6728): [KK AccuPhone]>>> ==============================================================================================
D/SettingsProvider(  834): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  834): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  834): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  834): selectionArgs: false
D/SettingsProvider(  834): selectionArgs: 10070
D/SecContentProvider(  834): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  834): ret = -1
I/NfcService( 1477): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
D/NfcService( 1477): call the applyRotuiing
I/SurfaceFlinger(  259): id=13 createSurf (1x1),1 flag=404, Starting com.example.hello
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
E/Zygote  ( 6770): MountEmulatedStorage()
E/Zygote  ( 6770): v2
I/libpersona( 6770): KNOX_SDCARD checking this for 10191
I/libpersona( 6770): KNOX_SDCARD not a persona
I/ActivityManager(  834): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6770 uid=10191 gids={50191, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/SELinux ( 6770): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6770): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6770): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/TimaKeyStoreProvider( 6770): TimaSignature is unavailable
D/ActivityThread( 6770): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/StatusBarManagerService(  834): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/MicrophoneInputStream( 1570): mic_close gfk@11b2a60
V/WindowOrientationListener(  834): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  834): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  834): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  834): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  834): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/AudioPolicyManager(  300): stopInput() input 30
V/AudioPolicyManager(  300): releaseInput() 30
V/AudioPolicyManager(  300): closeInput(30)
I/HotwordRecognitionRnr( 1570): Hotword detection finished
V/audio_hw_primary(  300): in_standby: enter
I/HotwordRecognitionRnr( 1570): Stopping hotword detection.
D/Launcher.HomeView( 1497): onStop
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
V/ActivityManager(  834): Display changed displayId=0
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2100): [237392/6] Surface widget pause on instance = 1
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2100): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1497): onTrimMemory. Level: 20
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/SurfaceWidgetView( 1497): destroyHardwareResources():434213161
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/StatusBarManagerService(  834): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
V/audio_hw_primary(  300): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  300): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  300): disable_audio_route: reset mixer path: audio-record
D/audio_route(  300): ++++ audio_route_update_mixer ==============
D/audio_route(  300): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  300): Setting mixer control: value: 0
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/audio_route(  300): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  300): disable_audio_route: exit
V/audio_hw_primary(  300): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  300): ++++ audio_route_update_mixer ==============
D/audio_route(  300): Setting mixer control: DEC2 Volume
D/audio_route(  300): Setting mixer control: value: 0
D/audio_route(  300): Setting mixer control: SLIM TX7 MUX, value: 0
D/audio_route(  300): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  300): Setting mixer control: value: 0
D/audio_route(  300): Setting mixer control: DEC2 MUX, value: 0
D/audio_route(  300): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  300): stop_input_stream: exit: status(0)
V/audio_hw_primary(  300): in_standby: exit:  status(0)
V/audio_hw_primary(  300): adev_close_input_stream
V/audio_hw_primary(  300): in_standby: enter
V/audio_hw_primary(  300): in_standby: exit:  status(0)
E/audio_hw_primary(  300): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  300): releaseInput() exit
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 6770): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
E/Zygote  ( 6786): MountEmulatedStorage()
E/Zygote  ( 6786): v2
I/libpersona( 6786): KNOX_SDCARD checking this for 10112
I/libpersona( 6786): KNOX_SDCARD not a persona
I/ActivityManager(  834): Start proc com.sec.android.GeoLookout for broadcast com.sec.android.GeoLookout/.widget.SafetyCareWidget: pid=6786 uid=10112 gids={50112, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  834): Killing 5038:com.sec.spp.push/u0a37 (adj 15): bgCount ##41
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/SELinux ( 6786): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6786): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6786): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,E/SQLiteLog( 1654): (10) POSIX Error : 11 SQLite Error : 3850
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/daemonapp( 1337): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/SurfaceWidgetView( 1497): destroyHardwareResources():434213161
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/TimaKeyStoreProvider( 6786): TimaSignature is unavailable
,D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/ActivityThread( 6786): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1182): value : false
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,W/libprocessgroup(  834): failed to open /acct/uid_10037/pid_5038/cgroup.procs: No such file or directory
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/accuweather( 2100): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
I/SamsungIME( 1857): getNextShiftState() cursorCapsMode : 0
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ResourcesManager( 6786): creating new AssetManager and set to /system/app/GeoLookout/GeoLookout.apk
,D/daemonapp( 1337): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 2100): [KK AccuPhone]>>> SM:442 [0:0] updateView iSA = false, mCI = 0, mSL = null , cls = 0 , cls = 1
,D/accuweather( 2100): [KK AccuPhone]>>> SM:447 [0:0] bg transparency val = 0
D/accuweather( 2100): [KK AccuPhone]>>> SM:679 [0:0] [sCCTZ] set default tZ
,D/accuweather( 2100): [KK AccuPhone]>>> SM:1044 [0:0] setLayoutContentEmptyMsg = 2131558522
,D/accuweather( 2100): [KK AccuPhone]>>> U:1012 [0:0] icon = 99, isDay = true, type = 261
,D/accuweather( 2100): [KK AccuPhone]>>> U:1187 [0:0] resID = 2130837848
D/accuweather( 2100): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
I/art     (  834): Explicit concurrent mark sweep GC freed 34960(2047KB) AllocSpace objects, 10(160KB) LOS objects, 31% free, 35MB/51MB, paused 5.686ms total 174.049ms
,D/daemonapp( 1337): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/SurfaceWidget.Renderer( 2100): [237392/6] SurfaceWidget drawing first frame
,D/accuweather( 2100): [KK AccuPhone]>>> SM:1072 [0:0] complete setLayoutContentEmptyMsg Content
,D/accuweather( 2100): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
,D/accuweather( 2100): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2100): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
,D/accuweather( 2100): [KK AccuPhone]>>> WR:132 [0:0] onPause
,D/accuweather( 2100): [KK AccuPhone]>>> SM:538 [0:0] onPause
,I/ActivityManager(  834): Killing 5384:com.samsung.android.sdk.samsunglink/u0a41 (adj 15): bgCount ##41
,D/accuweather( 2100): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 2100): [KK AccuPhone]>>> SWW:479 [0:0] doChangeDayOrNight : 1
,D/accuweather( 2100): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
D/accuweather( 2100): [KK AccuPhone]>>> SWW:496 [0:0] makeClock : 1
,D/accuweather( 2100): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
D/accuweather( 2100): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
I/WebViewFactory( 6770): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 6770): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
W/GeoLookout( 6786): H: zOXtzplbN+8pOR8lXMN+zuVFxvDlCo+Yzxg4ugbhd7A04DIT5nFf+o6jguBECoC9dC8nZsnXtcP6wJ/Do8CKbApjnmitl3AiTeKReyJRDttBktCZIh1mNkZuovfXxXoAjd37PhyBM3ng3bcKYjYGOEDyKJaWZrwK1FfNJWfEtzYH8n1Joa422xGgCu3P2tNC0syzQpcTEb6CNvuJmw0Apg==
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/LibraryLoader( 6770): Loading: webviewchromium
I/GeoLookout( 6786): H: zOXtzplbN+8pOR8lXMN+zq5rYKS75KQLo4xvOOBhIY6eGw1/GT6WQYb1SRYOugxmkGHzev/Lb2j+GB0+6UGDnw==
I/LibraryLoader( 6770): Time to load native libraries: 2 ms (timestamps 381-383)
I/LibraryLoader( 6770): Expected native library version number "",actual native library version number ""
,D/SettingsProvider(  834): name = safetycare_geolookout_registering
D/SettingsProvider(  834): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  834): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  834): selectionArgs: false
D/SettingsProvider(  834): selectionArgs: 10112
D/SecContentProvider(  834): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  834): ret = -1
,D/SurfaceWidget.Renderer( 2100): [237392/6] SurfaceWidget drawing first frame
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/GeoLookout( 6786): H: mmqeDLqBgrS1PY9ZxjAERmjpyYDSyckxRVEBLahXFCCjxEHkYkZuzwjV7ldL9/y2wUiG8ZXusFQQzoKG1FCUjw==
,D/GeoLookout( 6786): H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
,V/WebViewChromiumFactoryProvider( 6770): Binding Chromium to main looper Looper (main, tid 1) {284fc24c}
,I/LibraryLoader( 6770): Expected native library version number "",actual native library version number ""
D/GeoLookout( 6786): H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDnr4brh3hp83PTv8sTeWgfzb09Wu8w+l9FeW3bXb18r1tcp17zAuCthjNMD7/ctUpMsPOZWZzY9gg1XBOkZWTGk
I/chromium( 6770): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6770): Initializing chromium process, renderers=0
,W/art     ( 6770): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/GeoLookout( 6786): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
,D/GeoLookout( 6786): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
,D/GeoLookout( 6786): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
,D/GeoLookout( 6786): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
,D/GeoLookout( 6786): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
,D/GeoLookout( 6786): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,W/chromium( 6770): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  834): failed to open /acct/uid_10041/pid_5384/cgroup.procs: No such file or directory
D/GeoLookout( 6786): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
,W/chromium( 6770): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6770): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium( 6770): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/GeoLookout( 6786): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/GeoLookout( 6786): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1MpblPvMyD8bF5o9h5mVT9aba68PSLy9IpSfBXGHVgOg==
,D/BluetoothAdapter( 6770): 166793877: getState() :  mService = null. Returning STATE_OFF
,I/Adreno-EGL( 6770): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6770): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6770): Build Date: 03/03/15 Tue
I/Adreno-EGL( 6770): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 6770): Remote Branch: 
I/Adreno-EGL( 6770): Local Patches: 
I/Adreno-EGL( 6770): Reconstruct Branch: 
,I/SystemBroadcastReceiver( 6442): [#DCM#] [DCM_Performance] onReceive completed in time  406 microsec. 
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/SystemBroadcastReceiver( 6442): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 6442): [#DCM#] onReceive action = EVENT_SCREEN_ON
I/DCMController( 6442): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_ON
D/PowerManagerService(  834): [PWL] sb release: PowerManagerService.Broadcasts
,D/SurfaceWidget.Renderer( 2100): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2100): [237392/6] SurfaceWidget drawing first frame
,D/SSRM:m  (  834): SIOP:: AP = 320, PST = 393, CUR = 450
,D/GeoLookout( 6786): H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
D/GeoLookout( 6786): H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDnr4brh3hp83PTv8sTeWgfzb09Wu8w+l9FeW3bXb18r1tcp17zAuCthjNMD7/ctUpMsPOZWZzY9gg1XBOkZWTGk
,D/GeoLookout( 6786): H: oG7yKmvlgCB+MeB9ScCFjVjhROowReQZ6uZ83+PHbxXxfrUuNQHmPlY4PsIKqeHXpHMfmw7BKa8EvZP1XFE95vEpSHlOxg9XQoR6KQvcMJUezCj+VlRSvYmiaFKv4yMdF9ANJ7ri8t1rvBR++sDAZA==
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,E/Zygote  ( 6818): MountEmulatedStorage()
E/Zygote  ( 6818): v2
I/libpersona( 6818): KNOX_SDCARD checking this for 10153
I/libpersona( 6818): KNOX_SDCARD not a persona
,I/ActivityManager(  834): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6818 uid=10153 gids={50153, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/ActivityManager(  834): Killing 5054:com.osp.app.signin/u0a44 (adj 15): bgCount ##41
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
I/SELinux ( 6818): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1182): value : false
,I/SELinux ( 6818): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6818): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,W/chromium( 6770): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,D/TimaKeyStoreProvider( 6818): TimaSignature is unavailable
,D/ActivityThread( 6818): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,W/chromium( 6770): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 6770): Attempt to remove local handle scope entry from IRT, ignoring
,D/ResourcesManager( 6818): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,W/AwContents( 6770): onDetachedFromWindow called when already detached. Ignoring
,W/ResourcesManager( 6818): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6818): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6818): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 6818): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,W/libprocessgroup(  834): failed to open /acct/uid_10044/pid_5054/cgroup.procs: No such file or directory
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/SystemWebViewEngine( 6770): CordovaWebView is running on device made by: samsung
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,W/art     ( 6770): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6770): Attempt to remove local handle scope entry from IRT, ignoring
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/SurfaceFlinger(  259): id=6 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/8)
,I/SurfaceFlinger(  259): id=6 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/8)
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,V/TaskCloserActivity( 6423): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,I/ActivityManager(  834): Killing 5800:com.sec.android.app.myfiles/u0a50 (adj 15): bgCount ##41
,D/Finsky  ( 6179): [1015] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6179): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/TaskCloserActivity( 6423): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/ActivityManager(  834): Killing 5832:com.sec.android.app.soundalive/u0a57 (adj 15): bgCount ##41
D/daemonapp( 1337): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
D/daemonapp( 1337): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
,D/daemonapp( 1337): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/daemonapp( 1337): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1337): [MSC_Daemon]>>> WDSM:41 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1337): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1337): [MSC_Daemon]>>> daemonapp [Version : 15010801 ] [ 2 ] 
D/comsamsunglog( 1337): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1337): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1337): [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
D/daemonapp( 1337): [MSC_Daemon]>>> WDSM:418 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 1337): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1337): [MSC_Daemon]>>> WDSM:421 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1337): [MSC_Daemon]>>> WDSM:422 [0:0] [ASO][NUT] = 1448328060000
D/daemonapp( 1337): [MSC_Daemon]>>> WDSM:423 [0:0] [ASO][CT] = 1448306552939
,D/daemonapp( 1337): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/daemonapp( 1337): [MSC_Daemon]>>> WU:1622 [0:0] PakNme size = 5
,D/Activity( 6770): performCreate Call secproduct feature valuefalse
D/Activity( 6770): performCreate Call debug elastic valuetrue
,D/daemonapp( 1337): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,D/daemonapp( 1337): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
,D/daemonapp( 1337): [MSC_Daemon]>>> WU:1626 [0:0] CP Name cp_eng
D/OpenGLRenderer( 6770): Render dirty regions requested: true
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/daemonapp( 1337): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/ActivityManager(  834): post active user change for 0
D/KnoxTimeoutHandler(  834): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  834): handleActiveUserChange for user 0
,E/daemonapp( 1337): [MSC_Daemon]>>> WU:1606 [0:0] [NameNotFoundException] !!
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
W/libprocessgroup(  834): failed to open /acct/uid_10050/pid_5800/cgroup.procs: No such file or directory
,W/libprocessgroup(  834): failed to open /acct/uid_10057/pid_5832/cgroup.procs: No such file or directory
,I/SurfaceFlinger(  259): id=14 createSurf (1x1),1 flag=404, com.example.hello/com.example.hello.MainActivity
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/OpenGLRenderer( 6770): Initialized EGL, version 1.4
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/OpenGLRenderer( 6770): HWUI protection enabled for context ,  &this =0xa1a53060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 6770): Enabling debug mode 0
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,E/LightSensor(  834): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/InputMethodManagerService(  834): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,I/Timeline( 6770): Timeline: Activity_idle id: android.os.BinderProxy@206e567c time:80840
,I/ActivityManager(  834): Displayed com.example.hello/.MainActivity: +853ms
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,I/chromium( 6770): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 6770): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,W/ActivityManager(  834): mDVFSHelper.release()
I/Timeline(  834): Timeline: Activity_windows_visible id: ActivityRecord{3614a95c u0 com.example.hello/.MainActivity t3} time:80894
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/CustomFrequencyManagerService(  834): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 834  pkgName : ACTIVITY_RESUME_BOOSTER@10
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/JsMessageQueue( 6770): Set native->JS mode to OnlineEventsBridgeMode
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,I/chromium( 6770): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6770): 
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,E/LightSensor(  834): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/SurfaceFlinger(  259): id=13 Removed Starting com.example.hello (6/8)
I/SurfaceFlinger(  259): id=13 Removed Starting com.example.hello (-2/8)
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
E/Adreno-ES20( 6770): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6770): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
D/jxcore_app_log( 6770): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1359654272
D/JX-Cordova( 6770): jxcore cordova android initializing
E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
D/PowerManagerService(  834): [input device light] handleInputDeviceLightOff
D/lights  (  834): button : 0 +
W/jxcore-log( 6770): Initializing JXcore engine
W/jxcore-log( 6770): JXcore engine is ready
W/jxcore-log( 6770): Starting JXcore engine
D/CustomFrequencyManagerService(  834): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 834  tag : ACTIVITY_RESUME_BOOSTER@10
D/lights  (  834): button : 0 -
D/SSRM:a  (  834): DeviceInfo:: 000000000000
D/SSRM:a  (  834): SettingsAirViewInfo:: 000000000
E/auditd  ( 2160): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService(  834): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
D/SecurityLogAgent:SEDenialService(  834): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6856): MountEmulatedStorage()
I/libpersona( 6856): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6856): v2
I/libpersona( 6856): KNOX_SDCARD not a persona
I/ActivityManager(  834): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6856 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 6856): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6856): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6856): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6856): TimaSignature is unavailable
D/ActivityThread( 6856): Added TimaKeyStore provider
D/ResourcesManager( 6856): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
W/jxcore-log( 6770): Platform android
W/jxcore-log( 6770): 
W/jxcore-log( 6770): Process ARCH arm
W/jxcore-log( 6770): 
E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
D/SecurityLogAgent( 6856):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
D/SecurityLogAgent( 6856):  SeDenialReceiver : File path = null
I/ActivityManager(  834): Killing 5875:com.google.android.apps.docs/u0a97 (adj 15): bgCount ##41
I/jxcore-log( 6770): JXcore Cordova bridge is ready!
I/jxcore-log( 6770): 
W/jxcore-log( 6770): JXcore engine is started
W/libprocessgroup(  834): failed to open /acct/uid_10097/pid_5875/cgroup.procs: No such file or directory
E/jxcore-log( 6770): >> samsung-SM-G900F
E/jxcore-log( 6770): 
I/jxcore-log( 6770): Total memory 1787449344
I/jxcore-log( 6770): 
I/jxcore-log( 6770): Free memory 60264448
I/jxcore-log( 6770): 
I/jxcore-log( 6770): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6770): 
I/jxcore-log( 6770): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6770): 
I/jxcore-log( 6770): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6770): 
I/jxcore-log( 6770): Size 1080 1920
I/jxcore-log( 6770): 
I/jxcore-log( 6770): Screen Brightness 134
I/jxcore-log( 6770): 
E/jxcore-log( 6770): Dummy Error Log.
E/jxcore-log( 6770): 
E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,I/jxcore-log( 6770): getBuffer is called!!!!
I/jxcore-log( 6770): 
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,E/SMD     (  294): DCD ON
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/GeoLookout( 6786): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
,D/GeoLookout( 6786): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
,D/GeoLookout( 6786): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
,D/GeoLookout( 6786): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
,D/GeoLookout( 6786): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
,D/GeoLookout( 6786): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
,D/GeoLookout( 6786): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
,D/GeoLookout( 6786): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
,E/SMD     (  294): DCD ON
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/BluetoothAdapter( 6770): disable()
,E/BluetoothManagerService(  834): Bluetooth is already disabled. DO NOT disable again.
,D/WifiService(  834): New client listening to asynchronous messages
,I/WifiManager( 6770): packageName : com.example.hello
,D/SecContentProvider(  834): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  834): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  834): mCursor = null
,D/WifiService(  834): setWifiEnabled: false pid=6770, uid=10191
E/WifiService(  834): Invoking mWifiStateMachine.setWifiEnabled
D/SettingsProvider(  834): name = wifi_on
,I/jxcore-log( 6770): ****TEST TOOK:  5064  ms ****
I/jxcore-log( 6770): 
,I/jxcore-log( 6770): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6770): 
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/AndroidRuntime( 6894): 
D/AndroidRuntime( 6894): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6894): CheckJNI is OFF
,D/AndroidRuntime( 6894): setted country_code = Poland
,D/AndroidRuntime( 6894): setted countryiso_code = PL
D/AndroidRuntime( 6894): setted sales_code = XEO
,D/AndroidRuntime( 6894): readGMSProperty: start
D/AndroidRuntime( 6894): readGMSProperty: already setted!!
D/AndroidRuntime( 6894): readGMSProperty: end
D/AndroidRuntime( 6894): addProductProperty: start
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/AffinityControl( 6894): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6894): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  834): START PACKAGE DELETE: observer{475281339}
D/PackageManager(  834): pkg{<packageName>}
D/PackageManager(  834): user{0}
D/PackageManager(  834): caller{2000}
D/PackageManager(  834): flags{3}
D/PersonaManagerService(  834): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,D/PersonaManagerService(  834): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  834): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  834): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager(  834): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  834): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  834): deletePackage- pkg:com.example.hello, edmuserId:0
,D/PackageManagerService(  834): deletePackage- pkg:com.example.hello, edmuserId:-1
,D/ApplicationPolicy(  834): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  834): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  834): !@killApplicatoin: 10191, uninstall pkg
,I/ActivityManager(  834): Force stopping com.example.hello appid=10191 user=-1: uninstall pkg
,I/ActivityManager(  834): Killing 6770:com.example.hello/u0a191 (adj 0): stop com.example.hello
W/ActivityManager(  834): Force removing ActivityRecord{3614a95c u0 com.example.hello/.MainActivity t3}: app died, no saved state
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/SurfaceFlinger(  259): id=14 Removed com.example.hello/com.example.hello.MainActivity (5/7)
I/SurfaceFlinger(  259): id=14 Removed com.example.hello/com.example.hello.MainActivity (-2/7)
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/FocusedStackFrame(  834): Set to : 0
,D/CustomFrequencyManagerService(  834): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 834  pkgName : ACTIVITY_RESUME_BOOSTER@6
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,W/ActivityManager(  834): mDVFSHelper.acquire()
,V/WindowOrientationListener(  834): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  834): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  834): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  834): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  834): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/SQLiteSecureOpenHelper( 3329): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3329): getDatabaseLocked(b,b,pwd)...
,D/SurfaceWidgetView( 1497): destroyHardwareResources():434213161
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/WifiService(  834): Client connection lost with reason: 4
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,W/PackageSettings(  834): Skipping PackageSetting{3ab8b51a com.test.thalitest/10356} due to missing metadata
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  834): Force stopping com.example.hello appid=10191 user=0: pkg removed
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/Launcher( 1497): onRestart, Launcher: 806022262
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/art     ( 4451): Explicit concurrent mark sweep GC freed 3484(195KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 14MB/23MB, paused 482us total 19.132ms
,D/Launcher( 1497): onStart, Launcher: 806022262
D/Launcher.HomeView( 1497): onStart
,D/Launcher( 1497): onResume, Launcher: 806022262
,D/SettingsProvider(  834): name = kids_home_mode
,D/SettingsProvider(  834): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  834): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  834): selectionArgs: false
D/SettingsProvider(  834): selectionArgs: 10008
,D/SecContentProvider(  834): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  834): ret = -1
D/Launcher.HomeView( 1497): onResume
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2100): [237392/6] Surface widget resume on instance = 1
,D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/Launcher( 1497): setSystemUiTransparency.SettingNotFoundException : set as TRUE
D/Launcher( 1497): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,D/accuweather( 2100): [KK AccuPhone]>>> SWW:209 [0:0] [SWW] onResume : instance = 1
,D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/InputReader(  834): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1857): mOCRHelper is null
,W/GeofencerStateMachine( 1558): Ignoring removeGeofence because network location is disabled.
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6916): MountEmulatedStorage()
E/Zygote  ( 6916): v2
I/libpersona( 6916): KNOX_SDCARD checking this for 10018
I/libpersona( 6916): KNOX_SDCARD not a persona
,I/ActivityManager(  834): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6916 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/talkback/talkback.apk
,I/SELinux ( 6916): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6916): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6916): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/daemonapp( 1337): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/MenuAppsGridFragment( 1497): onResume
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2100): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2100): [237392/6] SurfaceWidget drawing first frame
D/ActivityManager(  834): handle home activity for 0
,I/WallpaperManagerService(  834): switchPersonaWallpaper is called for personaId-0
D/ActivityManager(  834): post active user change for 0
D/KnoxTimeoutHandler(  834): postActiveUserChange for user 0
,I/SurfaceFlinger(  259): id=15 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/StatusBarManagerService(  834): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/art     (  834): Explicit concurrent mark sweep GC freed 23358(1788KB) AllocSpace objects, 8(128KB) LOS objects, 31% free, 35MB/51MB, paused 1.359ms total 103.781ms
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/art     (  834): WaitForGcToComplete blocked for 57.335ms for cause Explicit
,D/ResourcesManager(  834): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/EnterpriseDeviceManagerService(  834): Package has changed for user 0
D/EnterpriseDeviceManagerService(  834): Admin package name: com.google.android.gms
,E/LightSensor(  834): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/TimaKeyStoreProvider( 6916): TimaSignature is unavailable
,D/ActivityThread( 6916): Added TimaKeyStore provider
,D/daemonapp( 1337): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 1497): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 1497): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/accuweather( 2100): [KK AccuPhone]>>> RM:150 [0:0]  onFirstUpdate :: mFU = false
D/accuweather( 2100): [KK AccuPhone]>>> SWW:223 [0:0]  onResume :: isFirst = false, cnt = 0
,D/accuweather( 2100): [KK AccuPhone]>>> SWW:230 [0:0] onResume : size = 1
D/accuweather( 2100): [KK AccuPhone]>>> SWW:512 [0:0]  registerTTReceiver ! 
W/ResourcesManager( 1497): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1497): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/accuweather( 2100): [KK AccuPhone]>>> WR:139 [0:0] onResume orientation = 1, from res = Port fHD
D/accuweather( 2100): [KK AccuPhone]>>> SM:523 [0:0] onResume : false, rsStep = 2
,D/daemonapp( 1337): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ResourcesManager( 1497): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 1497): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1497): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/Launcher( 1497): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 1497): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,D/InputMethodManagerService(  834): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager( 6916): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/daemonapp( 1337): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 2100): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,W/InputMethodManagerService(  834): Got RemoteException sending setActive(false) notification to pid 6770 uid 10191
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/daemonapp( 1337): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/accuweather( 2100): [KK AccuPhone]>>> SM:442 [0:0] updateView iSA = false, mCI = 0, mSL = null , cls = 0 , cls = 1
D/accuweather( 2100): [KK AccuPhone]>>> SM:447 [0:0] bg transparency val = 0
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/accuweather( 2100): [KK AccuPhone]>>> SM:679 [0:0] [sCCTZ] set default tZ
D/accuweather( 2100): [KK AccuPhone]>>> SM:1044 [0:0] setLayoutContentEmptyMsg = 2131558522
,D/accuweather( 2100): [KK AccuPhone]>>> U:1012 [0:0] icon = 99, isDay = true, type = 261
D/accuweather( 2100): [KK AccuPhone]>>> U:1187 [0:0] resID = 2130837848
D/accuweather( 2100): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
,I/HotwordRecognitionRnr( 1570): Starting hotword detection.
,I/MicrophoneInputStream( 1570): mic_starting gfk@189585b7
,V/AudioPolicyManager(  300): getInput() inputSource 1999, samplingRate 16000, format 8, channelMask 1, session 0, flags 0x10
V/AudioPolicyManager(  300): getDeviceForInputSource()input source 1999, device 80000004
V/audio_hw_primary(  300): adev_open_input_stream: enter
E/audio_hw_primary(  300): adev_open_input_stream : jack_config 0
,E/audio_hw_primary(  300): can not make /data/snd/hal_input.pcm 
E/audio_hw_primary(  300): can not make /data/snd/hal_input_before_ns.pcm 
E/audio_hw_primary(  300): can not make /data/snd/hal_input_after_ns.pcm 
E/audio_hw_primary(  300): adev_open_input_stream input is null, set new input stream
V/audio_hw_primary(  300): adev_open_input_stream: exit
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/AudioFlinger(  300): AudioFlinger's thread 0xaf046000 ready to run
V/audio_hw_primary(  300): in_standby: enter
V/audio_hw_primary(  300): in_standby: exit:  status(0)
,V/audio_hw_primary(  300): in_standby: enter
V/audio_hw_primary(  300): in_standby: exit:  status(0)
,I/EDMNativeHelperService(  834): isMicrophoneEnabled
,V/AudioPolicyManager(  300): startInput() input 32
,V/AudioPolicyManager(  300): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  300): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  300): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  300): DeviceVector::getDevicesFromType() for type 80000004 found 0xb295b3c0
,V/audio_hw_primary(  300): in_set_parameters: enter: kvpairs=input_source=6;keyIsHotword=true;routing=-2147483644
V/audio_hw_primary(  300): in_set_parameters: exit: status(11)
V/AudioPolicyManager(  300): setInputDevice() createAudioPatch returned 11 patchHandle 0
V/AudioPolicyManager(  300): AudioPolicyManager::startInput() input source = 1999
,I/MicrophoneInputStream( 1570): mic_started gfk@189585b7
,D/SecContentProvider2(  834): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  834): mCursor = null
,D/RegisteredServicesCache( 1477): empty dynamic service
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,V/msm8974_platform(  300): platform_update_usecase_from_source: input source :6
V/audio_hw_primary(  300): start_input_stream: enter: usecase(7)
V/voice   (  300): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  300): start_input_stream: usecase(7)
D/PreProcess(  300): new SamsungRecord
D/PreProcess(  300): new NS
I/samsungRecord(  300): [samsungrecord] SamsungRecInit 
,I/samsungRecord(  300): [samsungrecordMIC]Use HardCoding Values
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
D/audio_hw_primary(  300): select_devices: in_snd_device(122: vr-main-mic)
D/ACDB-LOADER(  300): ACDB -> send_audio_cal, acdb_id = 53, path =  1
D/ACDB-LOADER(  300): ACDB -> send_adm_topology
D/ACDB-LOADER(  300): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  300): ACDB -> send_asm_topology
D/ACDB-LOADER(  300): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  300): ACDB -> send_audtable
D/ACDB-LOADER(  300): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/        (  300): ACDBFILE_MGR:Read the devices count as zero, please check the acdb file
D/ACDB-LOADER(  300): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  300): ACDB -> send_audvoltable
D/ACDB-LOADER(  300): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  300): ACDBFILE_MGR:Read the devices count as zero, please check the acdb file
D/        (  300): Failed to fetch the lookup information of the device 00000035 
E/ACDB-LOADER(  300): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  300): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  300): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  300): enable_snd_device: snd_device(122: vr-main-mic, vr-main-mic)
D/audio_route(  300): ++++ audio_route_update_mixer ==============
D/audio_route(  300): Setting mixer control: DEC2 Volume
D/audio_route(  300): Setting mixer control: value: 106
,D/audio_route(  300): Setting mixer control: SLIM TX7 MUX, value: 9
,D/WallpaperManager( 1497): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/audio_route(  300): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  300): Setting mixer control: value: 1
,D/WallpaperManager( 1497): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
D/audio_route(  300): Setting mixer control: DEC2 MUX, value: 1
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/audio_route(  300): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  300): enable_audio_route: enter: usecase(7)
V/audio_hw_primary(  300): enable_audio_route: apply mixer path: audio-record
D/audio_route(  300): ++++ audio_route_update_mixer ==============
D/audio_route(  300): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  300): Setting mixer control: value: 1
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/WallpaperManager( 1497): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
D/audio_route(  300): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  300): enable_audio_route: exit
V/audio_hw_primary(  300): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
,D/StatusBarManagerService(  834): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
V/audio_hw_primary(  300): start_input_stream: exit
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/SurfaceWidget.Renderer( 2100): [237392/6] SurfaceWidget drawing first frame
D/accuweather( 2100): [KK AccuPhone]>>> SM:1072 [0:0] complete setLayoutContentEmptyMsg Content
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/Timeline( 1497): Timeline: Activity_idle id: android.os.BinderProxy@13379dbf time:87409
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
I/KLMS-2.4.503: ( 6916): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Books/Books.apk
I/KLMS-2.4.503: ( 6916): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1448306559666
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/KLMS-2.4.503: ( 6916): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.503: ( 6916): MainReciver(): REPLACING: false | pkgName: com.example.hello
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/LightSensor(  834): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,I/HotwordWorker( 1570): onReady
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SurfaceWidget.Renderer( 2100): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2100): [237392/6] SurfaceWidget drawing first frame
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/art     (  834): Explicit concurrent mark sweep GC freed 8840(534KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 35MB/51MB, paused 3.934ms total 248.859ms
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ResourcesManager(  834): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/CustomFrequencyManagerService(  834): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 834  tag : ACTIVITY_RESUME_BOOSTER@6
,D/RCPManagerService(  834): PackageReceiver onReceive()
I/HarmonyEASService(  834): onReceive : android.intent.action.PACKAGE_REMOVED for 0
W/ActivityManager(  834): mDVFSHelper.release()
D/CustomFrequencyManagerService(  834): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 834  pkgName : ACTIVITY_RESUME_BOOSTER@10
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/KnoxMUMContainerPolicy(  834): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  834): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  834): Receieved: android.intent.action.PACKAGE_REMOVED
,E/Zygote  ( 6941): MountEmulatedStorage()
I/libpersona( 6941): KNOX_SDCARD checking this for 10103
E/Zygote  ( 6941): v2
I/libpersona( 6941): KNOX_SDCARD not a persona
,V/EnterpriseBillingPolicy(  834): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  834): uID is 10191
V/EnterpriseBillingPolicy(  834): Removed Packageuid is0
,V/EnterpriseBillingPolicyStorage(  834): getProfileForApplication - enter
I/ActivityManager(  834): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6941 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
,V/EnterpriseBillingPolicyStorage(  834): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  834): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  834): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  834): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage(  834): getBillingProfileForVpnEngine - end - null
,I/ActivityManager(  834): Killing 5936:com.vlingo.midas/u0a32 (adj 15): bgCount ##41
,D/TaskPersister(  834): removeObsoleteFile: deleting file=3_task.xml
,D/WallpaperManagerService(  834):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler(  834): handleActiveUserChange for user 0
,I/art     (  322): Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 271us total 12.178ms
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.763ms
,W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 8.014ms
,W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/PackageManager(  834): delete codoeFile: 
,D/PackageManager(  834): result of delete: 1{475281339}
,I/SELinux ( 6941): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/SELinux ( 6941): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6941): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/BitmapFactory( 1497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_mic.png
,D/AndroidRuntime( 6894): Shutting down VM
,W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Drive/Drive.apk
,W/libprocessgroup(  834): failed to open /acct/uid_10032/pid_5936/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6941): TimaSignature is unavailable
,D/ActivityThread( 6941): Added TimaKeyStore provider
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ResourcesManager( 6941): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,W/ResourcesManager(  834): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  834): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(  834): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  834): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ResourcesManager(  834): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/elm:14451( 6941): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 6941): ELMEngine.ELMEngine( context ).
,D/elm:14451( 6941): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/elm:14451( 6941): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,D/elm:14451( 6941): ElmAgentService : onCreate()
D/elm:14451( 6941): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 6941): MainReceiver.listeningToPackageRemoved()
,D/elm:14451( 6941): MDMBridge.getInstance()
D/elm:14451( 6941): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/elm:14451( 6941): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 6957): MountEmulatedStorage()
I/libpersona( 6957): KNOX_SDCARD checking this for 10016
E/Zygote  ( 6957): v2
I/libpersona( 6957): KNOX_SDCARD not a persona
,I/ActivityManager(  834): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6957 uid=10016 gids={50016, 9997} abi=armeabi-v7a
,W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,I/Timeline(  834): Timeline: Activity_windows_visible id: ActivityRecord{175727b5 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:87660
,W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 6957): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/SELinux ( 6957): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6957): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/UsbSettingsManager(  834): clearDefaults: com.example.hello
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/CrashAnrDetector(  834): onPackageRemoved : com.example.hello
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/elm:14451( 6941): ElmAgentService : onDestroy().
,I/ActivityManager(  834): Killing 5917:com.sec.android.automotive.drivelink/u0a98 (adj 15): bgCount ##41
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/TimaKeyStoreProvider( 6957): TimaSignature is unavailable
,D/ActivityThread( 6957): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ResourcesManager( 6957): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 6957): onReceive()
,I/com.sec.android.service.health.upgrade.UninstallReceiver( 6957): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6957): onReceive() : package name is not s health. Return !!!
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  834): failed to open /acct/uid_10098/pid_5917/cgroup.procs: No such file or directory
,E/Zygote  ( 6974): MountEmulatedStorage()
E/Zygote  ( 6974): v2
I/libpersona( 6974): KNOX_SDCARD checking this for 1000
I/libpersona( 6974): KNOX_SDCARD not a persona
,I/ActivityManager(  834): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6974 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  834): Killing 5971:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,I/SELinux ( 6974): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6974): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6974): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  834): failed to open /acct/uid_10003/pid_5971/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6974): TimaSignature is unavailable
,D/ActivityThread( 6974): Added TimaKeyStore provider
,D/ResourcesManager( 6974): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,E/LightSensor(  834): RED : 0, GREEN : 1, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=-1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/PCWCLIENTTRACE_LOG( 6974): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 6974): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 6974): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 6974): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6974): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6974): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6974): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,D/CustomFrequencyManagerService(  834): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 834  tag : ACTIVITY_RESUME_BOOSTER@10
,E/Zygote  ( 6989): MountEmulatedStorage()
I/libpersona( 6989): KNOX_SDCARD checking this for 10037
E/Zygote  ( 6989): v2
I/libpersona( 6989): KNOX_SDCARD not a persona
,I/ActivityManager(  834): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=6989 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6989): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6989): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/ActivityManager(  834): Killing 5986:com.sec.android.provider.logsprovider/u0a19 (adj 15): bgCount ##41
E/SELinux ( 6989): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6989): TimaSignature is unavailable
,D/ActivityThread( 6989): Added TimaKeyStore provider
,D/ResourcesManager( 6989): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/libprocessgroup(  834): failed to open /acct/uid_10019/pid_5986/cgroup.procs: No such file or directory
,E/SPPClientService( 6989): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6989): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 6989): PushLog.txt file is not deleted.
,D/SPPClientService( 6989): PushLog.txt file is not deleted.
D/SPPClientService( 6989): ============PushLog. stop!
,E/SQLiteDatabase( 6989): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 6989): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6989): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6989): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6989): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6989): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6989): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6989): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6989): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteDatabase( 6989): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteDatabase( 6989): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6989): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteDatabase( 6989): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6989): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6989): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6989): 	at com.sec.spp.push.h.a.a(Unknown Source)
E/SQLiteDatabase( 6989): 	at com.sec.spp.push.h.c.d(Unknown Source)
E/SQLiteDatabase( 6989): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 6989): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 6989): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.onReceive(Unknown Source)
E/SQLiteDatabase( 6989): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2945)
E/SQLiteDatabase( 6989): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 6989): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1499)
E/SQLiteDatabase( 6989): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6989): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6989): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/SQLiteDatabase( 6989): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6989): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6989): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6989): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SPPClientService( 6989): [c] [getAppId()] SQLiteException with message =not an error (code 0): Could not open the database in read/write mode.
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7008): MountEmulatedStorage()
E/Zygote  ( 7008): v2
I/libpersona( 7008): KNOX_SDCARD checking this for 10037
I/libpersona( 7008): KNOX_SDCARD not a persona
I/ActivityManager(  834): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7008 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  834): Killing 6005:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
I/EventHub(  834): Removing device '/dev/input/event4' due to inotify event
,I/SELinux ( 7008): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0014
,E/SELinux ( 7008): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7008): TimaSignature is unavailable
,D/ActivityThread( 7008): Added TimaKeyStore provider
,I/EventHub(  834): Removing device '/dev/input/event5' due to inotify event
,D/ResourcesManager( 7008): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/libprocessgroup(  834): failed to open /acct/uid_1000/pid_6005/cgroup.procs: No such file or directory
,E/SPPClientService( 7008): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 7008): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7008): PushLog.txt file is not deleted.
,D/SPPClientService( 7008): PushLog.txt file is not deleted.
D/SPPClientService( 7008): ============PushLog. stop!
,E/SQLiteLog( 7008): (14) cannot open file at line 32470 of [9491ba7d73]
,E/SQLiteLog( 7008): (14) os_unix.c:32470: (5) open(/data/data/com.sec.spp.push/databases/push_noti_db) - 
,E/SQLiteDatabase( 7008): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 7008): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 7008): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7008): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7008): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteDatabase( 7008): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteDatabase( 7008): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7008): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteDatabase( 7008): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7008): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7008): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7008): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7008): 	at com.sec.spp.push.notisvc.a.b.<init>(Unknown Source)
E/SQLiteDatabase( 7008): 	at com.sec.spp.push.notisvc.a.b.a(Unknown Source)
E/SQLiteDatabase( 7008): 	at com.sec.spp.push.notisvc.registration.l.b(Unknown Source)
E/SQLiteDatabase( 7008): 	at com.sec.spp.push.notisvc.registration.l.a(Unknown Source)
E/SQLiteDatabase( 7008): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
E/SQLiteDatabase( 7008): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.onReceive(Unknown Source)
E/SQLiteDatabase( 7008): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2945)
E/SQLiteDatabase( 7008): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7008): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1499)
E/SQLiteDatabase( 7008): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7008): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7008): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/SQLiteDatabase( 7008): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7008): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7008): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 7008): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/LNoti   ( 7008): [b] open fail. SQLException occured
F/libc    ( 7008): Fatal signal 7 (SIGBUS), code 2, fault addr 0x773de979 in tid 7008 (moteNotiProcess)
E/audit_log( 2160): File locking failed. error= Bad file number
F/libc    ( 7008): Failed while talking to debuggerd: Broken pipe
E/audit_log( 2160): File locking failed. error= Bad file number
I/ActivityManager(  834): Process com.sec.spp.push:RemoteNotiProcess (pid 7008)(adj 0) has died(146,609)
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7024): MountEmulatedStorage()
E/Zygote  ( 7024): v2
I/libpersona( 7024): KNOX_SDCARD checking this for 10041
I/libpersona( 7024): KNOX_SDCARD not a persona
,I/ActivityManager(  834): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=7024 uid=10041 gids={50041, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/EventHub(  834): Removing device '/dev/input/event6' due to inotify event
,I/SELinux ( 7024): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0014
I/Zygote  (  322): Process 7008 exited due to signal (7)
,E/SELinux ( 7024): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7024): TimaSignature is unavailable
,D/ActivityThread( 7024): Added TimaKeyStore provider
,I/EventHub(  834): Removing device '/dev/input/event7' due to inotify event
,D/ResourcesManager( 7024): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,W/ResourcesManager( 7024): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7024): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ContextImpl( 7024): Unable to create files subdir /data/data/com.samsung.android.sdk.samsunglink/cache
E/ActivityThread( 7024): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 7024): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb3922000 in tid 7024 (sdk.samsunglink)
,F/libc    ( 7024): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2160): File locking failed. error= Bad file number
,I/ActivityManager(  834): Process com.samsung.android.sdk.samsunglink (pid 7024)(adj 0) has died(145,610)
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7039): MountEmulatedStorage()
E/Zygote  ( 7039): v2
I/libpersona( 7039): KNOX_SDCARD checking this for 10044
I/libpersona( 7039): KNOX_SDCARD not a persona
,I/ActivityManager(  834): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver: pid=7039 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/EventHub(  834): Removing device '/dev/input/event8' due to inotify event
,I/Zygote  (  322): Process 7024 exited due to signal (7)
,I/SELinux ( 7039): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0014
E/SELinux ( 7039): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/EventHub(  834): Removing device '/dev/input/event9' due to inotify event
,D/TimaKeyStoreProvider( 7039): TimaSignature is unavailable
,D/ActivityThread( 7039): Added TimaKeyStore provider
,D/ResourcesManager( 7039): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,W/ContextImpl( 7039): Unable to create files subdir /data/data/com.osp.app.signin/cache
E/ActivityThread( 7039): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 7039): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb45ad000 in tid 7039 (.osp.app.signin)
,F/libc    ( 7039): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2160): File locking failed. error= Bad file number
,I/ActivityManager(  834): Process com.osp.app.signin (pid 7039)(adj 0) has died(144,610)
,F/libc    ( 1784): Fatal signal 7 (SIGBUS), code 2, fault addr 0x776f8e10 in tid 1867 (ContactsProvide)
,F/libc    ( 1784): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2160): File locking failed. error= Bad file number
,I/EventHub(  834): Removing device '/dev/input/event10' due to inotify event
,I/ActivityManager(  834): Process android.process.acore (pid 1784)(adj 0) has died(153,610)
,F/libc    (  834): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa0a0a60f in tid 865 (Binder_1)
,F/libc    (  834): Unable to open connection to debuggerd: Connection refused
,I/Zygote  (  322): Process 7039 exited due to signal (7)
E/audit_log( 2160): File locking failed. error= Bad file number
,I/Zygote  (  322): Process 1784 exited due to signal (7)
,I/ServiceManager(  257): service 'application_policy' died
W/AudioFlinger(  300): power manager service died !!!
W/AudioFlinger(  300): power manager service died !!!
W/Sensors ( 5343): sensorservice died [0xaefcf500]
W/AudioFlinger(  300): power manager service died !!!
,I/ServiceManager(  257): service 'wifi_policy' died
I/ServiceManager(  257): service 'phone_restriction_policy' died
I/ServiceManager(  257): service 'remoteinjection' died
I/ServiceManager(  257): service 'mum_container_policy' died
I/ServiceManager(  257): service 'enterprise_billing_policy' died
I/ServiceManager(  257): service 'knox_timakeystore_policy' died
W/Sensors ( 1483): sensorservice died [0xaefd4380]
I/ServiceManager(  257): service 'enterprise_policy' died
I/ServiceManager(  257): service 'statusbar' died
I/ServiceManager(  257): service 'clipboard' died
I/ServiceManager(  257): service 'clipboardEx' died
I/ServiceManager(  257): service 'network_management' died
I/ServiceManager(  257): service 'ABTPersistenceService' died
I/ServiceManager(  257): service 'textservices' died
I/ServiceManager(  257): service 'network_score' died
I/ServiceManager(  257): service 'netstats' died
I/SurfaceFlinger(  259): restart the boot-animation @ binderDied
I/ServiceManager(  257): service 'netpolicy' died
I/ServiceManager(  257): service 'wifip2p' died
I/ServiceManager(  257): service 'wifi' died
I/ServiceManager(  257): service 'msapwifi' died
I/ServiceManager(  257): service 'wifiscanner' died
I/ServiceManager(  257): service 'rttmanager' died
I/ServiceManager(  257): service 'connectivity' died
I/ServiceManager(  257): service 'sb_service' died
I/ServiceManager(  257): service 'clinfo' died
I/ServiceManager(  257): service 'servicediscovery' died
I/ServiceManager(  257): service 'updatelock' died
I/ServiceManager(  257): service 'notification' died
I/ServiceManager(  257): service 'devicestoragemonitor' died
I/ServiceManager(  257): service 'location' died
I/ServiceManager(  257): service 'country_detector' died
I/ServiceManager(  257): service 'sec_location' died
I/ServiceManager(  257): service 'search' died
I/ServiceManager(  257): service 'dropbox' died
I/ServiceManager(  257): service 'wallpaper' died
I/ServiceManager(  257): service 'audio' died
W/Sensors ( 1182): sensorservice died [0xaef7f0c0]
I/ServiceManager(  257): service 'DockObserver' died
I/ServiceManager(  257): service 'usb' died
I/ServiceManager(  257): service 'serial' died
I/ServiceManager(  257): service 'uimode' died
I/ServiceManager(  257): service 'jobscheduler' died
I/ServiceManager(  257): service 'backup' died
I/ServiceManager(  257): service 'appwidget' died
I/ServiceManager(  257): service 'voiceinteraction' died
I/ServiceManager(  257): service 'SecExternalDisplayService' died
I/ServiceManager(  257): service 'diskstats' died
I/ServiceManager(  257): service 'spengestureservice' died
I/ServiceManager(  257): service 'quickconnect' died
I/ServiceManager(  257): service 'samplingprofiler' died
I/ServiceManager(  257): service 'commontime_management' died
I/ServiceManager(  257): service 'dreams' died
I/ServiceManager(  257): service 'print' died
I/ServiceManager(  257): service 'restrictions' died
I/ServiceManager(  257): service 'media_session' died
I/ServiceManager(  257): service 'media_router' died
I/ServiceManager(  257): service 'trust' died
I/ServiceManager(  257): service 'fingerprint' died
I/ServiceManager(  257): service 'launcherapps' died
I/ServiceManager(  257): service 'voip' died
I/ServiceManager(  257): service 'media_projection' died
I/ServiceManager(  257): service 'imms' died
I/ServiceManager(  257): service 'sec_analytics' died
I/ServiceManager(  257): service 'context_aware' died
I/ServiceManager(  257): service 'scontext' died
,I/ServiceManager(  257): service 'barbeam' died
I/ServiceManager(  257): service 'multiwindow_facade' died
I/ServiceManager(  257): service 'window' died
I/ServiceManager(  257): service 'input' died
I/ServiceManager(  257): service 'tactileassist' died
I/ServiceManager(  257): service 'bluetooth_manager' died
I/ServiceManager(  257): service 'bluetooth_secure_mode_manager' died
I/ServiceManager(  257): service 'rcp' died
I/ServiceManager(  257): service 'input_method' died
I/ServiceManager(  257): service 'accessibility' died
I/ServiceManager(  257): service 'motion_recognition' died
I/ServiceManager(  257): service 'cover' died
I/ServiceManager(  257): service 'mount' died
I/ServiceManager(  257): service 'lock_settings' died
I/ServiceManager(  257): service 'device_policy' died
I/ServiceManager(  257): service 'harmony_eas_service' died
I/ServiceManager(  257): service 'sdp' died
I/ServiceManager(  257): service 'log_manager_service' died
I/ServiceManager(  257): service 'enterprise_license_policy' died
I/ServiceManager(  257): service 'meminfo' died
I/ServiceManager(  257): service 'user' died
I/ServiceManager(  257): service 'batterystats' died
I/ServiceManager(  257): service 'appops' died
I/ServiceManager(  257): service 'power' died
I/ServiceManager(  257): service 'display' died
I/ServiceManager(  257): service 'sedenial' died
I/ServiceManager(  257): service 'vibrator' died
I/ServiceManager(  257): service 'tw_toolbox' died
I/ServiceManager(  257): service 'tima' died
I/ServiceManager(  257): service 'cepproxyks' died
I/ServiceManager(  257): service 'SEAMService' died
I/ServiceManager(  257): service 'persona' died
I/ServiceManager(  257): service 'account' died
I/ServiceManager(  257): service 'content' died
I/ServiceManager(  257): service 'DirEncryptService' died
I/ServiceManager(  257): service 'ReactiveService' died
I/ServiceManager(  257): service 'persona_policy' died
I/ServiceManager(  257): service 'CustomFrequencyManagerService' died
I/ServiceManager(  257): service 'samsung.smartfaceservice' died
I/ServiceManager(  257): service 'consumer_ir' died
I/ServiceManager(  257): service 'alarm' died
I/ServiceManager(  257): service 'activity' died
I/ServiceManager(  257): service 'procstats' died
I/ServiceManager(  257): service 'permission' died
I/ServiceManager(  257): service 'webviewupdate' died
I/ServiceManager(  257): service 'usagestats' died
I/ServiceManager(  257): service 'hardware' died
I/ServiceManager(  257): service 'entropy' died
I/ServiceManager(  257): service 'cpuinfo' died
I/ServiceManager(  257): service 'edmnativehelper' died
I/ServiceManager(  257): service 'scheduling_policy' died
I/ServiceManager(  257): service 'telephony.registry' died
I/ServiceManager(  257): service 'package' died
I/ServiceManager(  257): service 'dbinfo' died
I/ServiceManager(  257): service 'gfxinfo' died
I/ServiceManager(  257): service 'sensorservice' died
I/ServiceManager(  257): service 'mdm.remotedesktop' died
I/ServiceManager(  257): service 'battery' died
W/Sensors ( 1312): sensorservice died [0x9d521300]
W/Sensors ( 1558): sensorservice died [0xaef60480]
W/Sensors ( 2242): sensorservice died [0xb4eefc00]
W/Sensors ( 1497): sensorservice died [0xaef533c0]
W/Sensors ( 1467): sensorservice died [0xb4eefbc0]
E/WifiManager( 1558): Channel connection lost
E/WifiManager( 1483): Channel connection lost
D/SurfaceFlinger(  259): Set power mode=2, type=0 flinger=0xb6a62000
D/SurfaceFlinger(  259): Screen type=0 is already mode=2
E/WifiManager( 1570): Channel connection lost
I/SurfaceFlinger(  259): id=2 Removed FocusedStackFrame (4/7)
I/SurfaceFlinger(  259): id=5 Removed com.android.systemui.ImageWallpaper (3/6)
I/SurfaceFlinger(  259): id=5 Removed com.android.systemui.ImageWallpaper (-2/6)
I/SurfaceFlinger(  259): id=7 Removed StatusBar (5/5)
I/SurfaceFlinger(  259): id=15 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (3/4)
I/SurfaceFlinger(  259): id=7 Removed StatusBar (-2/4)
I/SurfaceFlinger(  259): id=15 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/4)
I/SurfaceFlinger(  259): id=8 Removed DimLayer (2/3)
I/SurfaceFlinger(  259): id=9 Removed DimLayer (2/2)
I/SurfaceFlinger(  259): id=3 Removed DimLayer (0/1)
I/SurfaceFlinger(  259): id=4 Removed DimLayer (0/0)
I/SurfaceFlinger(  259): id=8 Removed DimLayer (-2/0)
I/SurfaceFlinger(  259): id=9 Removed DimLayer (-2/0)
I/SurfaceFlinger(  259): id=2 Removed FocusedStackFrame (-2/0)
I/SurfaceFlinger(  259): id=3 Removed DimLayer (-2/0)
I/SurfaceFlinger(  259): id=4 Removed DimLayer (-2/0)
E/WifiManager( 1312): Channel connection lost
E/WifiManager( 1654): Channel connection lost
E/WifiManager( 1182): Channel connection lost
,E/SMD     (  294): DCD ON
,E/installd(  303): eof
E/installd(  303): failed to read size
I/installd(  303): closing connection
,I/SurfaceFlinger(  259): Disp[0] Orientation 0=>0
,F/libc    (  259): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb61231ed in tid 259 (surfaceflinger)
,F/libc    (  259): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2160): File locking failed. error= Bad file number
,I/ServiceManager(  257): service 'SurfaceFlinger' died
I/ServiceManager(  257): service 'display.qservice' died
,W/SurfaceComposerClient( 2100): ComposerService remote (surfaceflinger) died [0xaef57ac0]
W/SurfaceComposerClient( 1182): ComposerService remote (surfaceflinger) died [0xaef7f380]
W/SurfaceComposerClient( 1497): ComposerService remote (surfaceflinger) died [0xaef53200]
,E/DisplayEventReceiver( 1182): Display event receiver pipe was closed or an error occurred.  events=0x9
E/DisplayEventReceiver( 1497): Display event receiver pipe was closed or an error occurred.  events=0x9
E/OpenGLRenderer( 1497): Display event receiver pipe was closed or an error occurred.  events=0x9
E/OpenGLRenderer( 1182): Display event receiver pipe was closed or an error occurred.  events=0x9
E/DisplayEventReceiver( 2100): Display event receiver pipe was closed or an error occurred.  events=0x9

```
