#### Test 561510933390750_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
D/InputManager-JNI(  879): setDeviceInteractive: 0
D/InputManager-JNI(  879): sysfs_write +: /sys/class/input/event1/device/enabled: 0
I/SurfaceFlinger(  250): id=14 createSurf (1080x1920),2 flag=404, ColorFade
D/InputManager-JNI(  879): sysfs_write +: /sys/class/input/event2/device/enabled: 0
D/InputManager-JNI(  879): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/InputManager-JNI(  879): sysfs_write -: /sys/class/input/event2/device/enabled: 0
D/SContextService(  879): 	.unregisterCallback : 1, client=
D/SContextService(  879): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@1087a157, Service = Auto Rotation, used = 1
--------- beginning of system
D/PowerManagerService(  879): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  879): Nap time (uid 1000)...
I/PowerManagerService(  879): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  879): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService(  879): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  879): SecHardwareInterface.setBatteryADC : false
D/PowerManagerService(  879): handleSandman : startDream()
E/PowerManagerService(  879): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  879): Sleeping (uid 1000)...
D/PowerManagerService(  879): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  879): [input device light] setInputDeviceLightOn is called : 0
D/PowerManagerService(  879): [input device light] handleInputDeviceLightOff
W/CAE     (  879): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
V/CAE     (  879): stop(ContextProvider.java:149)
V/CAE     (  879): clear(AutoRotationRunner.java:182)
V/CAE     (  879): disable(AutoRotationRunner.java:171)
I/CAE     (  879): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  879): SendSensorHubData: send data = -78, 7, 0, 0
D/Sensorhubs(  297): sendContextData: -78, 7, 0, 0
D/CAE     (  879): getFaultDetectionResult(AutoRotationRunner.java:195) - true
I/CAE     (  879): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  879): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
I/CAE     (  879): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     (  879): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
W/CAE     (  879): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  879): removeSContextService() : service = Auto Rotation
D/SContextService(  879): ===== SContext Service List =====
D/SContextManager(  879):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@f3e36de, service=Auto Rotation
D/KeyguardViewMediator( 1178): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1178): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1178): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1178): notifyScreenOffLocked
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/Launcher.HomeView( 1492): onPause
D/LockPatternUtilsCache( 1178): value : false
D/KeyguardViewMediator( 1178): timeout : 5000
D/Launcher( 1492): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/DisplayPowerController(  879): ColorFade: onAnimationStart
D/DisplayPowerController(  879): getFinalBrightness : 75 -> 0
D/lights  (  879): lcd : 8 +
D/lights  (  879): lcd : 8 -
D/lights  (  879): lcd : 0 +
D/DisplayPowerController(  879): getFinalBrightness : 75 -> 0
D/lights  (  879): lcd : 0 -
D/KeyguardViewMediator( 1178): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 1178): handleNotifyScreenOff
V/TaskCloserActivity( 7103): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/StatusBarManagerService(  879): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LightsService(  879): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 879) 
D/LightsService(  879): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/LightsService(  879): [SvcLED]  onSensorChanged::light value = 83
D/Launcher.HomeView( 1492): onStop
I/MicrophoneInputStream( 1575): mic_close gfk@57520fb
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2084): [237392/6] Surface widget pause on instance = 1
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/accuweather( 2084): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2084): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2084): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/SensorManager(  879): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/SensorManager(  879): unregisterListener ::   
D/lights  (  879): led_pattern : 5 +
V/AudioPolicyManager(  291): stopInput() input 29
D/accuweather( 2084): [KK AccuPhone]>>> WR:132 [0:0] onPause
V/audio_hw_primary(  291): in_standby: enter
D/accuweather( 2084): [KK AccuPhone]>>> SM:538 [0:0] onPause
I/HotwordRecognitionRnr( 1575): Stopping hotword detection.
I/HotwordRecognitionRnr( 1575): Hotword detection finished
D/BatteryService(  879): turn on LED for fully charged
D/lights  (  879): led_pattern : 5 -
D/LightsService(  879): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
I/CAE     (  879): handleMessage(CaPowerManager.java:182) - AP_SLEEP
I/CAE     (  879): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  879): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  879): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  297): sendContextData: -76, 13, -46, 0
I/CAE     (  879): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 12, 12, 58,
D/SensorHubManager(  879): SendSensorHubData: send data = -63, 14, 12, 12, 58
D/Sensorhubs(  297): sendContextData: -63, 14, 12, 12, 58
V/audio_hw_primary(  291): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  291): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  291): disable_audio_route: reset mixer path: audio-record
D/audio_route(  291): ++++ audio_route_update_mixer ==============
D/audio_route(  291): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  291): Setting mixer control: value: 0
D/audio_route(  291): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  291): disable_audio_route: exit
V/audio_hw_primary(  291): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  291): ++++ audio_route_update_mixer ==============
D/audio_route(  291): Setting mixer control: DEC2 Volume
D/audio_route(  291): Setting mixer control: value: 0
D/audio_route(  291): Setting mixer control: SLIM TX7 MUX, value: 0
D/audio_route(  291): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  291): Setting mixer control: value: 0
D/audio_route(  291): Setting mixer control: DEC2 MUX, value: 0
D/audio_route(  291): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  291): stop_input_stream: exit: status(0)
V/audio_hw_primary(  291): in_standby: exit:  status(0)
V/AudioPolicyManager(  291): releaseInput() 29
V/AudioPolicyManager(  291): closeInput(29)
V/audio_hw_primary(  291): adev_close_input_stream
V/audio_hw_primary(  291): in_standby: enter
V/audio_hw_primary(  291): in_standby: exit:  status(0)
E/audio_hw_primary(  291): adev_close_input_stream, set jack_in to null
D/MotionRecognitionService(  879):   mReceiver.onReceive : ACTION_SCREEN_OFF
V/AudioPolicyManager(  291): releaseInput() exit
E/MotionRecognitionService(  879):  handler : SCREEN_OFF end 
D/NotificationService(  879): ACTION_SCREEN_OFF
D/LightsService(  879): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 879) 
D/LightsService(  879): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
D/LightsService(  879): [SvcLED]  onSensorChanged::light value = 83
D/WifiStateMachine(  879): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  879): handleScreenStateChanged Exit: false
E/WifiStateMachine(  879): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/WifiStateMachine(  879): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  879): do suspend true
D/DisplayPowerState(  879): !@ ColorFade entry
D/DisplayPowerController(  879): ColorFade: onAnimationEnd
D/SensorManager(  879): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/SensorManager(  879): unregisterListener ::   
D/LightsService(  879): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
V/AlarmManager(  879): waitForAlarm result :4
D/AutomaticBrightnessController(  879): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  879): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
I/AutomaticBrightnessController(  879): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/AutomaticBrightnessController(  879): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  879): Light old sensor_state 8705, new sensor_state : 8193 en : 0
D/audio_hw_primary(  291): adev_set_parameters: enter: screen_state=off
V/voice   (  291): voice_set_parameters: enter: screen_state=off
V/voice   (  291): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  291): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  291): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  291): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  291): adev_set_parameters: exit
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
D/SensorManager(  879): unregisterListener ::   
E/Sensors (  879): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
D/SensorManager(  879): unregisterListener ::   
D/DisplayPowerController(  879): getFinalBrightness : 0 -> 0
I/DisplayManagerService(  879): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  250): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  250): hwc_blank: Blanking display: 0
E/Zygote  ( 7620): MountEmulatedStorage()
E/Zygote  ( 7620): v2
I/libpersona( 7620): KNOX_SDCARD checking this for 10179
I/libpersona( 7620): KNOX_SDCARD not a persona
D/DisplayPowerController(  879): getFinalBrightness : 0 -> 0
I/ActivityManager(  879): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler: pid=7620 uid=10179 gids={50179, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
V/ActivityManager(  879): Display changed displayId=0
I/SecExternalDisplayIntents_Java(  879): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
I/SELinux ( 7620): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7620): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7620): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/IpRemoteDisplayController(  879): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  879): Bridge Server is not available
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/VolumePanel( 1178): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1178): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/VolumePanel( 1178): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1178): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
D/StatusBar.NetworkController( 1178): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/TimaKeyStoreProvider( 7620): TimaSignature is unavailable
D/ActivityThread( 7620): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PersonaManagerService(  879): ACTION_SCREEN_OFF onReceive
D/ResourcesManager( 7620): creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
D/PersonaManagerServiceHandler(  879): MSG_ACTION_SCREEN_OFF called
D/NfcService( 1477): call the applyRotuiing
D/AndroidRuntime( 7611): 
D/AndroidRuntime( 7611): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/STATUSBAR-PhoneStatusBar( 1178):      ACTION_SCREEN_OFF is finished!!!! 
D/AndroidRuntime( 7611): CheckJNI is OFF
D/AndroidRuntime( 7611): setted country_code = Germany
W/ResourcesManager( 7620): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/AndroidRuntime( 7611): setted countryiso_code = DE
D/AndroidRuntime( 7611): setted sales_code = DBT
D/AndroidRuntime( 7611): readGMSProperty: start
D/AndroidRuntime( 7611): readGMSProperty: already setted!!
D/AndroidRuntime( 7611): readGMSProperty: end
D/AndroidRuntime( 7611): addProductProperty: start
E/StatusBar( 1178): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1178): dismissHelpPopup 
D/accuweather( 2084): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 2084): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2084): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PowerManagerService(  879): [PWL] sb release: PowerManagerService.Broadcasts
I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6c01090
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1228406016)
D/UMC:Core( 7620): onCreate(): 
D/SSRM:m  (  879): SIOP:: AP = 360, PST = 448, CUR = 300
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1228406016) wakelock released: 1, error no: 22
I/rmt_storage(  272): 
I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6c01090
D/qdhwcomposer(  250): hwc_blank: Done blanking display: 0
I/qdhwcomposer(  250): handle_blank_event: dpy:0 panel power state: 0
D/SurfaceControl(  879): Excessive delay in setPowerMode(): 265ms
D/PowerManagerService(  879): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  879): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  879): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL(  879): Got set_interactive hint
I/PowerManagerService(  879): [PWL] Off : 0s ago
I/PowerManagerService(  879): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  879): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  879): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=2495, ws=null) (elapsedTime=59836)
I/PowerManagerService(  879): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=879, ws=WorkSource{10179}) (elapsedTime=290)
I/PowerManagerService(  879): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  879): [PWL]     mDisplayReady : false
D/DisplayPowerController(  879): getFinalBrightness : 0 -> 0
D/PowerManagerService(  879): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  879): [PWL] sb release: PowerManagerService.Display
D/USER_AGENT( 7620): UMC/1.1.39 (SM-G900F) SAFE-5.3 KNOX-2.3
E/AffinityControl( 7611): AffinityControl: registerfunction enter
D/AndroidRuntime( 7611): Calling main entry com.android.commands.am.Am
D/[SAMSUNG SMARCART NATIVE]( 7620): initialize...
D/[SAMSUNG SMARCART NATIVE]( 7620): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
I/CSTORAGE( 7620): ================================================
I/CSTORAGE( 7620):  CSTORAGE_SKM_LIB v1.0.8
I/CSTORAGE( 7620): ================================================
I/TZ_CCM_C_GetFunctionList: ( 7620): TZ_CCM_C_GetFunctionList was called
D/[SAMSUNG SMARCART NATIVE]( 7620): FINISHED: initialize rv:0
E/PersonaManagerService(  879): inState():  stateMachine is null !!
V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  879): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  879): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  879): mDVFSHelper.acquire()
D/FocusedStackFrame(  879): Set to : 0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7648): MountEmulatedStorage()
I/libpersona( 7648): KNOX_SDCARD checking this for 10200
E/Zygote  ( 7648): v2
I/libpersona( 7648): KNOX_SDCARD not a persona
I/ActivityManager(  879): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7648 uid=10200 gids={50200, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7648): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
I/SELinux ( 7648): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7648): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 7611): Shutting down VM
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/TimaKeyStoreProvider( 7648): TimaSignature is unavailable
D/ActivityThread( 7648): Added TimaKeyStore provider
V/WindowOrientationListener(  879): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  879): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  879): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  879): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  879): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/SurfaceWidgetView( 1492): destroyHardwareResources():538053983
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
I/SurfaceFlinger(  250): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (6/8)
I/SurfaceFlinger(  250): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/8)
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/Launcher( 1492): onTrimMemory. Level: 20
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2084): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/UMC:SecurityUtils( 7620): Loaded server certificates: 0
D/UMC:SecurityUtils( 7620): Loaded server certificates: 0
D/UMC:SecurityUtils( 7620): timaVersion on the device: 3.0
D/UMC:CloudMDMSecurity( 7620): New Flow
D/ResourcesManager( 7648): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/TimaService(  879): TIMA3: in ccmRegisterForDefaultCertificate
D/TimaService(  879): TIMA: in getTimaVersion
I/        (  879): CCM JNI: In ccm_register_for_default_cert
I/        (  879): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: (  879): DEBUG_CONTAINER_PROBLEM Enter TZ_CCM_C_Initialize_TLC!
I/TZ_CCM_C_Initialize: (  879): pInitArgs 0x6e8ec814 has not called C_Init before.
I/TZ_CCM_C_Initialize: (  879): &ctx = 0x9fb6ec1c
I/TLC_TZ_CCM: (  879): creating new ccm context...
I/TLC_TZ_CCM: (  879): initializing ccm context...
I/TLC_TZ_CCM: (  879): root = /firmware/image, root_strlen = 15
I/TLC_TZ_CCM: (  879): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  879): input max_sendmsg_size = 19420
I/TZ: client_server_communication(  879): input max_recvmsg_size = 19420
I/TZ: client_server_communication(  879): root = /firmware/image, root_len = 15
I/TZ: client_server_communication(  879): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  879): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication(  879): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication(  879): Client_Server_Open was called
I/TZ: client_server_communication(  879): IClientServer::IClientServer()
I/TZ: client_server_communication(  879): BpClientServer::BpClientServer()
I/TZ: client_server_communication(  879): IClientServer::~IClientServer()
I/TZ_CCM_SERVER( 1079): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 1079): OPENSWCONN
I/TZ_CCM_SERVER( 1079): creating new ccm context...
I/TZ_CCM_SERVER( 1079): initializing ccm context...
I/TZ_CCM_SERVER( 1079): root = /firmware/image, root_strlen = 15
I/TZ_CCM_SERVER( 1079): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1079): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1079): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1079): aligned max_sendmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1079): aligned max_recvmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1079): max_message_size = 38912 = 0x9800
D/QSEECOMAPI: ( 1079): QSEECom_get_handle sb_length = 0x9800
D/QSEECOMAPI: ( 1079): App is not loaded in QSEE
I/SQLiteSecureOpenHelper( 3552): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3552): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/QSEECOMAPI: ( 1079): Loaded image: APP id = 3
I/TZ: qc_tlc_communication( 1079): TIMA: path = /firmware/image, fname = tz_ccm, tzapp is loaded
I/TZ: client_server_communication(  879): OpenSWConn(CCM) is successful
I/TZ: client_server_communication(  879): Client_Server_Open succeeded, serverName = CCM
I/TZ_CCM_C_Initialize: (  879): ctx = 0x8c12a5b0, comm = 0x9c6f7610, sendmsg = 0x8c154000, recvmsg = 0x8c158c00
I/TZ_init: (  879): TZ_init: sending initialization request...
I/TZ: client_server_communication(  879): Cmd id = 2, len = 19456
I/TZ: client_server_communication(  879): Calling Communicate()
I/TZ_CCM_SERVER( 1079): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1079): COMM
I/TZ_init: (  879): TZ_init: successful initialization
I/TLC_TZ_COMMON: key_db_init: (  879): Exercising TZ_DB_INIT in TLC
I/TZ: client_server_communication(  879): Cmd id = 17, len = 19456
I/TZ: client_server_communication(  879): Calling Communicate()
I/TZ_CCM_SERVER( 1079): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1079): COMM
I/TZ_COMMON: tlc_key_db_util: (  879): DB Operation suceeded
I/TLC_TZ_CCM: register for default cert: (  879): Exercising TZ_CCM_register_default_TLC
I/TZ: client_server_communication(  879): Cmd id = 25, len = 19456
I/TZ: client_server_communication(  879): Calling Communicate()
I/TZ_CCM_SERVER( 1079): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1079): COMM
I/TLC_TZ_CCM: register for default cert: (  879): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: (  879): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
I/TZ_CCM_C_Finalize: (  879): DEBUG_CONTAINER_PROBLEM Exercising TZ_CCM_C_Finalize_TLC
I/TZ: client_server_communication(  879): Cmd id = 41, len = 19456
I/TZ: client_server_communication(  879): Calling Communicate()
I/TZ_CCM_SERVER( 1079): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1079): COMM
I/TZ: client_server_communication(  879): Client_Server_Close was called
I/TZ_CCM_SERVER( 1079): BnCCM::onTransact(1) 16
I/TZ_CCM_SERVER( 1079): CLOSESWCONN
D/QSEECOMAPI: ( 1079): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1079): QSEECom_shutdown_app, app_id = 3
I/TZ: client_server_communication(  879): Client_Server_Close succeeded
D/UMC:CloudMDMSecurity( 7620): ccmRegisterForDefaultCertificate: 0
D/UMC:CloudMDMSecurity( 7620): TIMA service call for password change success!!
D/UMC:AdminManager( 7620): init - start
D/UMC:AdminManager( 7620): loadAdmins
D/UMC:AdminManager( 7620): startPolicyHandlers
I/UMC:TestPolicyHandler( 7620): Setup is called in testpolicyhandler
D/UMC:AdminManager( 7620): init - end
V/UMC:AlarmHandler( 7620): Enter loadList
D/GSLBManager( 7620): migrateStoredUrlFromOldPref
D/GSLBManager( 7620): migrateStoredUrlFromOldPref : Migration Not Needed
D/UMC:UMCAdmin( 7620): deactivateUMCAdminIfNotRequired : -1
E/UMC:Utils( 7620): Admin not found in package com.samsung.knoxpb.mdm
D/UMC:UMCAdmin( 7620): deactivateUMCAdmin : -1
D/UMC:UMCAdmin( 7620): isContainer : 0
W/LicenseLogService(  879): log() failed
D/EnterpriseDeviceManagerService(  879): isManagedProfileUser(): userId = 0
E/UMC:UMCAdmin( 7620): No active admin owned by uid 10179
D/UMC:UMCAdmin( 7620): isContainer : 0
D/UMC:UMCAdmin( 7620): deactivateUMCAdmin - UMC App Admin deactivated
V/UMC:AlarmHandler( 7620): onReceive :Intent { flg=0x14 cmp=com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler (has extras) }
I/ActivityManager(  879): Killing 6827:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
D/QuickStartReceiver( 7620): Msg Id : 2
D/QuickStartReceiver( 7620): model : SM-G900F
D/QuickStartReceiver( 7620): id : 100
,I/WebViewFactory( 7648): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7648): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
W/libprocessgroup(  879): failed to open /acct/uid_10098/pid_6827/cgroup.procs: No such file or directory
I/LibraryLoader( 7648): Loading: webviewchromium
I/LibraryLoader( 7648): Time to load native libraries: 3 ms (timestamps 7301-7304)
I/LibraryLoader( 7648): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7648): Binding Chromium to main looper Looper (main, tid 1) {3b587b87}
I/LibraryLoader( 7648): Expected native library version number "",actual native library version number ""
I/chromium( 7648): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7648): Initializing chromium process, renderers=0
W/art     ( 7648): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7648): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7648): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7648): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
I/Adreno-EGL( 7648): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7648): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7648): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7648): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7648): Remote Branch: 
I/Adreno-EGL( 7648): Local Patches: 
I/Adreno-EGL( 7648): Reconstruct Branch: 
W/chromium( 7648): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7648): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7648): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7648): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7648): CordovaWebView is running on device made by: samsung
W/art     ( 7648): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7648): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity( 7648): performCreate Call secproduct feature valuefalse
D/Activity( 7648): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 7648): Render dirty regions requested: true
D/ActivityManager(  879): post active user change for 0
D/KnoxTimeoutHandler(  879): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  879): handleActiveUserChange for user 0
I/SurfaceFlinger(  250): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/StatusBarManagerService(  879): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/StatusBarManagerService(  879): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
I/OpenGLRenderer( 7648): Initialized EGL, version 1.4
I/OpenGLRenderer( 7648): HWUI protection enabled for context ,  &this =0xa1753060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7648): Enabling debug mode 0
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/InputMethodManagerService(  879): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
W/ActivityManager(  879): mDVFSHelper.release()
I/Timeline(  879): Timeline: Activity_windows_visible id: ActivityRecord{19dc895c u0 com.test.thalitest/.MainActivity t17} time:97659
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
W/IInputConnectionWrapper( 7648): showStatusIcon on inactive InputConnection
I/Timeline( 7648): Timeline: Activity_idle id: android.os.BinderProxy@10b63676 time:97664
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
E/SMD     (  284): DCD ON
D/JsMessageQueue( 7648): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 7648): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7648): 
D/jxcore_app_log( 7648): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1358541824
D/JX-Cordova( 7648): jxcore cordova android initializing
V/AlarmManager(  879): waitForAlarm result :4
D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  879): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  879): stay LED for fully charged
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
D/MotionRecognitionService(  879):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,V/HeadsetService( 3228): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3228): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager(  879): waitForAlarm result :8
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6412): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6412): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6412): [1] 5.onFinished: Scheduling replication attempt 2.
,W/jxcore-log( 7648): Initializing JXcore engine
,W/jxcore-log( 7648): JXcore engine is ready
,W/jxcore-log( 7648): Starting JXcore engine
,E/auditd  ( 2055): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  879): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  879): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,D/SecurityLogAgent( 7450):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7450):  SeDenialReceiver : File path = null
,W/jxcore-log( 7648): Platform android
W/jxcore-log( 7648): 
W/jxcore-log( 7648): Process ARCH arm
W/jxcore-log( 7648): 
,I/jxcore-log( 7648): JXcore Cordova bridge is ready!
I/jxcore-log( 7648): 
,W/jxcore-log( 7648): JXcore engine is started
,I/jxcore-log( 7648): Toggling radios to true
I/jxcore-log( 7648): 
D/WifiService(  879): New client listening to asynchronous messages
D/BluetoothAdapter( 7648): enable()
D/BluetoothAdapter( 7648): enable(): BT is already enabled..!
,I/WifiManager( 7648): packageName : com.test.thalitest
,D/SecContentProvider(  879): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  879): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  879): mCursor = null
,D/WifiService(  879): setWifiEnabled: true pid=7648, uid=10200
,E/WifiService(  879): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  879): Permission Denial: getCurrentUser() from pid=7648, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  879): Failed getting userId using ActivityManagerNative
W/WifiService(  879): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7648, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  879): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  879): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  879): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  879): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  879): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  879): name = wifi_on
,I/WifiService(  879): disconnect: pid=7648, uid=10200
,I/wpa_supplicant( 1292): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7648): Radios toggled
I/jxcore-log( 7648): 
,I/jxcore-log( 7648): My device name is: samsung-SM-G900F
I/jxcore-log( 7648): 
,I/wpa_supplicant( 1292): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1292): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1292): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1292): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  879): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1292): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1292): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1292): Disconnected - do not scan
I/wpa_supplicant( 1292): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  879): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  879): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  879): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  879): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  879): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  879): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  879): do suspend true
,D/WifiP2pService(  879): InactiveState{ what=143375 }
,D/WifiP2pService(  879): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1708): Read error: ssl=0x9bc4de00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1708): SSL shutdown failed: ssl=0x9bc4de00: I/O error during system call, Broken pipe
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): DefaultState{ when=-2ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Forcing reevaluation
,E/WifiStateMachine(  879): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  879): updateNetworkInfo()
,D/ConnectivityService(  879): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  879): updateNetworkInfo()
,D/ConnectivityService(  879): ignoring duplicate network state non-change
D/ConnectivityService(  879): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Validated
,I/WifiTrafficPoller(  879): evaluateTrafficStatsPolling
,I/CLocInfoService(  879): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiConfigStore(  879): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
E/WifiStateMachine(  879): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1292): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1292): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1292): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1292): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1292): First Scan Start
,I/wpa_supplicant( 1292): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  879): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  879): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  879): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  879): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/native  (  879): do suspend true
,D/WifiP2pService(  879): InactiveState{ what=143375 }
,D/WifiP2pService(  879): P2pEnabledState{ what=143375 }
,I/Hs20UtilService( 1300): Starting #6
,I/Hs20UtilService( 1300): Message received 5007
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1300): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1300): MountReceiver.mPrefHandler - 7002
,D/CommandListener(  277): Clearing all IP addresses on wlan0
D/ConnectivityService(  879): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  879): calling update connectivity
D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  879): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  879): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  879): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  879): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  879): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/EntConnectivity(  879): Not allowed due to - mEnabled false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory( 1486): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Disconnected - quitting
D/WifiStateMachine(  879): updateConfiguredNetworkExpiration - currTime: 1453032782232
D/WifiStateMachine(  879): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,E/WifiStateMachine(  879): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  879): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524292
,E/WifiStateMachine(  879): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,D/CSLegacyTypeTracker(  879): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
I/WifiTrafficPoller(  879): evaluateTrafficStatsPolling
,D/CSLegacyTypeTracker(  879): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/CLocInfoService(  879): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  879): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  879): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  879): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  879): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityService(  879): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  879): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/ConnectivityService(  879): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,V/NetworkStats(  879): updateIfacesLocked()
,V/NetworkStats(  879): performPollLocked(flags=0x1)
D/NtpTrustedTime(  879): currentTimeMillis() cache hit
D/SmartBondingService(  879): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1178): updateDataNetType()
D/StatusBar.NetworkController( 1178): NoService, mRoamingIconId = 0
D/SmartBondingService(  879): getSBEnabled() enabled =false
D/SmartBondingService(  879): getSBEnabled() enabled =false
,D/SmartBondingService(  879): getSBEnabled() enabled =false
,D/NetworkStatsFactory(  879): UpdateStatsForKnox
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  879): currentTimeMillis() cache hit
,D/NtpTrustedTime(  879): currentTimeMillis() cache hit
D/NtpTrustedTime(  879): currentTimeMillis() cache hit
V/NetworkStats(  879): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  879): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1178): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/SmartBondingService(  879): getNetworkEnabled : wifi : true mobile : true
V/NetworkStats(  879): performPollLocked() took 10ms
D/NtpTrustedTime(  879): currentTimeMillis() cache hit
I/Hs20UtilService( 1300): Starting #7
D/NtpTrustedTime(  879): currentTimeMillis() cache hit
D/NtpTrustedTime(  879): currentTimeMillis() cache hit
E/WifiStateMachine(  879): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  879): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  879): setDetailed state send new extra info"NG700"
D/SecContentProvider2(  879): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  879): mCursor = null
D/SecContentProvider2(  879): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  879): mCursor = null
I/Hs20UtilService( 1300): Message received 5007
D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1300): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1300): MountReceiver.mPrefHandler - 7002
,D/FileWriteThread_Telephony( 1486): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1486): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1486): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1486): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1486): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1486): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1486): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1486): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1486): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1486): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1486): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1486): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1486): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1486): FileWriteThread : threadType = 3
,E/SMD     (  284): DCD ON
,D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ApplicationPolicy(  879): updateDataUsageMap
,D/Tethering(  879): MasterInitialState.processMessage what=3
D/SmartBondingService(  879): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  879): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  879): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  879): getSBEnabled() enabled =false
D/SmartBondingService(  879): getSBEnabled() enabled =false
D/SmartBondingService(  879): getSBEnabled() enabled =false
,D/SmartBondingService(  879): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2084): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  879): CLoinfo wifi false
W/SLocation(  879): No Active Data Connection
E/Zygote  ( 7756): MountEmulatedStorage()
E/Zygote  ( 7756): v2
I/libpersona( 7756): KNOX_SDCARD checking this for 1000
I/libpersona( 7756): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7756 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/DBG_DM  ( 3767): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/SELinux ( 7756): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7756): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7756): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3767): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7756): TimaSignature is unavailable
,D/ActivityThread( 7756): Added TimaKeyStore provider
,D/ResourcesManager( 7756): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG( 7756): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7756): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_DMDBOpenHelper( 7756): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 7756): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7756): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7756): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7756): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7756): noConnectivity : true
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7781): MountEmulatedStorage()
,E/Zygote  ( 7781): v2
I/libpersona( 7781): KNOX_SDCARD checking this for 10126
I/libpersona( 7781): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=7781 uid=10126 gids={50126, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 6874:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,I/SELinux ( 7781): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7781): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7781): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7781): TimaSignature is unavailable
,D/ActivityThread( 7781): Added TimaKeyStore provider
,D/ResourcesManager( 7781): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/libprocessgroup(  879): failed to open /acct/uid_10033/pid_6874/cgroup.procs: No such file or directory
,V/AlarmManager(  879): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,I/MusicStore( 7781): Database version: 104
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ResourcesManager( 7781): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7781): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7781): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 7781): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7781): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7781): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@617d199: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7781): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7781): GMSCore installation verified
,I/ConfigStore( 7781): Config Database version: 1
,I/wpa_supplicant( 1292): nl80211: Received scan results (6 BSSes)
I/wpa_supplicant( 1292): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1292): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1292): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1292): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  879): [1,453,032,783,283 ms] noteScanEnd no scan source
,E/WifiStateMachine(  879): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2a28b157 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  879): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  879): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,E/WifiStateMachine(  879): setDetailed state send new extra info0x
,D/SecContentProvider2(  879): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  879): mCursor = null
,I/CLocInfoService(  879): External Intent Received android.net.wifi.SCAN_RESULTS
,E/Vold    (  249): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7781): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  249): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7781): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  249): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7781): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter(  879): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter(  879): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/AudioPolicyManager(  291): getOutputsForDevice device 0002 -> 0002
,I/AudioService(  879): getStreamVolume 3 index 70
,I/MediaRouter( 7781): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/wpa_supplicant( 1292): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1292): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1292): Associated with C0.AA.48
,E/WifiStateMachine(  879): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  879): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider2(  879): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  879): mCursor = null
,E/Zygote  ( 7808): MountEmulatedStorage()
E/Zygote  ( 7808): v2
I/libpersona( 7808): KNOX_SDCARD checking this for 10002
I/libpersona( 7808): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7808 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7808): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7808): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7808): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiDisplayAdapter(  879): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7781): type=WIFI subType= reason=null isConnected=false
,I/wpa_supplicant( 1292): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1292): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  879): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  879): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/TimaKeyStoreProvider( 7808): TimaSignature is unavailable
E/WifiStateMachine(  879): setDetailed state send new extra info"NG700"
D/ActivityThread( 7808): Added TimaKeyStore provider
,D/SecContentProvider2(  879): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  879): mCursor = null
,I/ActivityManager(  879): Killing 6850:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,D/ResourcesManager( 7808): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/wpa_supplicant( 1292): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1292): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1292): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1292): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiStateMachine(  879): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
I/wpa_supplicant( 1292): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
E/WifiStateMachine(  879): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant( 1292): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1292): Blacklist: Clear (temp) 
I/wpa_supplicant( 1292): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  879): Network connection established
,D/WifiNative-HAL(  879): callSECApiVoid - ID [50]
E/WifiStateMachine(  879): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  879): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  879): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  879): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  879): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  879): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  879): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  879): Got NetworkAgent Messenger
D/ConnectivityService(  879): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  879): updateNetworkInfo()
D/ConnectivityService(  879): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  879): NetworkAgent connected
,E/WifiStateMachine(  879): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  879): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  879): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  879): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  277): Setting iface cfg
,E/WifiStateMachine(  879): Start Dhcp Watchdog 2
D/SecContentProvider2(  879): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  879): mCursor = null
,E/WifiStateMachine(  879): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  879): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/ConnectivityService(  879): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,W/libprocessgroup(  879): failed to open /acct/uid_10099/pid_6850/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Killing 6917:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7836): MountEmulatedStorage()
E/Zygote  ( 7836): v2
I/libpersona( 7836): KNOX_SDCARD checking this for 1000
I/libpersona( 7836): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7836 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7836): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  879): failed to open /acct/uid_10003/pid_6917/cgroup.procs: No such file or directory
,I/SELinux ( 7836): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7836): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7836): TimaSignature is unavailable
,D/ActivityThread( 7836): Added TimaKeyStore provider
,D/ResourcesManager( 7836): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,E/WifiStateMachine(  879): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  879): do suspend false
,D/SecContentProvider2(  879): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService(  879): InactiveState{ what=143375 }
D/WifiP2pService(  879): P2pEnabledState{ what=143375 }
,D/SecContentProvider2(  879): mCursor = null
,I/DIAGMON_AGENT( 7836): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7836): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/PowerManagerService(  879): [PWL] Off : 5s ago
,I/PowerManagerService(  879): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  879): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  879): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=879, ws=null) (elapsedTime=1383)
,I/DIAGMON_AGENT( 7836): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7836): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7836): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7836): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client( 7283): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7283): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,E/dhcpcd  ( 7856): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7856): version 5.5.6 starting
,E/dhcpcd  ( 7856): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/FOTA_Client( 7283): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7283): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7283): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7300): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7300): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453032783824
,I/KLMS-2.4.503: ( 7300): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7300): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7300): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  879): Killing 6932:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,I/dhcpcd  ( 7856): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7856): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7856): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7856): bssid match
,I/dhcpcd  ( 7856): wlan0: rebinding lease of 192.168.1.135
,I/SO_AGENT( 7315): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7863): MountEmulatedStorage()
E/Zygote  ( 7863): v2
I/libpersona( 7863): KNOX_SDCARD checking this for 1000
I/libpersona( 7863): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7863 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7863): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7863): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7863): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7863): TimaSignature is unavailable
,D/ActivityThread( 7863): Added TimaKeyStore provider
,W/libprocessgroup(  879): failed to open /acct/uid_10020/pid_6932/cgroup.procs: No such file or directory
,D/ResourcesManager( 7863): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7889): MountEmulatedStorage()
E/Zygote  ( 7889): v2
I/libpersona( 7889): KNOX_SDCARD checking this for 10038
I/libpersona( 7889): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7889 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 6947:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,I/SELinux ( 7889): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7889): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SELinux ( 7889): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7889): TimaSignature is unavailable
,D/ActivityThread( 7889): Added TimaKeyStore provider
,D/ResourcesManager( 7889): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/libprocessgroup(  879): failed to open /acct/uid_1000/pid_6947/cgroup.procs: No such file or directory
,E/SPPClientService( 7889): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 7889): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7889): PushLog.txt file is not deleted.
D/SPPClientService( 7889): PushLog.txt file is not deleted.
D/SPPClientService( 7889): ============PushLog. stop!
,E/SPPClientService( 7889): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6680): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6680): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6680): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 6680): [SLFUCHKMGR] constructor called
,I/SA      ( 6680): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6680): [OR] == isSIMCardReady false ==
,I/SA      ( 6680): [SCU] == networkStateCheck == false
I/SA      ( 6680): [OR] onReceive END
,E/SPPClientService( 7889): [[SystemStateMonitorService]] No Active Internet
,D/accuweather( 7183): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7183): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7908): MountEmulatedStorage()
E/Zygote  ( 7908): v2
I/libpersona( 7908): KNOX_SDCARD checking this for 1000
I/libpersona( 7908): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7908 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7908): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  879): Killing 6968:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,I/SELinux ( 7908): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7908): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7908): TimaSignature is unavailable
,D/ActivityThread( 7908): Added TimaKeyStore provider
,D/ResourcesManager( 7908): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7908): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7908): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7908): premStatus:2
,I/KnoxUsageLogPro( 7908): isEulaShown : false
I/KnoxUsageLogPro( 7908): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7923): MountEmulatedStorage()
E/Zygote  ( 7923): v2
I/libpersona( 7923): KNOX_SDCARD checking this for 10086
I/libpersona( 7923): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.NetStateReceiver: pid=7923 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 6987:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,I/SELinux ( 7923): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7923): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7923): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  879): failed to open /acct/uid_10112/pid_6968/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7923): TimaSignature is unavailable
,D/ActivityThread( 7923): Added TimaKeyStore provider
,D/ResourcesManager( 7923): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7923): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  879): failed to open /acct/uid_10118/pid_6987/cgroup.procs: No such file or directory
,I/dhcpcd  ( 7856): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,D/PushModule( 7923): [PushClientApplication] (main) PushClientApplication.onCreate()
,I/PushModule( 7923): [PushClientApplication] (main) PushModule version: 0.9.01.12
,D/PushModule( 7923): [PushClientApplication] (main) Discovered public push client. disable in app push client.
,I/dhcpcd  ( 7856): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  879): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService(  879): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  879): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/ChatON  ( 7923): [1][isApplicationInstalled] com.android.mms was installed
,W/ContextImpl( 7923): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
,W/ActivityManager(  879): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,D/ChatON  ( 7923): [1][a] ChatONV isn't installed.
,D/ChatON  ( 7923): [1][a] ChatONVPlugIn.isAvailable()
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7954): MountEmulatedStorage()
E/Zygote  ( 7954): v2
I/libpersona( 7954): KNOX_SDCARD checking this for 10088
I/libpersona( 7954): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7954 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7003:com.samsung.helphub/1000 (adj 15): bgCount ##41
,I/SELinux ( 7954): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/art     (  314): Explicit concurrent mark sweep GC freed 8734(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 393us total 12.102ms
,I/SELinux ( 7954): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7954): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 256us total 9.042ms
,D/TimaKeyStoreProvider( 7954): TimaSignature is unavailable
,D/ActivityThread( 7954): Added TimaKeyStore provider
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 239us total 7.961ms
,D/ResourcesManager( 7954): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  879): failed to open /acct/uid_1000/pid_7003/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Killing 7045:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,D/Headlines( 5449): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5449): getCountryCode(): countryCode = DE
,D/Headlines( 5449): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5449): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5449): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5449): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5449): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5449): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5449): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7987): MountEmulatedStorage()
E/Zygote  ( 7987): v2
I/libpersona( 7987): KNOX_SDCARD checking this for 10128
I/libpersona( 7987): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7987 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7987): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  879): failed to open /acct/uid_10166/pid_7045/cgroup.procs: No such file or directory
,I/SELinux ( 7987): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7987): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7987): TimaSignature is unavailable
,D/ActivityThread( 7987): Added TimaKeyStore provider
,D/ResourcesManager( 7987): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/WifiStateMachine(  879): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  879): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  879): do suspend true
,D/WifiP2pService(  879): InactiveState{ what=143375 }
D/WifiP2pService(  879): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  879): WifiStateMachine DHCP successful
,E/WifiStateMachine(  879): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  879): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  879): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  879): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  879): Not connected state, yet.
E/WifiStateMachine(  879): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiStateMachine(  879): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  879): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  879): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  879): callSECApiInt - ID [210]
,E/WifiStateMachine(  879): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  879): updateNetworkInfo()
,D/ConnectivityService(  879): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  879): Adding iface wlan0 to network 503
,I/CLocInfoService(  879): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  879): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  879): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  879): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.SingDnsChecker(  879): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  879): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,E/WifiStateMachine(  879): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  879): Now, connected state.
E/WifiStateMachine(  879): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  879): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,E/WifiStateMachine(  879): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  879): evaluateTrafficStatsPolling
,D/ConnectivityService(  879): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  879): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  879): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,I/CLocInfoService(  879): External Intent Received android.net.wifi.STATE_CHANGE
,E/ConnectivityService(  879): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  879): updateSourceRoutes : add source routing for type : 1
,D/ConnectivityService(  879): updateSourceRoutes : add src route for:192.168.1.135
V/        (  277): QcRouteController
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/WifiTrafficPoller(  879): evaluateTrafficStatsPolling
E/WifiStateMachine(  879): ConnectedState Enter  mScreenOn=false scanperiod=20000
I/WifiTrafficPoller(  879): mBoosterFLAG : 0
I/WifiTrafficPoller(  879): current booster mode : FullMode
,D/WifiNative-HAL(  879): callSECApiVoid - ID [212]
,I/CLocInfoService(  879): External Intent Received android.net.wifi.STATE_CHANGE
,V/        (  277): QcRouteController
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/WifiStateMachine(  879): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
,I/jxcore-log( 7648): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7648): 
,D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,I/jxcore-log( 7648): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7648): 
,V/        (  277): QcRouteController
,V/        (  277): QcRouteController
,V/        (  277): QcRouteController
,V/        (  277): QcRouteController
,V/        (  277): QcRouteController
,I/jxcore-log( 7648): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7648): 
,V/        (  277): QcRouteController
,I/jxcore-log( 7648): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7648): 
,D/ConnectivityService(  879): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  879): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  879): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  879): calling update connectivity
E/ConnectivityService(  879): updateNetworkInfo()
D/ConnectivityService(  879): ignoring duplicate network state non-change
E/ConnectivityService(  879): updateNetworkInfo()
D/ConnectivityService(  879): ignoring duplicate network state non-change
D/ConnectivityService(  879): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  879): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  879): calling update connectivity
D/ConnectivityService(  879): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  879):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  879):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  879):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  879): currentScore = 0, newScore = 60
D/ConnectivityService(  879):    accepting network in place of null
D/ConnectivityService(  879): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): DefaultState{ when=-4ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Validated
,D/TelephonyNetworkFactory( 1486): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  879): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker(  879): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
,D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  879): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  879): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/SmartBondingService(  879): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  879): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  879): getSBEnabled() enabled =false
D/SmartBondingService(  879): getSBEnabled() enabled =false
D/SmartBondingService(  879): getSBEnabled() enabled =false
,D/ConnectivityService(  879): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/EntConnectivity(  879): Not allowed due to - mEnabled false
D/ConnectivityService(  879): calling update connectivity
V/NetworkStats(  879): updateIfacesLocked()
D/NtpTrustedTime(  879): currentTimeMillis() cache hit
V/NetworkStats(  879): performPollLocked(flags=0x1)
D/SmartBondingService(  879): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  879): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkStatsFactory(  879): UpdateStatsForKnox
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  879): currentTimeMillis() cache hit
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1178): updateDataNetType()
D/StatusBar.NetworkController( 1178): NoService, mRoamingIconId = 0
,D/NtpTrustedTime(  879): currentTimeMillis() cache hit
D/NtpTrustedTime(  879): currentTimeMillis() cache hit
V/NetworkStats(  879): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  879): currentTimeMillis() cache hit
,V/NetworkStats(  879): performPollLocked() took 3ms
D/NtpTrustedTime(  879): currentTimeMillis() cache hit
,D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524290
D/ConnectivityService(  879): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  879): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  879):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  879):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  879): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  879): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  879): calling update connectivity
D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/StatusBar.NetworkController( 1178): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/ConnectivityService(  879): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/NtpTrustedTime(  879): currentTimeMillis() cache hit
D/NtpTrustedTime(  879): currentTimeMillis() cache hit
,D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524290
,D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/jxcore-log( 7648): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7648): 
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1178): updateDataNetType()
D/StatusBar.NetworkController( 1178): NoService, mRoamingIconId = 0
,D/StatusBar.NetworkController( 1178): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/jxcore-log( 7648): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7648): 
,E/Vold    (  249): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7987): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  249): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7987): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  249): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7987): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  249): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7987): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WebViewFactory( 7987): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7987): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7987): Loading: webviewchromium
,I/LibraryLoader( 7987): Time to load native libraries: 3 ms (timestamps 3345-3348)
,I/LibraryLoader( 7987): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7987): Binding Chromium to main looper Looper (main, tid 1) {3bec50e3}
,I/LibraryLoader( 7987): Expected native library version number "",actual native library version number ""
,I/chromium( 7987): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7987): Initializing chromium process, renderers=0
,W/art     ( 7987): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7987): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7987): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7987): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7987): Requires BLUETOOTH permission
,I/Adreno-EGL( 7987): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7987): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7987): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7987): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7987): Remote Branch: 
I/Adreno-EGL( 7987): Local Patches: 
I/Adreno-EGL( 7987): Reconstruct Branch: 
,I/NSApplication( 7987): Starting up...
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8059): MountEmulatedStorage()
E/Zygote  ( 8059): v2
I/libpersona( 8059): KNOX_SDCARD checking this for 10138
I/libpersona( 8059): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=8059 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7061:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): bgCount ##41
,I/SELinux ( 8059): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8059): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8059): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8059): TimaSignature is unavailable
,D/ActivityThread( 8059): Added TimaKeyStore provider
,W/libprocessgroup(  879): failed to open /acct/uid_10170/pid_7061/cgroup.procs: No such file or directory
,D/ResourcesManager( 8059): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 8059): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8059): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8059): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 8059): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8059): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 8059): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8074): MountEmulatedStorage()
E/Zygote  ( 8074): v2
I/libpersona( 8074): KNOX_SDCARD checking this for 10163
I/libpersona( 8074): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=8074 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 4858:com.google.android.gms.wearable/u0a12 (adj 15): bgCount ##41
,I/SELinux ( 8074): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8074): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8074): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8074): TimaSignature is unavailable
,D/ActivityThread( 8074): Added TimaKeyStore provider
,W/libprocessgroup(  879): failed to open /acct/uid_10012/pid_4858/cgroup.procs: No such file or directory
,D/ResourcesManager( 8074): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8074): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8074): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8074): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8074): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/jxcore-log( 7648): Test app app.js loaded
I/jxcore-log( 7648): 
,I/Choreographer( 7648): Skipped 207 frames!  The application may be doing too much work on its main thread.
,E/SMD     (  284): DCD ON
,I/chromium( 7648): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 7648): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  879): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  879): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  879): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  879): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  879): CLocinfo wifi true 
D/Tethering(  879): MasterInitialState.processMessage what=3
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  879): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  879): getSBEnabled() enabled =false
D/SmartBondingService(  879): getSBEnabled() enabled =false
D/SmartBondingService(  879): getSBEnabled() enabled =false
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2084): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  879): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 2126): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2126): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3767): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3767): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7781): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  879): exchangeData() failure , invalid userId
,D/RCPManagerService(  879): exchangeData() failure , invalid userId
,E/Watchdog(  879): !@Sync 3
,I/art     (  879): Explicit concurrent mark sweep GC freed 76958(4MB) AllocSpace objects, 8(128KB) LOS objects, 30% free, 36MB/52MB, paused 1.268ms total 91.618ms
,D/SecContentProvider2(  879): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  879): mCursor = null
,D/RCPManagerService(  879): exchangeData() failure , invalid userId
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,D/RCPManagerService(  879): exchangeData() failure , invalid userId
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,E/Zygote  ( 8097): MountEmulatedStorage()
E/Zygote  ( 8097): v2
I/libpersona( 8097): KNOX_SDCARD checking this for 10078
I/libpersona( 8097): KNOX_SDCARD not a persona
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,I/ActivityManager(  879): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8097 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,I/SELinux ( 8097): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 8097): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  879): exchangeData() failure , invalid userId
E/SELinux ( 8097): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/RCPManagerService(  879): exchangeData() failure , invalid userId
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7450): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7450): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7450): StateMachine : Current State = 1
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7450): StateMachine : Changed Current State = 1
,I/ActivityManager(  879): Killing 7085:com.sec.android.app.samsungapps/u0a40 (adj 15): bgCount ##41
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/com.peel.receiver.ConnectivityActionReceiver( 1659): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 1659): 
D/com.peel.receiver.ConnectivityActionReceiver( 1659): 
D/com.peel.receiver.ConnectivityActionReceiver( 1659): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 1659): 
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 8097): TimaSignature is unavailable
,D/ActivityThread( 8097): Added TimaKeyStore provider
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 1659): 
D/com.peel.receiver.ConnectivityActionReceiver( 1659): 
D/com.peel.receiver.ConnectivityActionReceiver( 1659):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 1659): 
D/com.peel.receiver.ConnectivityActionReceiver( 1659): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 1659): 
D/com.peel.receiver.ConnectivityActionReceiver( 1659): 
D/com.peel.receiver.ConnectivityActionReceiver( 1659): last run: 1453023874109 -- System.currentTimeMillis()-last_run: 8911615
D/com.peel.receiver.ConnectivityActionReceiver( 1659): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 1659): ... skip last_72_check
,I/ActivityManager(  879): Killing 7118:com.sec.android.app.videoplayer/u0a54 (adj 15): bgCount ##41
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 8097): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,E/Zygote  ( 8112): MountEmulatedStorage()
I/libpersona( 8112): KNOX_SDCARD checking this for 10178
E/Zygote  ( 8112): v2
I/libpersona( 8112): KNOX_SDCARD not a persona
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,I/ActivityManager(  879): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8112 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,I/SELinux ( 8112): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
I/SELinux ( 8112): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,V/BitmapFactory( 8074): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,E/SELinux ( 8112): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 8097): onCreate
,D/BadgeProvider( 8097): DatabaseHelper
,D/TimaKeyStoreProvider( 8112): TimaSignature is unavailable
D/BadgeProvider( 8097): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/ActivityThread( 8112): Added TimaKeyStore provider
,D/ResourcesManager( 8112): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,D/BadgeProvider( 8097): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 8097): sendNotify, [notify] : null
D/Launcher.Model( 1492): reloadBadges entered.
D/BadgeProvider( 8097): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8097): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 8097): update, [UpdateCount] : 1
,I/ActivityManager(  879): Killing 5859:com.sec.android.gallery3d/u0a48 (adj 15): bgCount ##41
,W/libprocessgroup(  879): failed to open /acct/uid_10040/pid_7085/cgroup.procs: No such file or directory
,W/libprocessgroup(  879): failed to open /acct/uid_10054/pid_7118/cgroup.procs: No such file or directory
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2495): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2495): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 8129): MountEmulatedStorage()
,E/Zygote  ( 8129): v2
I/libpersona( 8129): KNOX_SDCARD checking this for 10040
I/libpersona( 8129): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=8129 uid=10040 gids={50040, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 8129): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  879): failed to open /acct/uid_10048/pid_5859/cgroup.procs: No such file or directory
,I/SELinux ( 8129): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8129): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/ActivityManager(  879): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/TimaKeyStoreProvider( 8129): TimaSignature is unavailable
,D/ActivityThread( 8129): Added TimaKeyStore provider
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 8129): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,D/ConnectivityService(  879): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  879): uri = 14 selection = getSealedState
D/SecContentProvider2(  879): mCursor = null
,D/SecContentProvider2(  879): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2495): [AccountUtils] Account not ready
W/Kids    ( 2495): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2495): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2495): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2495): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2495): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2495): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2495): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2495): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2495): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2495): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 8129): notifyNetworkActivated
,W/ContextImpl( 8129): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  879): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/KeyguardViewMediator( 1178): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/hcjo    ( 8129): AutoUpdateManager:IDLE:execute
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/KeyguardViewMediator( 1178): doKeyguard: not showing because lockscreen is off
,I/Hs20UtilService( 1300): Starting #8
D/InitializeManagerStateMachine( 8129): execute::IDLE:EXECUTE
,I/Hs20UtilService( 1300): Message received 5007
D/InitializeManagerStateMachine( 8129): exit::IDLE
D/InitializeManagerStateMachine( 8129): entry::NETWORK_CHECK
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 8129): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 8129): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 8129): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 8129): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 8129): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 8129): entry::SUCCESS
D/hcjo    ( 8129): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1300): MountReceiver.onReceive - Keep current state
,D/hcjo    ( 8129): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 8129): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 8129): exit::SUCCESS
D/InitializeManagerStateMachine( 8129): entry::IDLE
,I/Hs20UtilService( 1300): Starting #9
,I/Hs20UtilService( 1300): Message received 5007
,I/ActivityManager(  879): Killing 7200:com.sec.android.widgetapp.digitalclock/u0a94 (adj 15): bgCount ##41
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1300): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1300): Starting #10
,I/Hs20UtilService( 1300): Message received 5007
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1300): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1300): Starting #11
,I/Hs20UtilService( 1300): Message received 5007
D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1300): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  879): callSECApi what=220
,D/WifiStateMachine(  879): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,W/libprocessgroup(  879): failed to open /acct/uid_10094/pid_7200/cgroup.procs: No such file or directory
,I/PCWCLIENTTRACE_PushUtil( 7756): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7756): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7756): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7756): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7836): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7836): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/SurfaceFlinger(  250): id=16 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/PowerManagerService(  879): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=879
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,I/FOTA_Client( 7283): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7283): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7283): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7283): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7283): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7300): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7300): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453032786305
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,I/KLMS-2.4.503: ( 7300): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7300): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7300): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7300): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7300): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7315): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7889): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6680): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6680): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6680): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6680): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6680): [OR] == isSIMCardReady false ==
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6680): [SCU] == networkStateCheck == true
,I/SA      ( 6680): [DM] getCountryCodeFromCSC : DE
I/SA      ( 6680): isChinaCountryCode : false
I/SA      ( 6680): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6680): [OR] == networkStateCheck true ==
,I/SA      ( 6680): [OR] GetMyCountryZoneTask
,I/SA      ( 6680): [OR] onReceive END
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 7183): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7183): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/SA      ( 6680): [SRS] prepareGetMyCountryZone
,I/KnoxUsageLogPro( 7908): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7908): premStatus:2
,I/KnoxUsageLogPro( 7908): isEulaShown : false
I/KnoxUsageLogPro( 7908): KnoxUsageReceiver onReceive : not Processible, just return
,I/SA      ( 6680): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6680): [SSP] query invoked
,I/SA      ( 6680): [TPMU] GetMccFromDB : null
,I/SA      ( 6680): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6680): [TPM] isNoProxy(default) : true
,D/Headlines( 5449): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5449): getCountryCode(): countryCode = DE
,D/Headlines( 5449): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5449): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5449): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5449): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5449): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5449): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5449): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 8059): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8059): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 8059): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  879): exchangeData() failure , invalid userId
E/File    ( 6680): fail readDirectory() errno=2
D/RCPManagerService(  879): exchangeData() failure , invalid userId
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7450): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7450): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7450): StateMachine : Current State = 1
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7450): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 1659): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 1659): 
D/com.peel.receiver.ConnectivityActionReceiver( 1659): 
D/com.peel.receiver.ConnectivityActionReceiver( 1659): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 1659): 
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 1659): 
D/com.peel.receiver.ConnectivityActionReceiver( 1659): 
D/com.peel.receiver.ConnectivityActionReceiver( 1659):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 1659): 
D/com.peel.receiver.ConnectivityActionReceiver( 1659): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 1659): 
D/com.peel.receiver.ConnectivityActionReceiver( 1659): 
D/com.peel.receiver.ConnectivityActionReceiver( 1659): last run: 1453023874109 -- System.currentTimeMillis()-last_run: 8912350
D/com.peel.receiver.ConnectivityActionReceiver( 1659): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 1659): ... skip last_72_check
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2495): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2495): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 8129): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 8129): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 8129): exit::IDLE
,D/InitializeManagerStateMachine( 8129): entry::NETWORK_CHECK
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 8129): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 8129): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 8129): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 8129): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 8129): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 8129): entry::SUCCESS
D/hcjo    ( 8129): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 8129): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 8129): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 8129): exit::SUCCESS
D/InitializeManagerStateMachine( 8129): entry::IDLE
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  879): uri = 14 selection = getSealedState
,D/SecContentProvider2(  879): mCursor = null
D/SecContentProvider2(  879): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/Kids    ( 2495): [AccountUtils] Account not ready
W/Kids    ( 2495): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2495): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2495): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2495): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2495): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2495): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2495): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2495): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2495): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2495): 	at java.lang.Thread.run(Thread.java:818)
,I/PhoneStatusBar( 1178): Icon Only
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,I/SA      ( 6680): [RC New] Execute method=[GET] start
,I/SA      ( 6680): [RC New] Security=[true]
,I/System.out( 6680): Thread-1085(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6680): Thread-1085(ApacheHTTPLog):isShipBuild true
I/System.out( 6680): Thread-1085(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/SA      ( 6680): [RC New] [v2liruge] api execute + 1003
,I/SA      ( 6680): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6680): AsyncTask #1 calls detatch()
,I/SA      ( 6680): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6680): [OCP] update openData : PL
,I/SA      ( 6680): [TPMU] getNetworkMcc : 
,I/SA      ( 6680): [SCU] saveMccToPreferece Start
,I/SA      ( 6680): [SCU] RegionMCC : 260
I/SA      ( 6680): [SSP] query invoked
,I/SA      ( 6680): [TPMU] GetMccFromDB : null
,I/SA      ( 6680): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6680): [SCU] saveMccToPreferece End
,I/SA      ( 6680): [RC New] executeRequest [v2liruge] end. 1079
,I/SA      ( 6680): [RC New] Execute end
,I/SA      ( 6680): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6680): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  ( 7856): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7856): wlan0: sendmsg: Cannot assign requested address
,I/WifiStateMachine(  879): REQUEST_POWER_SAVE_ON
,V/AlarmManager(  879): waitForAlarm result :8
,E/WifiStateMachine(  879): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/SMD     (  284): DCD ON
,E/Zygote  ( 8181): MountEmulatedStorage()
,E/Zygote  ( 8181): v2
I/libpersona( 8181): KNOX_SDCARD checking this for 10012
I/libpersona( 8181): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=8181 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 8181): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8181): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8181): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8181): TimaSignature is unavailable
,D/ActivityThread( 8181): Added TimaKeyStore provider
,D/ResourcesManager( 8181): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 8181): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8181): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ResourcesManager( 7781): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7781): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7781): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 7781): Using the GMSCore's GoogleHttpClient
,I/art     ( 1708): Explicit concurrent mark sweep GC freed 27215(1658KB) AllocSpace objects, 19(1539KB) LOS objects, 40% free, 17MB/29MB, paused 469us total 25.854ms
,I/MultiDex( 8181): VM with version 2.1.0 has multidex support
I/MultiDex( 8181): install
I/MultiDex( 8181): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8181): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/SSRM:m  (  879): SIOP:: AP = 410, PST = 446, CUR = 300
,I/MusicLeanback( 7781): Conditions not met for autocaching.
I/MusicLeanback( 7781): Stop autocaching.
,E/ActivityThread( 7781): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@337cf91b that was originally bound here
E/ActivityThread( 7781): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@337cf91b that was originally bound here
E/ActivityThread( 7781): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 7781): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 7781): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 7781): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 7781): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 7781): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 7781): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7781): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7781): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7781): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 7781): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 7781): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 7781): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 7781): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 7781): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 7781): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 7781): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 7781): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 7781): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7781): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 7781): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 7781): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7781): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7781): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 7781): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityThread( 8181): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8181): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@18423286: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8181): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1708): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1708): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2495): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 8181): callingUid 10012, callindPid: 8181
,D/LocationInitializer( 2495): Restart initialization of location
,E/MDM     ( 2156): [237] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/WearableClient( 7781): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7781): WearableClientImpl.onPostInitHandler: done
,E/WifiStateMachine(  879): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/WearableClient( 7781): WearableClientImpl.onPostInitHandler: done
D/ConnectivityService(  879): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  879): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  879): identical MTU - not setting
D/ConnectivityService(  879): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  879): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
E/WifiStateMachine(  879): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
V/        (  277): QcRouteController
,D/SmartBondingService(  879): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  879): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  879): getSBEnabled() enabled =false
D/SmartBondingService(  879): getSBEnabled() enabled =false
D/SmartBondingService(  879): getSBEnabled() enabled =false
,D/WearableClient( 7781): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 7781): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 7781): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/        (  277): QcRouteController
,W/NetworkManagementService(  879): route cmd failed: 
W/NetworkManagementService(  879): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  879): '
W/NetworkManagementService(  879): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  879): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  879): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  879): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  879): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  879): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  879): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  879): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  879): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  879): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Nat464Xlat(  879): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  879): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  879): calling update connectivity
D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  879): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  879): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  879): calling update connectivity
D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524295
,D/ConnectivityService(  879): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524295
,D/PackageManager(  879): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager(  879): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager( 1492): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 1492): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1492): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1492): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/InputReader(  879): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 1492): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 1492): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 1492): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,E/Zygote  ( 8228): MountEmulatedStorage()
E/Zygote  ( 8228): v2
I/libpersona( 8228): KNOX_SDCARD checking this for 10034
I/libpersona( 8228): KNOX_SDCARD not a persona
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,I/ActivityManager(  879): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8228 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/SELinux ( 8228): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8228): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
E/SELinux ( 8228): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/RegisteredServicesCache( 1477): empty dynamic service
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/TimaKeyStoreProvider( 8228): TimaSignature is unavailable
,D/ActivityThread( 8228): Added TimaKeyStore provider
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/SecContentProvider2(  879): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  879): mCursor = null
D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/FeatureConfig( 8228): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService(  879): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  879): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  879): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  879): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8228): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8228): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8228): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 8228): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 8228): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8228): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8228): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8228): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8228): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 8228): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8228): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8228): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 8228): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 8228): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8228): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 8228): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8228): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8228): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 8228): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 8228): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8228): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 8228): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/SurfaceFlinger(  250): id=16 Removed Toast (8/9)
,I/SurfaceFlinger(  250): id=16 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/PowerManagerService(  879): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 879) eventTime = 107958
,D/PowerManagerService(  879): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=879 (0x0)
D/PowerManagerService(  879): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=879, ws=WorkSource{10059}) (elapsedTime=3470)
,I/ActivityManager(  879): Killing 7217:com.sec.android.widgetapp.dualclockdigital/u0a103 (adj 15): bgCount ##41
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,E/Zygote  ( 8247): MountEmulatedStorage()
I/libpersona( 8247): KNOX_SDCARD checking this for 10048
E/Zygote  ( 8247): v2
I/libpersona( 8247): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=8247 uid=10048 gids={50048, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 8247): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8247): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8247): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8247): TimaSignature is unavailable
,D/ActivityThread( 8247): Added TimaKeyStore provider
,W/libprocessgroup(  879): failed to open /acct/uid_10103/pid_7217/cgroup.procs: No such file or directory
,D/ResourcesManager( 8247): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8247): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8247): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8247): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8247): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8247): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 8247): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8247): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8247): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/SensorService(  879): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
,I/SensorService(  879): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  879): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
,D/Spen    ( 8247): SpenSdk version level = 55
D/Spen    ( 8247): SpenSdk jar version = 3.0.238
,D/Spen    ( 8247): SpenSdk apk version = 3.0.238
D/Spen    ( 8247): Server UPDATE Check
,W/linker  ( 8247): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/SPenError( 8247): JNI_OnLoad
,D/JNI_Bitmap( 8247): Init .. Done
,D/SPenSpiDecoder( 8247): JNI_OnLoad .. Done
D/SPenError( 8247): JNI_OnLoad Success
,D/PluginManager( 8247): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
,D/PluginManager( 8247): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
,D/Init_SPenSdk_Jni( 8247): JNI_OnLoad
,D/Init_SPenSdk_Jni( 8247): AndroidSDK: 21
D/Init_SPenSdk_Jni( 8247): JNI_OnLoad .. Done
,D/Model_ObjectBase_Jni( 8247): JNI_OnLoad .. Done
,D/Model_ObjectStroke_Jni( 8247): JNI_OnLoad .. Done
D/Model_ObjectImage_Jni( 8247): JNI_OnLoad .. Done
,D/Model_ObjectText_Jni( 8247): JNI_OnLoad .. Done
D/Model_ObjectContainer_Jni( 8247): JNI_OnLoad .. Done
,D/Model_PageDoc_Jni( 8247): JNI_OnLoad .. Done
,D/Model_NoteDoc_Jni( 8247): check build type eng[0]
D/Model_NoteDoc_Jni( 8247): JNI_OnLoad .. Done
D/Model_NoteFile_Jni( 8247): JNI_OnLoad .. Done
,D/Model_ObjectUtil_Jni( 8247): JNI_OnLoad .. Done
D/Model   ( 8247): OnLoad class Done
,I/GAV4    ( 7987): Thread[GAThread,5,main]: No campaign data found.
,D/spe_log ( 8247): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
,D/SPen_Library( 8247): Draw Engine JNI_OnLoad enter!!
D/SPen_Library( 8247): Canvas JNI_OnLoad enter!!
,D/SPen_Library( 8247): Canvas JNI_OnLoad Success
,D/SPen_Library( 8247): TextView JNI_OnLoad enter!!
D/SPen_Library( 8247): TextView JNI_OnLoad Success
,D/SPen_Library( 8247): Text JNI_OnLoad enter!!
D/SPen_Library( 8247): Text JNI_OnLoad Success
D/SPen_Library( 8247): FontManager JNI_OnLoad enter!!
,D/SPen_Library( 8247): FontManager JNI_OnLoad Success
D/SPen_Library( 8247): CapturePage JNI_OnLoad enter!!
D/SPen_Library( 8247): CapturePage JNI_OnLoad Success
D/SPen_Library( 8247): Multi JNI_OnLoad enter!!
,D/SPen_Library( 8247): Multi JNI_OnLoad Success
D/SPen_Library( 8247): Draw Engine JNI_OnLoad Success
,D/SPen_Library( 8247): Brush JNI_OnLoad enter!!
,D/SPen_Library( 8247): Brush JNI_OnLoad Success
,D/SPen_Library( 8247): ChineseBrush JNI_OnLoad enter!!
,D/SPen_Library( 8247): ChineseBrush JNI_OnLoad Success
,D/SPen_Library( 8247): InkPen JNI_OnLoad enter!!
,D/SPen_Library( 8247): InkPen JNI_OnLoad Success
,D/SPen_Library( 8247): Marker JNI_OnLoad enter!!
,D/SPen_Library( 8247): Marker JNI_OnLoad Success
,D/SPen_Library( 8247): Pencil JNI_OnLoad enter!!
,D/SPen_Library( 8247): Pencil JNI_OnLoad Success
,D/SPen_Library( 8247): NativePen JNI_OnLoad enter!!
,D/SPen_Library( 8247): NativePen JNI_OnLoad Success
,D/SPen_Library( 8247): MontblancFountainPen JNI_OnLoad enter!!
,D/SPen_Library( 8247): MontblancFountainPen JNI_OnLoad Success
,D/SPen_Library( 8247): MontblancCalligraphyPen JNI_OnLoad enter!!
,D/SPen_Library( 8247): MontblancCalligraphyPen JNI_OnLoad Success
,D/SPen_Library( 8247): MagicPen JNI_OnLoad enter!!
,D/SPen_Library( 8247): MagicPen JNI_OnLoad Success
,D/SPen_Library( 8247): ObliquePen JNI_OnLoad enter!!
,D/SPen_Library( 8247): ObliquePen JNI_OnLoad Success
,D/SPen_Library( 8247): FountainPen JNI_OnLoad enter!!
,D/SPen_Library( 8247): FountainPen JNI_OnLoad Success
D/Spen    ( 8247): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni( 8247): SPenSdk_init2
,D/Init_SPenSdk( 8247): Init - screen_width = 1080, screen_height = 1920, maxCacheSize = 5 M
,D/Init_SPenSdk( 8247): Total S Pen SDK Directory Size = 0
D/Spen    ( 8247): initialize complete
,D/NearbySource( 8247): Nearby Source Create!
,D/NearbyContext( 8247): Nearby Context Create!
,E/Vold    (  249): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8247): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 8247): Samsung link source created
,D/SLinkClient( 8247): query devices()
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8273): MountEmulatedStorage()
E/Zygote  ( 8273): v2
I/libpersona( 8273): KNOX_SDCARD checking this for 10042
I/libpersona( 8273): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.samsung.android.sdk.samsunglink for content provider com.samsung.android.sdk.samsunglink/com.mfluent.asp.datamodel.ASPMediaStoreProvider: pid=8273 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 8273): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8273): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/WifiDisplayAdapter(  879): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/SELinux ( 8273): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ContactProvider( 8247): getAllContactInfoList Start
,D/WifiDisplayAdapter(  879): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/TimaKeyStoreProvider( 8273): TimaSignature is unavailable
,D/ActivityThread( 8273): Added TimaKeyStore provider
,D/ResourcesManager( 8273): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,D/ContactProvider( 8247): getAllContactInfoList End
,I/syncContacts( 8247): thread: 1375, sync time = 77
,W/ResourcesManager( 8273): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8273): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1575): Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8290): MountEmulatedStorage()
E/Zygote  ( 8290): v2
I/libpersona( 8290): KNOX_SDCARD checking this for 10075
I/libpersona( 8290): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=8290 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  314): Explicit concurrent mark sweep GC freed 8743(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 279us total 15.710ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 8.019ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 243us total 7.589ms
,I/SELinux ( 8290): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  879): Killing 4916:com.android.defcontainer/u0a5 (adj 15): bgCount ##41
,I/SELinux ( 8290): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/ActivityManager(  879): Killing 7252:com.sec.android.app.camera/u0a154 (adj 15): bgCount ##42
,E/SELinux ( 8290): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8290): TimaSignature is unavailable
,D/ActivityThread( 8290): Added TimaKeyStore provider
,I/UpdateIcingCorporaServi( 1575): UpdateCorporaTask done [took 100 ms] updated apps [took 100 ms] 
,D/ResourcesManager( 8290): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/FileShare-Server( 8290): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  879): failed to open /acct/uid_10005/pid_4916/cgroup.procs: No such file or directory
,W/libprocessgroup(  879): failed to open /acct/uid_10154/pid_7252/cgroup.procs: No such file or directory
,E/Zygote  ( 8311): MountEmulatedStorage()
I/libpersona( 8311): KNOX_SDCARD checking this for 1000
E/Zygote  ( 8311): v2
I/libpersona( 8311): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=8311 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 6700:com.android.mms/u0a50 (adj 15): bgCount ##41
,I/SELinux ( 8311): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8311): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8311): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/CountryDetector(  879): No listener is left
,D/TimaKeyStoreProvider( 8311): TimaSignature is unavailable
,D/ActivityThread( 8311): Added TimaKeyStore provider
,W/libprocessgroup(  879): failed to open /acct/uid_10050/pid_6700/cgroup.procs: No such file or directory
,W/System.err( 8273): java.lang.NoSuchMethodException: getImeiInCDMAGSMPhone []
,W/System.err( 8273): 	at java.lang.Class.getMethod(Class.java:665)
W/System.err( 8273): 	at com.sec.pcw.util.c.c(SourceFile:295)
W/System.err( 8273): 	at com.sec.pcw.service.account.a.b(SourceFile:250)
W/System.err( 8273): 	at com.sec.pcw.service.account.a.a(SourceFile:52)
W/System.err( 8273): 	at com.mfluent.asp.datamodel.Device.r(SourceFile:359)
W/System.err( 8273): 	at com.mfluent.asp.datamodel.Device.<init>(SourceFile:248)
W/System.err( 8273): 	at com.mfluent.asp.datamodel.t.a(SourceFile:136)
W/System.err( 8273): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:484)
W/System.err( 8273): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
W/System.err( 8273): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
W/System.err( 8273): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
W/System.err( 8273): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
W/System.err( 8273): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
W/System.err( 8273): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 8273): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 8273): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8273): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 8273): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 8273): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 8273): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 8273): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 8273): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/ResourcesManager( 8311): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,I/SL_DEBUG( 8273): isLoggable:: isProductShip = 1
,I/SL_DEBUG( 8273): isLoggable:: SL_DEBUG_EXIST = false
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ShortcutReceiver( 8311):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,I/art     (  879): Explicit concurrent mark sweep GC freed 49329(3MB) AllocSpace objects, 5(210KB) LOS objects, 30% free, 36MB/52MB, paused 1.252ms total 84.548ms
,I/SLinkClient( 8247): queryDevices : cursor.getCount() = [ 0 ]
,D/SLinkClient( 8247): onStorageUpdated(), uri = [ slink://slink ]
,I/ActivityManager(  879): Killing 7335:com.samsung.android.scloud.sync/u0a67 (adj 15): bgCount ##41
,I/SLinkClient( 8247): SlinkBackgroundJob: slink wake up ok!
D/PackageBroadcastService( 2495): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,E/Vold    (  249): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8273): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,I/PeopleContactsSync( 2495): CP2 sync disabled
,E/Vold    (  249): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8273): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,W/libprocessgroup(  879): failed to open /acct/uid_10067/pid_7335/cgroup.procs: No such file or directory
,V/Transcoder( 8273): Transcoder(0xaf07a830)::constructor
V/Transcoder( 8273): addObitRecipient
V/TMI-JNI ( 8273): Mobile Transcoder JNI version 1.6.0/20131120/4.4
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  879): waitForAlarm result :4
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4342, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  879): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  879): stay LED for fully charged
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  879):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3228): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3228): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1708): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_google_search.png
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7756): mConnectivityHandler : connected
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7756): [hasSamungAccount] - No Samsung Account
V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  879): uri = 14 selection = getSealedState
D/SecContentProvider2(  879): mCursor = null
,D/SecContentProvider2(  879): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/Search.LoginHelper( 1575): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/PhoneStatusBar( 1178): Icon Only
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,I/CSTORAGE( 7756): ================================================
I/CSTORAGE( 7756):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 7756): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7756): [GetString-S]
E/art     ( 7756): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI( 7756): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7756): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7756): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7756): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7756): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7756): [ensureRegistration] - No Samsung account
,D/GCM     ( 1708): Connected
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1708): Message class com.google.f.a.a.p
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  284): DCD ON
,I/dhcpcd  ( 7856): wlan0: sending IPv6 Router Solicitation
,I/PowerManagerService(  879): [PWL] Off : 15s ago
,I/ActivityManager(  879): Killing 7351:com.sec.android.app.clockpackage/u0a91 (adj 15): bgCount ##41
,W/libprocessgroup(  879): failed to open /acct/uid_10091/pid_7351/cgroup.procs: No such file or directory
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  284): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/dhcpcd  ( 7856): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 7856): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine( 8129): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 8129): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 8129): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 8129): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 8129): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 8129): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 8129): entry::IDLE
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/PreloadUpdateManagerStateMachine( 8129): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 8129): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 8129): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 8129): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 8129): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 8129): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 8129): entry::IDLE
,E/SMD     (  284): DCD ON
,D/FactoryTest( 6513): Not factory mode
,D/FactoryTest( 6513): Not factory mode. isFactoryMode() returend false
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/MTPRx   ( 6513): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6513): still no open session command from host, so toast
,W/ContextImpl( 6513): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6513): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6513): Timeline: Activity_launch_request id:com.android.settings time:115769
,E/PersonaManagerService(  879): inState():  stateMachine is null !!
,V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  879): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  879): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,E/MTPRx   ( 6513): started activity for popup
,I/SQLiteSecureOpenHelper( 3552): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3552): getDatabaseLocked(b,b,pwd)...
,D/ResourcesManager( 6513): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6513): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6513): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6513): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6513): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6513): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6513): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6513): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6513): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,D/InputMethodManagerService(  879): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  879): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@22a9b2aa attribute=null, token = android.os.BinderProxy@2ad0f58d
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png,
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6513): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6513): dev.kiessupport is : TRUE
,D/Activity( 6513): performCreate Call secproduct feature valuefalse
,D/Activity( 6513): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/ActivityManager(  879): post active user change for 0
,D/KnoxTimeoutHandler(  879): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  879): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,I/Timeline( 7648): Timeline: Activity_idle id: android.os.BinderProxy@10b63676 time:116231
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,V/AlarmManager(  879): waitForAlarm result :4
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  879): SIOP:: AP = 380, PST = 437, CUR = 300
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,V/AlarmManager(  879): waitForAlarm result :4
,E/SMD     (  284): DCD ON
,W/ActivityManager(  879): mDVFSHelper.release()
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6412): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6412): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6412): [1] 5.onFinished: Scheduling replication attempt 3.
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  879): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  879):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3228): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3228): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  284): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  284): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/PowerManagerService(  879): [PWL] Off : 30s ago
,D/SSRM:m  (  879): SIOP:: AP = 340, PST = 422, CUR = 300
,D/X       (  879): broadcastSiopLevelIntent:: currentSiopLevel = 0
,D/ContentApp( 1224):  LEVEL : 0
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 8396): MountEmulatedStorage()
,E/Zygote  ( 8396): v2
,I/libpersona( 8396): KNOX_SDCARD checking this for 10054
I/libpersona( 8396): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=8396 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,I/SELinux ( 8396): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8396): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8396): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8396): TimaSignature is unavailable
,D/ActivityThread( 8396): Added TimaKeyStore provider
,D/ResourcesManager( 8396): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8396): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8396): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8396): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8396): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8396): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/TranscodeReceiver( 8396): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 8396): core_num = 4
,W/linker  ( 8396): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 8396): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 8396): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
,D/videowall-Global( 8396): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 8396):  SIOP_LEVEL: 0
,I/ActivityManager(  879): Killing 7367:com.sec.esdk.elm/u0a104 (adj 15): bgCount ##41
,W/libprocessgroup(  879): failed to open /acct/uid_10104/pid_7367/cgroup.procs: No such file or directory
,E/SMD     (  284): DCD ON
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  284): DCD ON
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  284): DCD ON
,E/Watchdog(  879): !@Sync 4
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  879): SIOP:: AP = 330, PST = 406, CUR = 300
,D/X       (  879): broadcastSiopLevelIntent:: currentSiopLevel = -1
,D/ContentApp( 1224):  LEVEL : -1
,E/TranscodeReceiver( 8396): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/TranscodeReceiver( 8396):  SIOP_LEVEL: -1
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,V/AlarmManager(  879): waitForAlarm result :4
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  879): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  879): stay LED for fully charged
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  879):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3228): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3228): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6412): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6412): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6412): [1] 5.onFinished: Scheduling replication attempt 4.
E/SMD     (  284): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  284): DCD ON
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  284): DCD ON
,I/PowerManagerService(  879): [PWL] Off : 50s ago
,D/SSRM:m  (  879): SIOP:: AP = 330, PST = 390, CUR = 300
,E/SMD     (  284): DCD ON
,V/AlarmManager(  879): waitForAlarm result :4
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1708): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  879): uri = 14 selection = getSealedState
,D/SecContentProvider2(  879): mCursor = null
D/SecContentProvider2(  879): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,E/HttpOperation( 5296): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5296): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5296): 	at kfv.a(PG:65)
E/HttpOperation( 5296): 	at kff.u(PG:385)
E/HttpOperation( 5296): 	at kfb.a(PG:29)
E/HttpOperation( 5296): 	at kff.l(PG:132)
E/HttpOperation( 5296): 	at dsf.a(PG:807)
E/HttpOperation( 5296): 	at fhk.a(PG:1126)
E/HttpOperation( 5296): 	at fhk.a(PG:908)
E/HttpOperation( 5296): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5296): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5296): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5296): 	at ihi.a(PG:22)
E/HttpOperation( 5296): 	at kft.a(PG:91)
E/HttpOperation( 5296): 	at kfv.a(PG:62)
E/HttpOperation( 5296): 	... 8 more
E/HttpOperation( 5296): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5296): 	at gde.c(Unknown Source)
E/HttpOperation( 5296): 	at gde.b(Unknown Source)
E/HttpOperation( 5296): 	at ihi.a(PG:19)
E/HttpOperation( 5296): 	... 10 more
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  879): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  879): stay LED for fully charged
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  879):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3228): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3228): Disconnected process message: 10
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  879): uri = 14 selection = getSealedState
D/SecContentProvider2(  879): mCursor = null
,D/SecContentProvider2(  879): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 5296): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5296): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5296): 	at kfv.a(PG:65)
E/HttpOperation( 5296): 	at kff.u(PG:385)
E/HttpOperation( 5296): 	at kfb.a(PG:29)
E/HttpOperation( 5296): 	at kff.l(PG:132)
E/HttpOperation( 5296): 	at ieo.a(PG:43)
E/HttpOperation( 5296): 	at iep.a(PG:93)
E/HttpOperation( 5296): 	at fhn.a(PG:59)
E/HttpOperation( 5296): 	at lex.a(PG:85)
E/HttpOperation( 5296): 	at lex.b(PG:132)
E/HttpOperation( 5296): 	at fhk.a(PG:1146)
E/HttpOperation( 5296): 	at fhk.a(PG:908)
E/HttpOperation( 5296): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5296): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5296): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5296): 	at ihi.a(PG:22)
E/HttpOperation( 5296): 	at kft.a(PG:91)
E/HttpOperation( 5296): 	at kfv.a(PG:62)
E/HttpOperation( 5296): 	... 12 more
E/HttpOperation( 5296): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5296): 	at gde.c(Unknown Source)
E/HttpOperation( 5296): 	at gde.b(Unknown Source)
E/HttpOperation( 5296): 	at ihi.a(PG:19)
E/HttpOperation( 5296): 	... 14 more
,E/ExperimentLoader( 5296): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5296): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5296): 	at kfv.a(PG:65)
E/ExperimentLoader( 5296): 	at kff.u(PG:385)
E/ExperimentLoader( 5296): 	at kfb.a(PG:29)
E/ExperimentLoader( 5296): 	at kff.l(PG:132)
E/ExperimentLoader( 5296): 	at ieo.a(PG:43)
E/ExperimentLoader( 5296): 	at iep.a(PG:93)
E/ExperimentLoader( 5296): 	at fhn.a(PG:59)
E/ExperimentLoader( 5296): 	at lex.a(PG:85)
E/ExperimentLoader( 5296): 	at lex.b(PG:132)
E/ExperimentLoader( 5296): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5296): 	at fhk.a(PG:908)
E/ExperimentLoader( 5296): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5296): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5296): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5296): 	at ihi.a(PG:22)
E/ExperimentLoader( 5296): 	at kft.a(PG:91)
E/ExperimentLoader( 5296): 	at kfv.a(PG:62)
E/ExperimentLoader( 5296): 	... 12 more
E/ExperimentLoader( 5296): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5296): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5296): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5296): 	at ihi.a(PG:19)
E/ExperimentLoader( 5296): 	... 14 more
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  879): uri = 14 selection = getSealedState
,D/SecContentProvider2(  879): mCursor = null
D/SecContentProvider2(  879): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 5296): [getaccountstatus] Unexpected exception
E/HttpOperation( 5296): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5296): 	at kfv.a(PG:65)
E/HttpOperation( 5296): 	at kff.u(PG:385)
E/HttpOperation( 5296): 	at kfb.a(PG:29)
E/HttpOperation( 5296): 	at ixd.a(PG:248)
E/HttpOperation( 5296): 	at ixd.b(PG:206)
E/HttpOperation( 5296): 	at ixd.a(PG:175)
E/HttpOperation( 5296): 	at fig.a(PG:78)
E/HttpOperation( 5296): 	at lex.a(PG:85)
E/HttpOperation( 5296): 	at lex.b(PG:132)
E/HttpOperation( 5296): 	at fhk.a(PG:1146)
E/HttpOperation( 5296): 	at fhk.a(PG:908)
E/HttpOperation( 5296): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5296): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5296): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5296): 	at ihi.a(PG:22)
E/HttpOperation( 5296): 	at kft.a(PG:91)
E/HttpOperation( 5296): 	at kfv.a(PG:62)
E/HttpOperation( 5296): 	... 12 more
E/HttpOperation( 5296): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5296): 	at gde.c(Unknown Source)
E/HttpOperation( 5296): 	at gde.b(Unknown Source)
E/HttpOperation( 5296): 	at ihi.a(PG:19)
E/HttpOperation( 5296): 	... 14 more
,E/EsSyncAdapterService( 5296): Sync failure
E/EsSyncAdapterService( 5296): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5296): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5296): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5296): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5296): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5296): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5296): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5296): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5296): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5296): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5296): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5296): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5296): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5296): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5296): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5296): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5296): 	... 10 more
E/EsSyncAdapterService( 5296): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5296): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5296): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5296): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5296): 	... 12 more
E/EsSyncAdapterService( 5296): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5296): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5296): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5296): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5296): 	... 14 more
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,D/SyncManager(  879): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 148978, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  879): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  879): mCursor = null
,E/SQLiteLog( 1708): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  284): DCD ON
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  879): SIOP:: AP = 320, PST = 373, CUR = 300
,E/SMD     (  284): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/AlarmManager(  879): waitForAlarm result :8
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/AlarmManager(  879): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  879): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  879): stay LED for fully charged
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  879):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3228): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3228): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6412): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6412): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6412): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  284): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  284): DCD ON
,E/Watchdog(  879): !@Sync 5
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  879): SIOP:: AP = 320, PST = 359, CUR = 300
,E/SMD     (  284): DCD ON
,I/PowerManagerService(  879): [PWL] Off : 75s ago
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  879): SIOP:: AP = 310, PST = 349, CUR = 300
,E/SMD     (  284): DCD ON
,V/AlarmManager(  879): waitForAlarm result :4
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7528): Starting books sync, d
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1708): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  879): uri = 14 selection = getSealedState
D/SecContentProvider2(  879): mCursor = null
D/SecContentProvider2(  879): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1708): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1708): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1708): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1708): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1708): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1708): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1708): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7528): Authentication error
E/BooksAccountManager( 7528): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7528): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7528): null auth token
,I/qtaguid ( 7528): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7528, getuid(): 10082
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,I/qtaguid ( 7528): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7528, getuid(): 10082
,I/qtaguid ( 7528): Untagging socket 34
,W/ApiaryClient( 7528): Error response from books API: {
W/ApiaryClient( 7528):  "error": {
W/ApiaryClient( 7528):   "errors": [
W/ApiaryClient( 7528):    {
W/ApiaryClient( 7528):     "domain": "global",
W/ApiaryClient( 7528):     "reason": "required",
W/ApiaryClient( 7528):     "message": "Login Required",
W/ApiaryClient( 7528):     "locationType": "header",
W/ApiaryClient( 7528):     "location": "Authorization"
W/ApiaryClient( 7528):    }
W/ApiaryClient( 7528):   ],
W/ApiaryClient( 7528):   "code": 401,
W/ApiaryClient( 7528):   "message": "Login Required"
W/ApiaryClient( 7528):  }
W/ApiaryClient( 7528): }
,W/ApiaryClient( 7528): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7528): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6863357259705130381&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7528): Headers suppressed
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  879): waitForAlarm result :4
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  879): Explicit concurrent mark sweep GC freed 55407(3MB) AllocSpace objects, 33(853KB) LOS objects, 30% free, 36MB/52MB, paused 1.958ms total 146.182ms
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  879): uri = 14 selection = getSealedState
D/SecContentProvider2(  879): mCursor = null
D/SecContentProvider2(  879): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1708): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1708): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1708): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1708): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1708): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1708): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1708): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7528): Authentication error
E/BooksAccountManager( 7528): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7528): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7528): null auth token
,I/qtaguid ( 7528): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7528, getuid(): 10082
I/qtaguid ( 7528): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7528, getuid(): 10082
,I/PhoneStatusBar( 1178): Icon Only
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 7528): Untagging socket 34
W/ApiaryClient( 7528): Error response from books API: {
W/ApiaryClient( 7528):  "error": {
W/ApiaryClient( 7528):   "errors": [
W/ApiaryClient( 7528):    {
W/ApiaryClient( 7528):     "domain": "global",
W/ApiaryClient( 7528):     "reason": "required",
W/ApiaryClient( 7528):     "message": "Login Required",
W/ApiaryClient( 7528):     "locationType": "header",
W/ApiaryClient( 7528):     "location": "Authorization"
W/ApiaryClient( 7528):    }
W/ApiaryClient( 7528):   ],
W/ApiaryClient( 7528):   "code": 401,
W/ApiaryClient( 7528):   "message": "Login Required"
W/ApiaryClient( 7528):  }
W/ApiaryClient( 7528): }
,W/ApiaryClient( 7528): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7528): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6863357259705130381&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7528): Headers suppressed
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1708): Vacuum at: now=1453032862814 tag=VacuumService
,I/GoogleURLConnFactory( 1708): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  879): uri = 14 selection = getSealedState
D/SecContentProvider2(  879): mCursor = null
,D/SecContentProvider2(  879): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
E/Uploader( 1708): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1708): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1708): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1708): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1708): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1708): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1708): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1708): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1708): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1708): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1708): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1708): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1708): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/System.out( 1708): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1708): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1708): (HTTPLog)-Thread-209-1010481681: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1708): Tagging socket 60 with tag 120100000000{4609,0} uid -1, pid: 1708, getuid(): 10012
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 1708): Tagging socket 64 with tag 120100000000{4609,0} uid -1, pid: 1708, getuid(): 10012
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6412): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6412): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6412): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1708): No account for auth token provided
,I/qtaguid ( 1708): Tagging socket 60 with tag 120100000000{4609,0} uid -1, pid: 1708, getuid(): 10012
,W/Uploader( 1708): No account for auth token provided
,I/qtaguid ( 1708): Tagging socket 60 with tag 120100000000{4609,0} uid -1, pid: 1708, getuid(): 10012
,W/Uploader( 1708): No account for auth token provided
,I/qtaguid ( 1708): Tagging socket 60 with tag 120100000000{4609,0} uid -1, pid: 1708, getuid(): 10012
,E/SMD     (  284): DCD ON
,W/Uploader( 1708): No account for auth token provided
,I/qtaguid ( 1708): Tagging socket 60 with tag 120100000000{4609,0} uid -1, pid: 1708, getuid(): 10012
,W/Uploader( 1708):  no longer exists, so no auth token.
,I/qtaguid ( 1708): Tagging socket 60 with tag 120100000000{4609,0} uid -1, pid: 1708, getuid(): 10012
,E/SQLiteLog( 1708): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1708): Explicit concurrent mark sweep GC freed 44296(2MB) AllocSpace objects, 50(3MB) LOS objects, 40% free, 18MB/30MB, paused 665us total 79.583ms
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1708): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  879): uri = 14 selection = getSealedState
,D/SecContentProvider2(  879): mCursor = null
D/SecContentProvider2(  879): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1708): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1708): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1708): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1708): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1708): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1708): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1708): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7528): Authentication error
E/BooksAccountManager( 7528): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7528): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7528): null auth token
,I/qtaguid ( 7528): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7528, getuid(): 10082
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,I/qtaguid ( 7528): Untagging socket 34
,W/ApiaryClient( 7528): Error response from books API: {
W/ApiaryClient( 7528):  "error": {
W/ApiaryClient( 7528):   "errors": [
W/ApiaryClient( 7528):    {
W/ApiaryClient( 7528):     "domain": "global",
W/ApiaryClient( 7528):     "reason": "required",
W/ApiaryClient( 7528):     "message": "Login Required",
W/ApiaryClient( 7528):     "locationType": "header",
W/ApiaryClient( 7528):     "location": "Authorization"
W/ApiaryClient( 7528):    }
W/ApiaryClient( 7528):   ],
W/ApiaryClient( 7528):   "code": 401,
W/ApiaryClient( 7528):   "message": "Login Required"
W/ApiaryClient( 7528):  }
W/ApiaryClient( 7528): }
,W/ApiaryClient( 7528): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7528): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6863357259705130381&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7528): Headers suppressed
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/BooksSync( 7528): Soft error
E/BooksSync( 7528): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7528): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6863357259705130381&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7528): Headers suppressed
E/BooksSync( 7528): 
E/BooksSync( 7528): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7528): Sync error
E/BooksSync( 7528): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7528): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6863357259705130381&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7528): Headers suppressed
E/BooksSync( 7528): 
E/BooksSync( 7528): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7528): Finished books sync
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  879): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 155641, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  879): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  879): mCursor = null
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1708): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  879): uri = 14 selection = getSealedState
,D/SecContentProvider2(  879): mCursor = null
D/SecContentProvider2(  879): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 5296): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5296): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5296): 	at kfv.a(PG:65)
E/HttpOperation( 5296): 	at kff.u(PG:385)
E/HttpOperation( 5296): 	at kfb.a(PG:29)
E/HttpOperation( 5296): 	at kff.l(PG:132)
E/HttpOperation( 5296): 	at dsf.a(PG:807)
E/HttpOperation( 5296): 	at fhk.a(PG:1126)
E/HttpOperation( 5296): 	at fhk.a(PG:908)
E/HttpOperation( 5296): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5296): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5296): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5296): 	at ihi.a(PG:22)
E/HttpOperation( 5296): 	at kft.a(PG:91)
E/HttpOperation( 5296): 	at kfv.a(PG:62)
E/HttpOperation( 5296): 	... 8 more
E/HttpOperation( 5296): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5296): 	at gde.c(Unknown Source)
E/HttpOperation( 5296): 	at gde.b(Unknown Source)
E/HttpOperation( 5296): 	at ihi.a(PG:19)
E/HttpOperation( 5296): 	... 10 more
,I/PhoneStatusBar( 1178): Icon Only
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  879): uri = 14 selection = getSealedState
,D/SecContentProvider2(  879): mCursor = null
D/SecContentProvider2(  879): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 5296): [getaccountstatus] Unexpected exception
E/HttpOperation( 5296): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5296): 	at kfv.a(PG:65)
E/HttpOperation( 5296): 	at kff.u(PG:385)
E/HttpOperation( 5296): 	at kfb.a(PG:29)
E/HttpOperation( 5296): 	at ixd.a(PG:248)
E/HttpOperation( 5296): 	at ixd.b(PG:206)
E/HttpOperation( 5296): 	at ixd.a(PG:175)
E/HttpOperation( 5296): 	at fig.a(PG:78)
E/HttpOperation( 5296): 	at lex.a(PG:85)
E/HttpOperation( 5296): 	at lex.b(PG:132)
E/HttpOperation( 5296): 	at fhk.a(PG:1146)
E/HttpOperation( 5296): 	at fhk.a(PG:908)
E/HttpOperation( 5296): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5296): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5296): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5296): 	at ihi.a(PG:22)
E/HttpOperation( 5296): 	at kft.a(PG:91)
E/HttpOperation( 5296): 	at kfv.a(PG:62)
E/HttpOperation( 5296): 	... 12 more
E/HttpOperation( 5296): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5296): 	at gde.c(Unknown Source)
E/HttpOperation( 5296): 	at gde.b(Unknown Source)
E/HttpOperation( 5296): 	at ihi.a(PG:19)
E/HttpOperation( 5296): 	... 14 more
,E/EsSyncAdapterService( 5296): Sync failure
E/EsSyncAdapterService( 5296): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5296): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5296): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5296): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5296): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5296): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5296): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5296): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5296): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5296): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5296): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5296): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5296): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5296): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5296): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5296): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5296): 	... 10 more
E/EsSyncAdapterService( 5296): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5296): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5296): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5296): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5296): 	... 12 more
E/EsSyncAdapterService( 5296): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5296): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5296): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5296): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5296): 	... 14 more
I/PhoneStatusBar( 1178): Icon Only
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
I/ServiceManager(  322): Waiting for service AtCmdFwd...
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  879): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  879): mCursor = null
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  879): uri = 14 selection = getSealedState
,D/SecContentProvider2(  879): mCursor = null
D/SecContentProvider2(  879): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,E/HttpOperation( 5296): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5296): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5296): 	at kfv.a(PG:65)
E/HttpOperation( 5296): 	at kff.u(PG:385)
E/HttpOperation( 5296): 	at kfb.a(PG:29)
E/HttpOperation( 5296): 	at kff.l(PG:132)
E/HttpOperation( 5296): 	at dsf.a(PG:807)
E/HttpOperation( 5296): 	at fhk.a(PG:1126)
E/HttpOperation( 5296): 	at fhk.a(PG:908)
E/HttpOperation( 5296): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5296): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5296): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5296): 	at ihi.a(PG:22)
E/HttpOperation( 5296): 	at kft.a(PG:91)
E/HttpOperation( 5296): 	at kfv.a(PG:62)
E/HttpOperation( 5296): 	... 8 more
E/HttpOperation( 5296): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5296): 	at gde.c(Unknown Source)
E/HttpOperation( 5296): 	at gde.b(Unknown Source)
E/HttpOperation( 5296): 	at ihi.a(PG:19)
E/HttpOperation( 5296): 	... 10 more
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  879): uri = 14 selection = getSealedState
,D/SecContentProvider2(  879): mCursor = null
D/SecContentProvider2(  879): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
E/HttpOperation( 5296): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5296): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5296): 	at kfv.a(PG:65)
E/HttpOperation( 5296): 	at kff.u(PG:385)
E/HttpOperation( 5296): 	at kfb.a(PG:29)
E/HttpOperation( 5296): 	at kff.l(PG:132)
E/HttpOperation( 5296): 	at ieo.a(PG:43)
E/HttpOperation( 5296): 	at iep.a(PG:93)
E/HttpOperation( 5296): 	at fhn.a(PG:59)
E/HttpOperation( 5296): 	at lex.a(PG:85)
E/HttpOperation( 5296): 	at lex.b(PG:132)
E/HttpOperation( 5296): 	at fhk.a(PG:1146)
E/HttpOperation( 5296): 	at fhk.a(PG:908)
E/HttpOperation( 5296): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5296): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5296): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5296): 	at ihi.a(PG:22)
E/HttpOperation( 5296): 	at kft.a(PG:91)
E/HttpOperation( 5296): 	at kfv.a(PG:62)
E/HttpOperation( 5296): 	... 12 more
E/HttpOperation( 5296): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5296): 	at gde.c(Unknown Source)
E/HttpOperation( 5296): 	at gde.b(Unknown Source)
E/HttpOperation( 5296): 	at ihi.a(PG:19)
E/HttpOperation( 5296): 	... 14 more
,E/ExperimentLoader( 5296): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5296): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5296): 	at kfv.a(PG:65)
E/ExperimentLoader( 5296): 	at kff.u(PG:385)
E/ExperimentLoader( 5296): 	at kfb.a(PG:29)
E/ExperimentLoader( 5296): 	at kff.l(PG:132)
E/ExperimentLoader( 5296): 	at ieo.a(PG:43)
E/ExperimentLoader( 5296): 	at iep.a(PG:93)
E/ExperimentLoader( 5296): 	at fhn.a(PG:59)
E/ExperimentLoader( 5296): 	at lex.a(PG:85)
E/ExperimentLoader( 5296): 	at lex.b(PG:132)
E/ExperimentLoader( 5296): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5296): 	at fhk.a(PG:908)
E/ExperimentLoader( 5296): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5296): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5296): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5296): 	at ihi.a(PG:22)
E/ExperimentLoader( 5296): 	at kft.a(PG:91)
E/ExperimentLoader( 5296): 	at kfv.a(PG:62)
E/ExperimentLoader( 5296): 	... 12 more
E/ExperimentLoader( 5296): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5296): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5296): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5296): 	at ihi.a(PG:19)
E/ExperimentLoader( 5296): 	... 14 more
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  879): uri = 14 selection = getSealedState
,D/SecContentProvider2(  879): mCursor = null
,D/SecContentProvider2(  879): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 5296): [getaccountstatus] Unexpected exception
E/HttpOperation( 5296): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5296): 	at kfv.a(PG:65)
E/HttpOperation( 5296): 	at kff.u(PG:385)
E/HttpOperation( 5296): 	at kfb.a(PG:29)
E/HttpOperation( 5296): 	at ixd.a(PG:248)
E/HttpOperation( 5296): 	at ixd.b(PG:206)
E/HttpOperation( 5296): 	at ixd.a(PG:175)
E/HttpOperation( 5296): 	at fig.a(PG:78)
E/HttpOperation( 5296): 	at lex.a(PG:85)
E/HttpOperation( 5296): 	at lex.b(PG:132)
E/HttpOperation( 5296): 	at fhk.a(PG:1146)
E/HttpOperation( 5296): 	at fhk.a(PG:908)
E/HttpOperation( 5296): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5296): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5296): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5296): 	at ihi.a(PG:22)
E/HttpOperation( 5296): 	at kft.a(PG:91)
E/HttpOperation( 5296): 	at kfv.a(PG:62)
E/HttpOperation( 5296): 	... 12 more
E/HttpOperation( 5296): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5296): 	at gde.c(Unknown Source)
E/HttpOperation( 5296): 	at gde.b(Unknown Source)
E/HttpOperation( 5296): 	at ihi.a(PG:19)
E/HttpOperation( 5296): 	... 14 more
,E/EsSyncAdapterService( 5296): Sync failure
E/EsSyncAdapterService( 5296): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5296): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5296): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5296): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5296): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5296): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5296): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5296): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5296): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5296): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5296): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5296): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5296): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5296): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5296): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5296): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5296): 	... 10 more
E/EsSyncAdapterService( 5296): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5296): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5296): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5296): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5296): 	... 12 more
E/EsSyncAdapterService( 5296): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5296): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5296): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5296): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5296): 	... 14 more
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,D/SyncManager(  879): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 149528, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  879): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  879): mCursor = null
,E/SMD     (  284): DCD ON
,E/SQLiteLog( 1708): (10) POSIX Error : 11 SQLite Error : 3850
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  879): SIOP:: AP = 310, PST = 341, CUR = 300
,E/SMD     (  284): DCD ON
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  879): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  879):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3228): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3228): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  284): DCD ON,
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  284): DCD ON
,E/Watchdog(  879): !@Sync 6
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  879): SIOP:: AP = 310, PST = 336, CUR = 300
,E/SMD     (  284): DCD ON
,I/PowerManagerService(  879): [PWL] Off : 105s ago
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  879): SIOP:: AP = 310, PST = 326, CUR = 300
,E/SMD     (  284): DCD ON
,V/AlarmManager(  879): waitForAlarm result :4
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  284): DCD ON
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  879): SIOP:: AP = 300, PST = 318, CUR = 300
,E/SMD     (  284): DCD ON
,V/AlarmManager(  879): waitForAlarm result :8
,E/SMD     (  284): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  284): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/Watchdog(  879): !@Sync 7
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  284): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  879): SIOP:: AP = 300, PST = 314, CUR = 300
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  284): DCD ON
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  284): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  284): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/PowerManagerService(  879): [PWL] Off : 140s ago
,D/SSRM:m  (  879): SIOP:: AP = 300, PST = 311, CUR = 300
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  284): DCD ON
,V/AlarmManager(  879): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  879): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  879): stay LED for fully charged
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/MotionRecognitionService(  879):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3228): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3228): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7528): Starting books sync, d
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  879): uri = 14 selection = getSealedState
D/SecContentProvider2(  879): mCursor = null
,D/SecContentProvider2(  879): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1708): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1708): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1708): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1708): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1708): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1708): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1708): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7528): Authentication error
E/BooksAccountManager( 7528): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7528): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7528): null auth token
,I/PhoneStatusBar( 1178): Icon Only
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,I/qtaguid ( 7528): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7528, getuid(): 10082
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  879): uri = 14 selection = getSealedState
,D/SecContentProvider2(  879): mCursor = null
D/SecContentProvider2(  879): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
E/HttpOperation( 5296): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5296): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5296): 	at kfv.a(PG:65)
E/HttpOperation( 5296): 	at kff.u(PG:385)
E/HttpOperation( 5296): 	at kfb.a(PG:29)
E/HttpOperation( 5296): 	at kff.l(PG:132)
E/HttpOperation( 5296): 	at dsf.a(PG:807)
E/HttpOperation( 5296): 	at fhk.a(PG:1126)
E/HttpOperation( 5296): 	at fhk.a(PG:908)
E/HttpOperation( 5296): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5296): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5296): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5296): 	at ihi.a(PG:22)
E/HttpOperation( 5296): 	at kft.a(PG:91)
E/HttpOperation( 5296): 	at kfv.a(PG:62)
E/HttpOperation( 5296): 	... 8 more
E/HttpOperation( 5296): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5296): 	at gde.c(Unknown Source)
E/HttpOperation( 5296): 	at gde.b(Unknown Source)
E/HttpOperation( 5296): 	at ihi.a(PG:19)
E/HttpOperation( 5296): 	... 10 more
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,I/qtaguid ( 7528): Untagging socket 34
,W/ApiaryClient( 7528): Error response from books API: {
W/ApiaryClient( 7528):  "error": {
W/ApiaryClient( 7528):   "errors": [
W/ApiaryClient( 7528):    {
W/ApiaryClient( 7528):     "domain": "global",
W/ApiaryClient( 7528):     "reason": "required",
W/ApiaryClient( 7528):     "message": "Login Required",
W/ApiaryClient( 7528):     "locationType": "header",
W/ApiaryClient( 7528):     "location": "Authorization"
W/ApiaryClient( 7528):    }
W/ApiaryClient( 7528):   ],
W/ApiaryClient( 7528):   "code": 401,
W/ApiaryClient( 7528):   "message": "Login Required"
W/ApiaryClient( 7528):  }
W/ApiaryClient( 7528): }
,W/ApiaryClient( 7528): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7528): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-660004796307942886&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7528): Headers suppressed
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  879): uri = 14 selection = getSealedState
D/SecContentProvider2(  879): mCursor = null
,D/SecContentProvider2(  879): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,E/HttpOperation( 5296): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5296): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5296): 	at kfv.a(PG:65)
E/HttpOperation( 5296): 	at kff.u(PG:385)
E/HttpOperation( 5296): 	at kfb.a(PG:29)
E/HttpOperation( 5296): 	at kff.l(PG:132)
E/HttpOperation( 5296): 	at ieo.a(PG:43)
E/HttpOperation( 5296): 	at iep.a(PG:93)
E/HttpOperation( 5296): 	at fhn.a(PG:59)
E/HttpOperation( 5296): 	at lex.a(PG:85)
E/HttpOperation( 5296): 	at lex.b(PG:132)
E/HttpOperation( 5296): 	at fhk.a(PG:1146)
E/HttpOperation( 5296): 	at fhk.a(PG:908)
E/HttpOperation( 5296): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5296): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5296): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5296): 	at ihi.a(PG:22)
E/HttpOperation( 5296): 	at kft.a(PG:91)
E/HttpOperation( 5296): 	at kfv.a(PG:62)
E/HttpOperation( 5296): 	... 12 more
E/HttpOperation( 5296): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5296): 	at gde.c(Unknown Source)
E/HttpOperation( 5296): 	at gde.b(Unknown Source)
E/HttpOperation( 5296): 	at ihi.a(PG:19)
E/HttpOperation( 5296): 	... 14 more
,E/ExperimentLoader( 5296): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5296): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5296): 	at kfv.a(PG:65)
E/ExperimentLoader( 5296): 	at kff.u(PG:385)
E/ExperimentLoader( 5296): 	at kfb.a(PG:29)
E/ExperimentLoader( 5296): 	at kff.l(PG:132)
E/ExperimentLoader( 5296): 	at ieo.a(PG:43)
E/ExperimentLoader( 5296): 	at iep.a(PG:93)
E/ExperimentLoader( 5296): 	at fhn.a(PG:59)
E/ExperimentLoader( 5296): 	at lex.a(PG:85)
E/ExperimentLoader( 5296): 	at lex.b(PG:132)
E/ExperimentLoader( 5296): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5296): 	at fhk.a(PG:908)
E/ExperimentLoader( 5296): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5296): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5296): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5296): 	at ihi.a(PG:22)
E/ExperimentLoader( 5296): 	at kft.a(PG:91)
E/ExperimentLoader( 5296): 	at kfv.a(PG:62)
E/ExperimentLoader( 5296): 	... 12 more
E/ExperimentLoader( 5296): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5296): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5296): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5296): 	at ihi.a(PG:19)
E/ExperimentLoader( 5296): 	... 14 more
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,E/SQLiteLog( 1708): (10) POSIX Error : 11 SQLite Error : 3850
,D/SecContentProvider2(  879): uri = 14 selection = getSealedState
D/SecContentProvider2(  879): mCursor = null
,D/SecContentProvider2(  879): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,E/HttpOperation( 5296): [getaccountstatus] Unexpected exception
E/HttpOperation( 5296): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5296): 	at kfv.a(PG:65)
E/HttpOperation( 5296): 	at kff.u(PG:385)
E/HttpOperation( 5296): 	at kfb.a(PG:29)
E/HttpOperation( 5296): 	at ixd.a(PG:248)
E/HttpOperation( 5296): 	at ixd.b(PG:206)
E/HttpOperation( 5296): 	at ixd.a(PG:175)
E/HttpOperation( 5296): 	at fig.a(PG:78)
E/HttpOperation( 5296): 	at lex.a(PG:85)
E/HttpOperation( 5296): 	at lex.b(PG:132)
E/HttpOperation( 5296): 	at fhk.a(PG:1146)
E/HttpOperation( 5296): 	at fhk.a(PG:908)
E/HttpOperation( 5296): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5296): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5296): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5296): 	at ihi.a(PG:22)
E/HttpOperation( 5296): 	at kft.a(PG:91)
E/HttpOperation( 5296): 	at kfv.a(PG:62)
E/HttpOperation( 5296): 	... 12 more
E/HttpOperation( 5296): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5296): 	at gde.c(Unknown Source)
E/HttpOperation( 5296): 	at gde.b(Unknown Source)
E/HttpOperation( 5296): 	at ihi.a(PG:19)
E/HttpOperation( 5296): 	... 14 more
,E/EsSyncAdapterService( 5296): Sync failure
E/EsSyncAdapterService( 5296): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5296): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5296): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5296): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5296): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5296): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5296): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5296): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5296): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5296): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5296): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5296): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5296): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5296): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5296): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5296): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5296): 	... 10 more
E/EsSyncAdapterService( 5296): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5296): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5296): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5296): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5296): 	... 12 more
E/EsSyncAdapterService( 5296): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5296): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5296): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5296): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5296): 	... 14 more
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  879): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 216598, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  879): Explicit concurrent mark sweep GC freed 53472(2MB) AllocSpace objects, 34(1324KB) LOS objects, 30% free, 36MB/52MB, paused 1.565ms total 121.006ms
,D/SecContentProvider2(  879): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  879): mCursor = null
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 1708): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  879): uri = 14 selection = getSealedState
,D/SecContentProvider2(  879): mCursor = null
,D/SecContentProvider2(  879): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,W/GLSActivity( 1708): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1708): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1708): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1708): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1708): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1708): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1708): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7528): Authentication error
E/BooksAccountManager( 7528): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7528): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7528): null auth token
,I/qtaguid ( 7528): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7528, getuid(): 10082
,I/qtaguid ( 7528): Untagging socket 34
,W/ApiaryClient( 7528): Error response from books API: {
W/ApiaryClient( 7528):  "error": {
W/ApiaryClient( 7528):   "errors": [
W/ApiaryClient( 7528):    {
W/ApiaryClient( 7528):     "domain": "global",
W/ApiaryClient( 7528):     "reason": "required",
W/ApiaryClient( 7528):     "message": "Login Required",
W/ApiaryClient( 7528):     "locationType": "header",
W/ApiaryClient( 7528):     "location": "Authorization"
W/ApiaryClient( 7528):    }
W/ApiaryClient( 7528):   ],
W/ApiaryClient( 7528):   "code": 401,
W/ApiaryClient( 7528):   "message": "Login Required"
W/ApiaryClient( 7528):  }
W/ApiaryClient( 7528): }
,W/ApiaryClient( 7528): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7528): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-660004796307942886&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7528): Headers suppressed
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  284): DCD ON
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  879): uri = 14 selection = getSealedState
,D/SecContentProvider2(  879): mCursor = null
D/SecContentProvider2(  879): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,W/GLSActivity( 1708): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1708): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1708): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1708): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1708): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1708): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1708): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7528): Authentication error
E/BooksAccountManager( 7528): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7528): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7528): null auth token
,I/qtaguid ( 7528): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7528, getuid(): 10082
,I/qtaguid ( 7528): Untagging socket 34
,W/ApiaryClient( 7528): Error response from books API: {
W/ApiaryClient( 7528):  "error": {
W/ApiaryClient( 7528):   "errors": [
W/ApiaryClient( 7528):    {
W/ApiaryClient( 7528):     "domain": "global",
W/ApiaryClient( 7528):     "reason": "required",
W/ApiaryClient( 7528):     "message": "Login Required",
W/ApiaryClient( 7528):     "locationType": "header",
W/ApiaryClient( 7528):     "location": "Authorization"
W/ApiaryClient( 7528):    }
W/ApiaryClient( 7528):   ],
W/ApiaryClient( 7528):   "code": 401,
W/ApiaryClient( 7528):   "message": "Login Required"
W/ApiaryClient( 7528):  }
W/ApiaryClient( 7528): }
,W/ApiaryClient( 7528): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7528): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-660004796307942886&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7528): Headers suppressed
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7528): Soft error
E/BooksSync( 7528): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7528): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-660004796307942886&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7528): Headers suppressed
E/BooksSync( 7528): 
E/BooksSync( 7528): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7528): Sync error
E/BooksSync( 7528): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7528): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-660004796307942886&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7528): Headers suppressed
E/BooksSync( 7528): 
E/BooksSync( 7528): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7528): Finished books sync
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  879): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 215639, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2853): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 2853): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  879): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  879): mCursor = null
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  879): SIOP:: AP = 300, PST = 308, CUR = 300
,E/SMD     (  284): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  879): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  879):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
,D/BatteryService(  879): stay LED for fully charged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3228): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3228): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  284): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  284): DCD ON
,E/Watchdog(  879): !@Sync 8
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  879): SIOP:: AP = 300, PST = 306, CUR = 300
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  879): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  879):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3228): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3228): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  879): SIOP:: AP = 300, PST = 304, CUR = 300
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  284): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/AlarmManager(  879): waitForAlarm result :4
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  879): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  879): stay LED for fully charged
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  879):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3228): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3228): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  284): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  284): DCD ON
,I/PowerManagerService(  879): [PWL] Off : 180s ago
,D/SSRM:m  (  879): SIOP:: AP = 300, PST = 303, CUR = 300
,E/SMD     (  284): DCD ON
,V/AlarmManager(  879): waitForAlarm result :8
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,E/Watchdog(  879): !@Sync 9
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  879): SIOP:: AP = 300, PST = 302, CUR = 300
,E/SMD     (  284): DCD ON
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  284): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  284): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  879): SIOP:: AP = 300, PST = 301, CUR = 300
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,V/AlarmManager(  879): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  879): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  879): stay LED for fully charged
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/MotionRecognitionService(  879):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,V/HeadsetService( 3228): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3228): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  879): uri = 14 selection = getSealedState
D/SecContentProvider2(  879): mCursor = null
,D/SecContentProvider2(  879): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 5296): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5296): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5296): 	at kfv.a(PG:65)
E/HttpOperation( 5296): 	at kff.u(PG:385)
E/HttpOperation( 5296): 	at kfb.a(PG:29)
E/HttpOperation( 5296): 	at kff.l(PG:132)
E/HttpOperation( 5296): 	at dsf.a(PG:807)
E/HttpOperation( 5296): 	at fhk.a(PG:1126)
E/HttpOperation( 5296): 	at fhk.a(PG:908)
E/HttpOperation( 5296): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5296): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5296): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5296): 	at ihi.a(PG:22)
E/HttpOperation( 5296): 	at kft.a(PG:91)
E/HttpOperation( 5296): 	at kfv.a(PG:62)
E/HttpOperation( 5296): 	... 8 more
E/HttpOperation( 5296): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5296): 	at gde.c(Unknown Source)
E/HttpOperation( 5296): 	at gde.b(Unknown Source)
E/HttpOperation( 5296): 	at ihi.a(PG:19)
E/HttpOperation( 5296): 	... 10 more
,I/PhoneStatusBar( 1178): Icon Only
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  879): uri = 14 selection = getSealedState
,D/SecContentProvider2(  879): mCursor = null
D/SecContentProvider2(  879): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,E/HttpOperation( 5296): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5296): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5296): 	at kfv.a(PG:65)
E/HttpOperation( 5296): 	at kff.u(PG:385)
E/HttpOperation( 5296): 	at kfb.a(PG:29)
E/HttpOperation( 5296): 	at kff.l(PG:132)
E/HttpOperation( 5296): 	at ieo.a(PG:43)
E/HttpOperation( 5296): 	at iep.a(PG:93)
E/HttpOperation( 5296): 	at fhn.a(PG:59)
E/HttpOperation( 5296): 	at lex.a(PG:85)
E/HttpOperation( 5296): 	at lex.b(PG:132)
E/HttpOperation( 5296): 	at fhk.a(PG:1146)
E/HttpOperation( 5296): 	at fhk.a(PG:908)
E/HttpOperation( 5296): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5296): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5296): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5296): 	at ihi.a(PG:22)
E/HttpOperation( 5296): 	at kft.a(PG:91)
E/HttpOperation( 5296): 	at kfv.a(PG:62)
E/HttpOperation( 5296): 	... 12 more
E/HttpOperation( 5296): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5296): 	at gde.c(Unknown Source)
E/HttpOperation( 5296): 	at gde.b(Unknown Source)
E/HttpOperation( 5296): 	at ihi.a(PG:19)
E/HttpOperation( 5296): 	... 14 more
,E/ExperimentLoader( 5296): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5296): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5296): 	at kfv.a(PG:65)
E/ExperimentLoader( 5296): 	at kff.u(PG:385)
E/ExperimentLoader( 5296): 	at kfb.a(PG:29)
E/ExperimentLoader( 5296): 	at kff.l(PG:132)
E/ExperimentLoader( 5296): 	at ieo.a(PG:43)
E/ExperimentLoader( 5296): 	at iep.a(PG:93)
E/ExperimentLoader( 5296): 	at fhn.a(PG:59)
E/ExperimentLoader( 5296): 	at lex.a(PG:85)
E/ExperimentLoader( 5296): 	at lex.b(PG:132)
E/ExperimentLoader( 5296): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5296): 	at fhk.a(PG:908)
E/ExperimentLoader( 5296): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5296): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5296): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5296): 	at ihi.a(PG:22)
E/ExperimentLoader( 5296): 	at kft.a(PG:91)
E/ExperimentLoader( 5296): 	at kfv.a(PG:62)
E/ExperimentLoader( 5296): 	... 12 more
E/ExperimentLoader( 5296): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5296): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5296): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5296): 	at ihi.a(PG:19)
E/ExperimentLoader( 5296): 	... 14 more
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1708): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  879): uri = 14 selection = getSealedState
,D/SecContentProvider2(  879): mCursor = null
D/SecContentProvider2(  879): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,E/SQLiteLog( 1708): (10) POSIX Error : 11 SQLite Error : 3850
,D/PanelView( 1178): There is/are notification(s) 
,E/HttpOperation( 5296): [getaccountstatus] Unexpected exception
E/HttpOperation( 5296): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5296): 	at kfv.a(PG:65)
E/HttpOperation( 5296): 	at kff.u(PG:385)
E/HttpOperation( 5296): 	at kfb.a(PG:29)
E/HttpOperation( 5296): 	at ixd.a(PG:248)
E/HttpOperation( 5296): 	at ixd.b(PG:206)
E/HttpOperation( 5296): 	at ixd.a(PG:175)
E/HttpOperation( 5296): 	at fig.a(PG:78)
E/HttpOperation( 5296): 	at lex.a(PG:85)
E/HttpOperation( 5296): 	at lex.b(PG:132)
E/HttpOperation( 5296): 	at fhk.a(PG:1146)
E/HttpOperation( 5296): 	at fhk.a(PG:908)
E/HttpOperation( 5296): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5296): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5296): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5296): 	at ihi.a(PG:22)
E/HttpOperation( 5296): 	at kft.a(PG:91)
E/HttpOperation( 5296): 	at kfv.a(PG:62)
E/HttpOperation( 5296): 	... 12 more
E/HttpOperation( 5296): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5296): 	at gde.c(Unknown Source)
E/HttpOperation( 5296): 	at gde.b(Unknown Source)
E/HttpOperation( 5296): 	at ihi.a(PG:19)
E/HttpOperation( 5296): 	... 14 more
,E/EsSyncAdapterService( 5296): Sync failure
E/EsSyncAdapterService( 5296): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5296): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5296): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5296): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5296): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5296): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5296): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5296): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5296): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5296): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5296): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5296): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5296): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5296): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5296): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5296): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5296): 	... 10 more
E/EsSyncAdapterService( 5296): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5296): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5296): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5296): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5296): 	... 12 more
E/EsSyncAdapterService( 5296): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5296): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5296): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5296): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5296): 	... 14 more
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1708): Explicit concurrent mark sweep GC freed 41606(2MB) AllocSpace objects, 32(2MB) LOS objects, 40% free, 18MB/30MB, paused 1.752ms total 42.727ms
,D/SyncManager(  879): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 305103, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2853): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 2853): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  879): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  879): mCursor = null
,E/SQLiteLog( 1708): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  879): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  284): DCD ON
,D/TimaService(  879): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  879): TimaServiceHandler.handleMessage what =1
,D/TimaService(  879): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  879): initializing...
,I/TLC_TIMA_PKM_initialize(  879): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  879): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  879): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  879): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  879): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  879): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  879): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: (  879): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  879): App is not loaded in QSEE
,D/QSEECOMAPI: (  879): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  879): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  879): Trustlet response is completed
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  284): DCD ON
,E/Watchdog(  879): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  879): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  879): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  879): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  879): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/jxcore-log( 7648): --= Surplus to requirements =--
I/jxcore-log( 7648): 
,I/jxcore-log( 7648): ****TEST TOOK:  ms ****
I/jxcore-log( 7648): 
I/jxcore-log( 7648): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7648): 
,D/AndroidRuntime( 8684): 
D/AndroidRuntime( 8684): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8684): CheckJNI is OFF
,D/AndroidRuntime( 8684): setted country_code = Germany
D/AndroidRuntime( 8684): setted countryiso_code = DE
,D/AndroidRuntime( 8684): setted sales_code = DBT
D/AndroidRuntime( 8684): readGMSProperty: start
D/AndroidRuntime( 8684): readGMSProperty: already setted!!
D/AndroidRuntime( 8684): readGMSProperty: end
D/AndroidRuntime( 8684): addProductProperty: start
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  879): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  879): stay LED for fully charged
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  879):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3228): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3228): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/AffinityControl( 8684): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8684): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  879): START PACKAGE DELETE: observer{942505276}
D/PackageManager(  879): pkg{<packageName>}
D/PackageManager(  879): user{0}
D/PackageManager(  879): caller{2000}
D/PackageManager(  879): flags{3}
D/PersonaManagerService(  879): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  879): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  879): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  879): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  879): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  879): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  879): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  879): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  879): getApplicationUninstallationEnabled
D/ApplicationPolicy(  879): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  879): !@killApplicatoin: 10200, uninstall pkg
,I/ActivityManager(  879): Force stopping com.test.thalitest appid=10200 user=-1: uninstall pkg
,I/ActivityManager(  879): Killing 7648:com.test.thalitest/u0a200 (adj 0): stop com.test.thalitest
,I/ActivityManager(  879):   Force finishing activity ActivityRecord{19dc895c u0 com.test.thalitest/.MainActivity t17}
,D/FocusedStackFrame(  879): Set to : 0
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,I/SurfaceFlinger(  250): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (6/8)
,I/SurfaceFlinger(  250): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/WifiService(  879): Client connection lost with reason: 4
,I/ActivityManager(  879): Force stopping com.test.thalitest appid=10200 user=0: pkg removed
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1575): Explicit concurrent mark sweep GC freed 16904(1134KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/27MB, paused 414us total 27.170ms
,I/art     ( 4552): Explicit concurrent mark sweep GC freed 5023(278KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 596us total 63.517ms
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/InputReader(  879): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 2156): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 1858): mOCRHelper is null
,I/KLMS-2.4.503: ( 7300): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7300): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1453032997413
,I/KLMS-2.4.503: ( 7300): MainReciver(): PACKAGE_REMOVED
,I/art     (  879): Explicit concurrent mark sweep GC freed 36705(2MB) AllocSpace objects, 32(837KB) LOS objects, 30% free, 36MB/52MB, paused 2.500ms total 130.733ms
,I/KLMS-2.4.503: ( 7300): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  879): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     (  879): WaitForGcToComplete blocked for 44.455ms for cause Explicit
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/SecContentProvider2(  879): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  879): mCursor = null
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/RegisteredServicesCache( 1477): empty dynamic service
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,E/Zygote  ( 8715): MountEmulatedStorage()
E/Zygote  ( 8715): v2
I/libpersona( 8715): KNOX_SDCARD checking this for 10104
I/libpersona( 8715): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8715 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/talkback/talkback.apk
,I/SELinux ( 8715): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8715): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8715): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/RCPManagerService(  879): PackageReceiver onReceive()
,I/HarmonyEASService(  879): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  879): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  879): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/EnterpriseDeviceManagerService(  879): Package has changed for user 0
D/EnterpriseDeviceManagerService(  879): Admin package name: com.google.android.gms
,D/JobSchedulerService(  879): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  879): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  879): uID is 10200
V/EnterpriseBillingPolicy(  879): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  879): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  879): getProfileForApplication - exit null
,V/EnterpriseBillingPolicy(  879): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  879): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  879): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage(  879): getBillingProfileForVpnEngine - end - null
,D/TimaKeyStoreProvider( 8715): TimaSignature is unavailable
,D/ActivityThread( 8715): Added TimaKeyStore provider
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/TaskPersister(  879): removeObsoleteFile: deleting file=17_task.xml
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 8715): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/SurfaceWidgetView( 1492): destroyHardwareResources():538053983
,V/WindowOrientationListener(  879): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  879): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  879): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  879): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  879): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/Launcher( 1492): onRestart, Launcher: 976102361
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Launcher( 1492): onStart, Launcher: 976102361
D/Launcher.HomeView( 1492): onStart
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2084): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2084): [237392/6] SurfaceWidget drawing first frame
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/elm:14451( 8715): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 8715): ELMEngine.ELMEngine( context ).
,D/elm:14451( 8715): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/elm:14451( 8715): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
I/SurfaceFlinger(  250): id=17 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/StatusBarManagerService(  879): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,I/art     (  879): Explicit concurrent mark sweep GC freed 13615(710KB) AllocSpace objects, 1(16KB) LOS objects, 30% free, 36MB/52MB, paused 2.853ms total 220.499ms
,D/StatusBarManagerService(  879): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,E/Zygote  ( 8732): MountEmulatedStorage()
E/Zygote  ( 8732): v2
I/libpersona( 8732): KNOX_SDCARD checking this for 10017
I/libpersona( 8732): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8732 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,D/elm:14451( 8715): ElmAgentService : onCreate()
,D/elm:14451( 8715): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8715): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8715): MDMBridge.getInstance()
D/elm:14451( 8715): MDMBridge.getAllLicenseInfoFromSDK()
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,I/SELinux ( 8732): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/elm:14451( 8715): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux ( 8732): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8732): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/InputMethodManagerService(  879): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService(  879): Got RemoteException sending setActive(false) notification to pid 7648 uid 10200
,D/TimaKeyStoreProvider( 8732): TimaSignature is unavailable
,D/ActivityThread( 8732): Added TimaKeyStore provider
,D/elm:14451( 8715): ElmAgentService : onDestroy().
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager(  879): Killing 7233:com.sec.android.GeoLookout/u0a113 (adj 15): bgCount ##41
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 8732): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 8732): onReceive()
,I/com.sec.android.service.health.upgrade.UninstallReceiver( 8732): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8732): onReceive() : package name is not s health. Return !!!
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/PackageManager(  879): delete codoeFile: 
I/PCWCLIENTTRACE_PushUtil( 7756): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7756): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7756): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7756): [onReceive] - android.intent.action.PACKAGE_REMOVED
,W/ResourcesManager(  879): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  879): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/PackageManager(  879): result of delete: 1{942505276}
W/ResourcesManager(  879): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  879): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,W/libprocessgroup(  879): failed to open /acct/uid_10113/pid_7233/cgroup.procs: No such file or directory
,D/AndroidRuntime( 8684): Shutting down VM
,D/ResourcesManager(  879): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,I/Timeline(  879): Timeline: Activity_windows_visible id: ActivityRecord{210ae55c u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t15} time:316017
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/ResourcesManager(  879): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,E/Zygote  ( 8752): MountEmulatedStorage()
E/Zygote  ( 8752): v2
I/libpersona( 8752): KNOX_SDCARD checking this for 10038
I/libpersona( 8752): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8752 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  879): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  879): onPackageRemoved : com.test.thalitest
,I/SELinux ( 8752): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/ActivityManager(  879): Killing 7477:com.sec.android.app.taskmanager/u0a176 (adj 15): bgCount ##41
,I/SELinux ( 8752): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
W/ResourcesManager( 8228): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8228): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/SELinux ( 8752): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 8228): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 8228): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 8228): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 8752): TimaSignature is unavailable
,D/ActivityThread( 8752): Added TimaKeyStore provider
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8228): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 8752): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8228): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 8228): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/libprocessgroup(  879): failed to open /acct/uid_10176/pid_7477/cgroup.procs: No such file or directory
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8228): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8228): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 8228): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8228): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
E/SPPClientService( 8752): ============PushLog. commonIsShipBuild. stop!
W/ResourcesManager( 8228): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/SPPClientService( 8752): [PushClientApplication] Push log off : This is Ship build version
W/ResourcesManager( 8228): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/SPPClientService( 8752): PushLog.txt file is not deleted.
D/SPPClientService( 8752): PushLog.txt file is not deleted.
D/SPPClientService( 8752): ============PushLog. stop!
,W/ResourcesManager( 8228): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8228): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 8228): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/SA      ( 6680): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6680): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10200 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager(  879): Killing 7494:com.qualcomm.timeservice/1000 (adj 15): bgCount ##41
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 8228): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8228): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 8228): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 8228): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8770): MountEmulatedStorage()
E/Zygote  ( 8770): v2
I/libpersona( 8770): KNOX_SDCARD checking this for 10050
I/libpersona( 8770): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageReceiver: pid=8770 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/SELinux ( 8770): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8770): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8770): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  879): failed to open /acct/uid_1000/pid_7494/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8770): TimaSignature is unavailable
,D/ActivityThread( 8770): Added TimaKeyStore provider
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 8770): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8770): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8770): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8770): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8770): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8770): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 8785): MountEmulatedStorage()
E/Zygote  ( 8785): v2
I/libpersona( 8785): KNOX_SDCARD checking this for 10020
I/libpersona( 8785): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=8785 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
,I/SELinux ( 8785): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8785): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8785): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8785): TimaSignature is unavailable
,D/ActivityThread( 8785): Added TimaKeyStore provider
,D/ResourcesManager( 8785): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,D/Mms/MmsApp( 8770): [start]    onCreate() consume time = 0.0
,D/Mms/TelephonyPermission( 8770): start operation mode monitor
,D/ResourcesManager( 8770): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,E/SQLiteDatabase( 8785): Failed to open database '/data/user/0/com.sec.android.provider.logsprovider/databases/logs.db'.
E/SQLiteDatabase( 8785): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8785): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 8785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 8785): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8785): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteDatabase( 8785): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteDatabase( 8785): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8785): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteDatabase( 8785): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 8785): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8785): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8785): 	at com.sec.android.provider.logsprovider.LogsProvider.onCreate(LogsProvider.java:1851)
E/SQLiteDatabase( 8785): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 8785): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 8785): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
E/SQLiteDatabase( 8785): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
E/SQLiteDatabase( 8785): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
E/SQLiteDatabase( 8785): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 8785): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/SQLiteDatabase( 8785): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8785): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 8785): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/SQLiteDatabase( 8785): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8785): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8785): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 8785): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime( 8785): Shutting down VM
,W/ResourcesManager( 8770): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/AndroidRuntime( 8785): FATAL EXCEPTION: main
E/AndroidRuntime( 8785): Process: com.sec.android.provider.logsprovider, PID: 8785
E/AndroidRuntime( 8785): java.lang.RuntimeException: Unable to get provider com.sec.android.provider.logsprovider.LogsProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8785): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5456)
E/AndroidRuntime( 8785): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
E/AndroidRuntime( 8785): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
E/AndroidRuntime( 8785): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8785): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/AndroidRuntime( 8785): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8785): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 8785): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/AndroidRuntime( 8785): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8785): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8785): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 8785): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 8785): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8785): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 8785): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 8785): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8785): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8785): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/AndroidRuntime( 8785): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/AndroidRuntime( 8785): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8785): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/AndroidRuntime( 8785): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 8785): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 8785): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 8785): 	at com.sec.android.provider.logsprovider.LogsProvider.onCreate(LogsProvider.java:1851)
E/AndroidRuntime( 8785): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/AndroidRuntime( 8785): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/AndroidRuntime( 8785): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
E/AndroidRuntime( 8785): 	... 11 more
V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.sec.android.provider.logsprovider
D/Mms/TelephonyPermission( 8770): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 8770): isDefault true
D/Mms/MmsApp( 8770): onCreate() com.android.mms
I/Process ( 8785): Sending signal. PID: 8785 SIG: 9
E/DropBoxManagerService(  879): Can't write: system_app_crash
E/DropBoxManagerService(  879): java.io.FileNotFoundException: /data/system/dropbox/drop186.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  879): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  879): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  879): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  879): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  879): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  879): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:14540)
E/DropBoxManagerService(  879): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  879): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  879): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  879): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  879): 	... 5 more
D/Mms/MmsConfig( 8770): [start]    MmsConfig.init() consume time = 37.070469
D/Mms/MmsConfig( 8770): before partial update
,I/ActivityManager(  879): Process com.sec.android.provider.logsprovider (pid 8785)(adj 5) has died(156,552)
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
D/Mms/MmsConfig( 8770): Load Resize quality : 80
E/Zygote  ( 8805): MountEmulatedStorage()
E/Zygote  ( 8805): v2
I/libpersona( 8805): KNOX_SDCARD checking this for 10020
I/libpersona( 8805): KNOX_SDCARD not a persona
I/ActivityManager(  879): Start proc com.sec.android.provider.logsprovider for restart com.sec.android.provider.logsprovider: pid=8805 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
E/ActivityThread( 8770): Failed to find provider info for com.samsung.android.coreapps.easysignup.public
D/EasySignUpManager( 8770): serviceId : 1, features : -1
D/Mms/MmsConfig( 8770): setFreeMessageEnabled, free message policy(getSupportedFeatures) is = -1
D/TP/MmsSmsProvider( 1486): query,matched:2117, calling pid = 8770
I/SELinux ( 8805): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/TP/MmsSmsProvider( 1486): match 2117:Elapsed time : 1.345 ms
I/SELinux ( 8805): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8805): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
E/ActivityThread( 8770): Failed to find provider info for com.samsung.android.coreapps.easysignup.public
,D/EasySignUpManager( 8770): serviceId : 3, features : -1
D/Mms/MmsConfig( 8770): Shop agent feature value :-1
,D/Mms/MmsConfig( 8770):  enable multiwindow = true
,E/Mms/MessageUtils( 8770): setCountryDetector : update country detector info 
F/libc    ( 8770): Fatal signal 7 (SIGBUS), code 2, fault addr 0x71c43d10 in tid 8770 (com.android.mms)
,E/audit_log( 2055): File locking failed. error= Bad file number
,F/libc    ( 8770): Failed while talking to debuggerd: Broken pipe
E/audit_log( 2055): File locking failed. error= Bad file number
,D/TimaKeyStoreProvider( 8805): TimaSignature is unavailable
,D/ActivityThread( 8805): Added TimaKeyStore provider
,D/ResourcesManager( 8805): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,I/ActivityManager(  879): Process com.android.mms (pid 8770)(adj 0) has died(163,552)
,I/TactileAssist(  879): enable value -1
,I/TactileAssist(  879): internal enable value -1
I/TactileAssist(  879): intensity value -1
I/TactileAssist(  879): saveAppList value true
,I/EventHub(  879): Removing device '/dev/input/event4' due to inotify event
,E/SQLiteDatabase( 8805): Failed to open database '/data/user/0/com.sec.android.provider.logsprovider/databases/logs.db'.
E/SQLiteDatabase( 8805): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8805): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8805): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 8805): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 8805): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8805): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8805): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8805): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteDatabase( 8805): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteDatabase( 8805): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8805): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteDatabase( 8805): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 8805): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8805): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8805): 	at com.sec.android.provider.logsprovider.LogsProvider.onCreate(LogsProvider.java:1851)
E/SQLiteDatabase( 8805): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 8805): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 8805): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
E/SQLiteDatabase( 8805): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
E/SQLiteDatabase( 8805): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
E/SQLiteDatabase( 8805): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 8805): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/SQLiteDatabase( 8805): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8805): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 8805): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/SQLiteDatabase( 8805): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8805): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8805): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 8805): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime( 8805): Shutting down VM
,I/TactileAssist(  879): List of disabled apps :
E/AndroidRuntime( 8805): FATAL EXCEPTION: main
E/AndroidRuntime( 8805): Process: com.sec.android.provider.logsprovider, PID: 8805
E/AndroidRuntime( 8805): java.lang.RuntimeException: Unable to get provider com.sec.android.provider.logsprovider.LogsProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8805): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5456)
E/AndroidRuntime( 8805): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
E/AndroidRuntime( 8805): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
E/AndroidRuntime( 8805): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8805): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/AndroidRuntime( 8805): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8805): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 8805): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/AndroidRuntime( 8805): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8805): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8805): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 8805): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 8805): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8805): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8805): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 8805): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 8805): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8805): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8805): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8805): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/AndroidRuntime( 8805): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/AndroidRuntime( 8805): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8805): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/AndroidRuntime( 8805): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 8805): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 8805): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 8805): 	at com.sec.android.provider.logsprovider.LogsProvider.onCreate(LogsProvider.java:1851)
E/AndroidRuntime( 8805): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/AndroidRuntime( 8805): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/AndroidRuntime( 8805): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
E/AndroidRuntime( 8805): 	... 11 more
I/TactileAssist(  879): de.zalando.mobile
,V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.sec.android.provider.logsprovider
,E/SharedPreferencesImpl(  879): Couldn't create directory for SharedPreferences file /data/data/com.android.settings/shared_prefs/com.android.settings_tactileassist.xml
,W/ActivityManager(  879): Process com.sec.android.provider.logsprovider has crashed too many times: killing!
,I/ActivityManager(  879): Killing 8805:com.sec.android.provider.logsprovider/u0a20 (adj 5): crash
,W/ActivityManager(  879): Unable to launch app com.sec.android.provider.logsprovider/10020 for provider logs: launching app became null
I/ActivityManager(  879): Killing 1810:android.process.acore/u0a20 (adj 5): depends on provider com.sec.android.provider.logsprovider/.LogsProvider in dying proc com.sec.android.provider.logsprovider
E/ActivityThread( 1810): Failed to find provider info for logs
,F/libc    ( 1810): Fatal signal 7 (SIGBUS), code 2, fault addr 0x782a54a7 in tid 8768 (IntentService[V)
,F/libc    ( 1810): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2055): File locking failed. error= Bad file number
I/Zygote  (  314): Process 8770 exited due to signal (7)
,E/DropBoxManagerService(  879): Can't write: system_app_crash
E/DropBoxManagerService(  879): java.io.FileNotFoundException: /data/system/dropbox/drop187.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  879): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  879): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  879): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  879): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  879): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  879): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:14540)
E/DropBoxManagerService(  879): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  879): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  879): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  879): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  879): 	... 5 more
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8821): MountEmulatedStorage()
I/libpersona( 8821): KNOX_SDCARD checking this for 10058
E/Zygote  ( 8821): v2
I/libpersona( 8821): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=8821 uid=10058 gids={50058, 9997, 3003, 3002} abi=armeabi-v7a
,I/EventHub(  879): Removing device '/dev/input/event5' due to inotify event
,I/SELinux ( 8821): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
E/audit_log( 2055): File locking failed. error= Bad file number
I/SELinux ( 8821): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
F/libc    (  879): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa05154bc in tid 1840 (Binder_10)
F/libc    (  879): Unable to open connection to debuggerd: Connection refused
E/SELinux ( 8821): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/Zygote  (  314): Process 1810 exited due to signal (7)
,E/installd(  294): eof
E/installd(  294): failed to read size
I/installd(  294): closing connection
,I/ServiceManager(  248): service 'dreams' died
I/ServiceManager(  248): service 'print' died
I/ServiceManager(  248): service 'restrictions' died
I/ServiceManager(  248): service 'media_session' died
I/ServiceManager(  248): service 'media_router' died
I/ServiceManager(  248): service 'trust' died
I/ServiceManager(  248): service 'fingerprint' died
I/ServiceManager(  248): service 'launcherapps' died
I/ServiceManager(  248): service 'voip' died
I/ServiceManager(  248): service 'media_projection' died
I/ServiceManager(  248): service 'imms' died
I/ServiceManager(  248): service 'sec_analytics' died
I/ServiceManager(  248): service 'mum_container_policy' died
I/ServiceManager(  248): service 'enterprise_billing_policy' died
I/ServiceManager(  248): service 'knox_timakeystore_policy' died
I/ServiceManager(  248): service 'enterprise_policy' died
I/ServiceManager(  248): service 'statusbar' died
I/ServiceManager(  248): service 'clipboard' died
I/ServiceManager(  248): service 'clipboardEx' died
I/ServiceManager(  248): service 'network_management' died
I/ServiceManager(  248): service 'ABTPersistenceService' died
I/ServiceManager(  248): service 'textservices' died
I/ServiceManager(  248): service 'jobscheduler' died
I/ServiceManager(  248): service 'network_score' died
I/ServiceManager(  248): service 'netstats' died
I/ServiceManager(  248): service 'netpolicy' died
I/ServiceManager(  248): service 'wifiscanner' died
I/ServiceManager(  248): service 'rttmanager' died
I/ServiceManager(  248): service 'connectivity' died
I/ServiceManager(  248): service 'sb_service' died
I/ServiceManager(  248): service 'clinfo' died
I/ServiceManager(  248): service 'servicediscovery' died
I/ServiceManager(  248): service 'updatelock' died
I/ServiceManager(  248): service 'notification' died
I/ServiceManager(  248): service 'devicestoragemonitor' died
I/ServiceManager(  248): service 'location' died
I/ServiceManager(  248): service 'country_detector' died
I/ServiceManager(  248): service 'sec_location' died
I/ServiceManager(  248): service 'search' died
I/ServiceManager(  248): service 'dropbox' died
I/ServiceManager(  248): service 'wallpaper' died
I/ServiceManager(  248): service 'audio' died
I/ServiceManager(  248): service 'DockObserver' died
I/ServiceManager(  248): service 'usb' died
I/ServiceManager(  248): service 'serial' died
I/ServiceManager(  248): service 'uimode' died
I/ServiceManager(  248): service 'wifip2p' died
I/ServiceManager(  248): service 'backup' died
I/ServiceManager(  248): service 'appwidget' died
I/ServiceManager(  248): service 'voiceinteraction' died
I/ServiceManager(  248): service 'SecExternalDisplayService' died
I/ServiceManager(  248): service 'diskstats' died
I/ServiceManager(  248): service 'spengestureservice' died
I/ServiceManager(  248): service 'quickconnect' died
I/ServiceManager(  248): service 'samplingprofiler' died
I/ServiceManager(  248): service 'commontime_management' died
I/ServiceManager(  248): service 'wifi' died
W/Sensors ( 2191): sensorservice died [0xaf0c0c40]
I/ServiceManager(  248): service 'msapwifi' died
I/ServiceManager(  248): service 'scheduling_policy' died
I/ServiceManager(  248): service 'context_aware' died
I/ServiceManager(  248): service 'scontext' died
I/ServiceManager(  248): service 'barbeam' died
I/ServiceManager(  248): service 'multiwindow_facade' died
I/ServiceManager(  248): service 'window' died
I/ServiceManager(  248): service 'input' died
I/ServiceManager(  248): service 'input_method' died
I/ServiceManager(  248): service 'accessibility' died
I/ServiceManager(  248): service 'motion_recognition' died
I/ServiceManager(  248): service 'cover' died
I/ServiceManager(  248): service 'mount' died
I/ServiceManager(  248): service 'lock_settings' died
I/ServiceManager(  248): service 'device_policy' died
I/ServiceManager(  248): service 'harmony_eas_service' died
I/ServiceManager(  248): service 'sdp' died
I/ServiceManager(  248): service 'log_manager_service' died
I/ServiceManager(  248): servic,e 'tactileassist' died
I/ServiceManager(  248): service 'bluetooth_manager' died
I/ServiceManager(  248): service 'bluetooth_secure_mode_manager' died
I/ServiceManager(  248): service 'rcp' died
I/ServiceManager(  248): service 'batterystats' died
I/ServiceManager(  248): service 'appops' died
I/ServiceManager(  248): service 'power' died
I/ServiceManager(  248): service 'display' died
I/ServiceManager(  248): service 'SEAMService' died
I/ServiceManager(  248): service 'persona' died
I/ServiceManager(  248): service 'account' died
I/ServiceManager(  248): service 'content' died
I/ServiceManager(  248): service 'DirEncryptService' died
I/ServiceManager(  248): service 'ReactiveService' died
I/ServiceManager(  248): service 'persona_policy' died
I/ServiceManager(  248): service 'sedenial' died
I/ServiceManager(  248): service 'vibrator' died
I/ServiceManager(  248): service 'tw_toolbox' died
I/ServiceManager(  248): service 'tima' died
I/ServiceManager(  248): service 'cepproxyks' died
I/ServiceManager(  248): service 'enterprise_license_policy' died
I/ServiceManager(  248): service 'application_policy' died
I/ServiceManager(  248): service 'wifi_policy' died
I/ServiceManager(  248): service 'phone_restriction_policy' died
I/ServiceManager(  248): service 'remoteinjection' died
I/ServiceManager(  248): service 'CustomFrequencyManagerService' died
I/ServiceManager(  248): service 'samsung.smartfaceservice' died
I/ServiceManager(  248): service 'consumer_ir' died
I/ServiceManager(  248): service 'alarm' died
I/ServiceManager(  248): service 'entropy' died
I/ServiceManager(  248): service 'user' died
I/ServiceManager(  248): service 'dbinfo' died
I/ServiceManager(  248): service 'hardware' died
W/Sensors ( 1300): sensorservice died [0x9d9212c0]
I/ServiceManager(  248): service 'cpuinfo' died
I/ServiceManager(  248): service 'battery' died
I/ServiceManager(  248): service 'webviewupdate' died
I/ServiceManager(  248): service 'package' died
I/ServiceManager(  248): service 'procstats' died
I/ServiceManager(  248): service 'activity' died
I/ServiceManager(  248): service 'gfxinfo' died
I/ServiceManager(  248): service 'meminfo' died
I/ServiceManager(  248): service 'permission' died
I/ServiceManager(  248): service 'usagestats' died
I/ServiceManager(  248): service 'telephony.registry' died
I/ServiceManager(  248): service 'edmnativehelper' died
I/ServiceManager(  248): service 'sensorservice' died
I/ServiceManager(  248): service 'mdm.remotedesktop' died
I/SurfaceFlinger(  250): restart the boot-animation @ binderDied
W/Sensors ( 1178): sensorservice died [0xaf0d2100]
W/AudioFlinger(  291): power manager service died !!!
W/AudioFlinger(  291): power manager service died !!!
W/Sensors ( 1470): sensorservice died [0xaf0c0c00]
I/SurfaceFlinger(  250): id=2 Removed FocusedStackFrame (5/8)
I/SurfaceFlinger(  250): id=3 Removed DimLayer (0/7)
I/SurfaceFlinger(  250): id=4 Removed DimLayer (0/6),
I/SurfaceFlinger(  250): id=5 Removed DimLayer (0/5)
I/SurfaceFlinger(  250): id=6 Removed DimLayer (0/4)
W/Sensors ( 1492): sensorservice died [0xaf0c3400]
W/Sensors ( 1486): sensorservice died [0xaf0643c0]
W/Sensors ( 8247): sensorservice died [0xaf0fa540]
,W/Sensors ( 2156): sensorservice died [0xaf0c3f00]
,E/WifiManager( 1178): Channel connection lost
,E/WifiManager( 1575): Channel connection lost
,E/WifiManager( 1659): Channel connection lost
,E/WifiManager( 2156): Channel connection lost
,I/SurfaceFlinger(  250): id=2 Removed FocusedStackFrame (-2/4)
I/SurfaceFlinger(  250): id=3 Removed DimLayer (-2/4)
I/SurfaceFlinger(  250): id=4 Removed DimLayer (-2/4)
,I/SurfaceFlinger(  250): id=17 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (1/3)
,I/SurfaceFlinger(  250): id=14 Removed ColorFade (2/2)
I/SurfaceFlinger(  250): id=7 Removed com.android.systemui.ImageWallpaper (0/1)
,I/SurfaceFlinger(  250): id=7 Removed com.android.systemui.ImageWallpaper (-2/1)
I/SurfaceFlinger(  250): id=17 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/1)
I/SurfaceFlinger(  250): id=9 Removed StatusBar (0/0)
,I/SurfaceFlinger(  250): id=9 Removed StatusBar (-2/0)
F/libc    ( 2126): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7247b420 in tid 2150 (Binder_1)
E/WifiManager( 1486): Channel connection lost
D/SurfaceFlinger(  250): Set power mode=2, type=0 flinger=0xb6a62000
D/qdhwcomposer(  250): hwc_blank: Unblanking display: 0
,E/WifiManager( 1300): Channel connection lost
,F/libc    ( 2126): Unable to open connection to debuggerd: Connection refused
I/SurfaceFlinger(  250): id=5 Removed DimLayer (-2/0)
I/SurfaceFlinger(  250): id=6 Removed DimLayer (-2/0)
I/SurfaceFlinger(  250): id=14 Removed ColorFade (-2/0)
,E/audit_log( 2055): File locking failed. error= Bad file number
,F/libc    ( 8821): Fatal signal 7 (SIGBUS), code 2, fault addr 0x759acd71 in tid 8821 (.app.soundalive)
,F/libc    ( 8821): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2055): File locking failed. error= Bad file number
,F/libc    ( 4552): Fatal signal 7 (SIGBUS), code 2, fault addr 0x758bd083 in tid 4590 (AppProvider)
,F/libc    ( 4552): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2055): File locking failed. error= Bad file number
,I/Zygote  (  314): Process 8821 exited due to signal (7)
,I/Zygote  (  314): Process 4552 exited due to signal (7)
,I/Zygote  (  314): Process 2126 exited due to signal (7)
,E/SMD     (  284): DCD ON
,I/qdhwcomposer(  250): handle_blank_event: dpy:0 panel power state: 1
,E/qdexternal(  250): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  250): hwc_blank: Done unblanking display: 0
,I/SurfaceFlinger(  250): Disp[0] Orientation 0=>0
,I/qdhwcomposer(  250): handle_blank_event: dpy:0 panel power state: 0

```
