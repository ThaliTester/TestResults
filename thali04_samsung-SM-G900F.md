#### Test 50650278b86327b_thali04_samsung-SM-G900F Logs


```
--------- beginning of main
D/KeyguardViewMediator( 1180): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 1180): handleNotifyScreenOff
D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
--------- beginning of system
D/LightsService(  896): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 896) 
D/LightsService(  896): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/LightsService(  896): [SvcLED]  onSensorChanged::light value = 2
D/SensorManager(  896): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/SensorManager(  896): unregisterListener ::   
D/lights  (  896): led_pattern : 5 +
D/lights  (  896): led_pattern : 5 -
D/BatteryService(  896): turn on LED for fully charged
D/LightsService(  896): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/CAE     (  896): handleMessage(CaPowerManager.java:182) - AP_SLEEP
I/CAE     (  896): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  896): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  896): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  305): sendContextData: -76, 13, -46, 0
D/Mms/FreeMessageReceiver( 5792): onReceive, action : android.intent.action.PACKAGE_ADDED
I/CAE     (  896): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 14, 12, 22,
D/SensorHubManager(  896): SendSensorHubData: send data = -63, 14, 14, 12, 22
D/Sensorhubs(  305): sendContextData: -63, 14, 14, 12, 22
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
D/Mms/FreeMessageReceiverService( 5792): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5792): onHandleIntent: ACTION_PACKAGE_ADDED
E/Zygote  ( 7380): MountEmulatedStorage()
I/libpersona( 7380): KNOX_SDCARD checking this for 10050
E/Zygote  ( 7380): v2
I/libpersona( 7380): KNOX_SDCARD not a persona
I/ActivityManager(  896): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7380 uid=10050 gids={50050, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  896):  handler : SCREEN_OFF end 
D/WifiStateMachine(  896): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  896): handleScreenStateChanged Exit: false
I/SELinux ( 7380): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/NotificationService(  896): ACTION_SCREEN_OFF
I/art     (  318): Explicit concurrent mark sweep GC freed 8736(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 277us total 11.367ms
E/WifiStateMachine(  896): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
I/SELinux ( 7380): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/LightsService(  896): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 896) 
E/WifiStateMachine(  896): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  896): do suspend true
D/LightsService(  896): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService(  896): [SvcLED]  onSensorChanged::light value = 2
E/SELinux ( 7380): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  896): Killing 5663:com.sec.android.app.samsungapps/u0a39 (adj 15): bgCount ##41
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 345us total 9.440ms
D/SensorManager(  896): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/SensorManager(  896): unregisterListener ::   
D/LightsService(  896): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/audio_hw_primary(  299): adev_set_parameters: enter: screen_state=off
V/voice   (  299): voice_set_parameters: enter: screen_state=off
V/voice   (  299): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  299): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  299): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  299): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  299): adev_set_parameters: exit
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 271us total 8.548ms
I/SecExternalDisplayIntents_Java(  896): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
I/Icing   ( 2470): Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
D/IpRemoteDisplayController(  896): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  896): Bridge Server is not available
D/VolumePanel( 1180): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1180): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/VolumePanel( 1180): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1180): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
D/TimaKeyStoreProvider( 7380): TimaSignature is unavailable
D/ActivityThread( 7380): Added TimaKeyStore provider
I/Icing   ( 2470): Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
D/PersonaManagerService(  896): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler(  896): MSG_ACTION_SCREEN_OFF called
D/ResourcesManager( 7380): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/NfcService( 1478): call the applyRotuiing
W/ResourcesManager( 7380): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7380): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/DisplayPowerState(  896): !@ ColorFade entry
D/DisplayPowerController(  896): ColorFade: onAnimationEnd
D/AutomaticBrightnessController(  896): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
D/AutomaticBrightnessController(  896): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  896): Light old sensor_state 513, new sensor_state : 1 en : 0
I/AutomaticBrightnessController(  896): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
I/AutomaticBrightnessController(  896): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
W/libprocessgroup(  896): failed to open /acct/uid_10039/pid_5663/cgroup.procs: No such file or directory
D/STATUSBAR-PhoneStatusBar( 1180):      ACTION_SCREEN_OFF is finished!!!! 
D/SensorManager(  896): unregisterListener ::   
E/Sensors (  896): Acc old sensor_state 1, new sensor_state : 0 en : 0
D/SensorManager(  896): unregisterListener ::   
E/StatusBar( 1180): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1180): dismissHelpPopup 
D/accuweather( 2067): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 2067): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2067): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
D/DisplayPowerController(  896): getFinalBrightness : 0 -> 0
D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb6962000
D/qdhwcomposer(  257): hwc_blank: Blanking display: 0
I/DisplayManagerService(  896): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  896): Display changed displayId=0
D/DisplayPowerController(  896): getFinalBrightness : 0 -> 0
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/StatusBar.NetworkController( 1180): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
I/SystemBroadcastReceiver( 6280): [#DCM#] [DCM_Performance] onReceive completed in time  303 microsec. 
I/SystemBroadcastReceiver( 6280): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 6280): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 6280): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
D/MyFiles ( 7380): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
W/ActivityManager(  896): getTasks: caller 10085 does not hold GET_TASKS; limiting output
W/ActivityManager(  896): getTasks: caller 10085 does not hold GET_TASKS; limiting output
D/SSRM:m  (  896): SIOP:: AP = 370, PST = 373, CUR = 450
D/PowerManagerService(  896): [PWL] sb release: PowerManagerService.Broadcasts
I/TactileAssist(  896): enable value -1
I/TactileAssist(  896): internal enable value -1
I/TactileAssist(  896): intensity value -1
I/TactileAssist(  896): saveAppList value true
I/TactileAssist(  896): List of disabled apps :
E/installd(  302): system dir 0 : /system/app/
E/installd(  302): system dir 1 : /system/priv-app/
E/installd(  302): system dir 2 : /vendor/app/
E/installd(  302): system dir 3 : /oem/app/
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7400): MountEmulatedStorage()
E/Zygote  ( 7400): v2
I/libpersona( 7400): KNOX_SDCARD checking this for 10057
I/libpersona( 7400): KNOX_SDCARD not a persona
I/ActivityManager(  896): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7400 uid=10057 gids={50057, 9997, 3003, 3002} abi=armeabi-v7a
D/AndroidRuntime( 7396): 
D/AndroidRuntime( 7396): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/rmt_storage(  283): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6c01090
I/rmt_storage(  283): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  283): wakelock acquired: 1, error no: 42
I/rmt_storage(  283): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1228406016)
D/AndroidRuntime( 7396): CheckJNI is OFF
I/SELinux ( 7400): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/AndroidRuntime( 7396): setted country_code = Poland
D/AndroidRuntime( 7396): setted countryiso_code = PL
D/AndroidRuntime( 7396): setted sales_code = XEO
I/SELinux ( 7400): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/AndroidRuntime( 7396): readGMSProperty: start
D/AndroidRuntime( 7396): readGMSProperty: already setted!!
D/AndroidRuntime( 7396): readGMSProperty: end
D/AndroidRuntime( 7396): addProductProperty: start
E/SELinux ( 7400): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/PackageManager(  896): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
D/TimaKeyStoreProvider( 7400): TimaSignature is unavailable
D/ActivityThread( 7400): Added TimaKeyStore provider
D/ResourcesManager( 7400): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
W/ResourcesManager( 7400): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/rmt_storage(  283): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  283): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  283): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1228406016) wakelock released: 1, error no: 22
I/rmt_storage(  283): 
I/rmt_storage(  283): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6c01090
D/Compatibility( 7400): onReceive() it will make start service
D/Compatibility( 7400): onHandleIntent()
D/Compatibility( 7400): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10356, android.intent.extra.user_handle=0}]
D/Compatibility( 7400): found: 2
I/UpdateIcingCorporaServi( 1679): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Compatibility( 7400): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7400): skipping ResolveInfo{1934218e com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 7400): considering ResolveInfo{1f3fbdaf com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 7400): default: com.sec.android.app.soundalive.SAControlPanelActivity
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
D/Compatibility( 7400): enabling receiver ResolveInfo{1e4945bc com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
D/Compatibility( 7400): enabling receiver ResolveInfo{23da2945 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 7400): enabling receiver ResolveInfo{2cd4c89a com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 7400): enabling receiver ResolveInfo{2cd485cb com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
E/Zygote  ( 7428): MountEmulatedStorage()
E/Zygote  ( 7428): v2
I/libpersona( 7428): KNOX_SDCARD checking this for 1000
I/libpersona( 7428): KNOX_SDCARD not a persona
I/ActivityManager(  896): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7428 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/Compatibility( 7400): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
I/SELinux ( 7428): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7428): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7428): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  257): hwc_blank: Done blanking display: 0
E/AffinityControl( 7396): AffinityControl: registerfunction enter
D/SurfaceControl(  896): Excessive delay in setPowerMode(): 253ms
D/PowerManagerService(  896): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  896): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  896): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL(  896): Got set_interactive hint
I/PowerManagerService(  896): [PWL] Off : 0s ago
I/PowerManagerService(  896): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  896): [PWL]     mDisplayReady : false
D/DisplayPowerController(  896): getFinalBrightness : 0 -> 0
D/PowerManagerService(  896): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  896): [PWL] sb release: PowerManagerService.Display
I/ActivityManager(  896): Killing 6050:com.sec.providers.settingsearch/u0a167 (adj 15): bgCount ##41
D/AndroidRuntime( 7396): Calling main entry com.android.commands.am.Am
D/TimaKeyStoreProvider( 7428): TimaSignature is unavailable
D/ActivityThread( 7428): Added TimaKeyStore provider
D/ResourcesManager( 1679): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
E/PersonaManagerService(  896): inState():  stateMachine is null !!
V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  896): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  896): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/ResourcesManager( 7428): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
I/UpdateIcingCorporaServi( 1679): UpdateCorporaTask done [took 76 ms] updated apps [took 76 ms] 
V/AlarmManager(  896): waitForAlarm result :4
W/ActivityManager(  896): mDVFSHelper.acquire()
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7445): MountEmulatedStorage()
E/Zygote  ( 7445): v2
I/libpersona( 7445): KNOX_SDCARD checking this for 10356
I/libpersona( 7445): KNOX_SDCARD not a persona
I/ActivityManager(  896): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7445 uid=10356 gids={50356, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7445): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/AndroidRuntime( 7396): Shutting down VM
W/libprocessgroup(  896): failed to open /acct/uid_10167/pid_6050/cgroup.procs: No such file or directory
I/SELinux ( 7445): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7445): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ContextImpl( 7428): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/TimaKeyStoreProvider( 7445): TimaSignature is unavailable
D/ActivityThread( 7445): Added TimaKeyStore provider
D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  896): stay LED for fully charged
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
I/SQLiteSecureOpenHelper( 3486): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3486): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
I/SurfaceFlinger(  257): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (5/8)
I/SurfaceFlinger(  257): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/8)
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
D/ResourcesManager( 7445): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3229): Disconnected process message: 10
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
E/Zygote  ( 7461): MountEmulatedStorage()
E/Zygote  ( 7461): v2
I/libpersona( 7461): KNOX_SDCARD checking this for 10097
I/libpersona( 7461): KNOX_SDCARD not a persona
I/ActivityManager(  896): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7461 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  896): Killing 5865:com.google.android.gm/u0a113 (adj 15): bgCount ##41
I/SELinux ( 7461): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
I/SELinux ( 7461): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7461): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  896): failed to open /acct/uid_10113/pid_5865/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 7461): TimaSignature is unavailable
D/ActivityThread( 7461): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/ResourcesManager( 7461): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/WebViewFactory( 7445): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7445): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 7445): Loading: webviewchromium
,I/LibraryLoader( 7445): Time to load native libraries: 2 ms (timestamps 6355-6357)
I/LibraryLoader( 7445): Expected native library version number "",actual native library version number ""
D/DocsApplication( 7461): Installing DEX configuration.
V/WebViewChromiumFactoryProvider( 7445): Binding Chromium to main looper Looper (main, tid 1) {2cd4c89a}
I/LibraryLoader( 7445): Expected native library version number "",actual native library version number ""
I/chromium( 7445): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7445): Initializing chromium process, renderers=0
W/art     ( 7445): Attempt to remove local handle scope entry from IRT, ignoring
D/DexInstaller( 7461): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
W/chromium( 7445): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7445): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7445): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
I/PackageInfoHelper( 7461): Provided clientMode=RELEASE, packageInfo=PackageInfo{c743d89 com.google.android.apps.docs}
I/Adreno-EGL( 7445): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7445): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7445): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7445): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7445): Remote Branch: 
I/Adreno-EGL( 7445): Local Patches: 
I/Adreno-EGL( 7445): Reconstruct Branch: 
D/TAG     ( 7461): onCreate()
D/CrossAppStateProvider( 7461): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
W/chromium( 7445): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7445): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7445): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7445): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7445): CordovaWebView is running on device made by: samsung
W/art     ( 7445): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7445): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity( 7445): performCreate Call secproduct feature valuefalse
D/Activity( 7445): performCreate Call debug elastic valuetrue
E/SMD     (  294): DCD ON
D/OpenGLRenderer( 7445): Render dirty regions requested: true
D/ActivityManager(  896): post active user change for 0
D/KnoxTimeoutHandler(  896): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  896): handleActiveUserChange for user 0
I/SurfaceFlinger(  257): id=16 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/StatusBarManagerService(  896): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/StatusBarManagerService(  896): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
I/OpenGLRenderer( 7445): Initialized EGL, version 1.4
I/OpenGLRenderer( 7445): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7445): Enabling debug mode 0
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/InputMethodManagerService(  896): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
W/IInputConnectionWrapper( 7445): showStatusIcon on inactive InputConnection
I/Timeline( 7445): Timeline: Activity_idle id: android.os.BinderProxy@16b0edb5 time:106690
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
W/ActivityManager(  896): mDVFSHelper.release()
I/Timeline(  896): Timeline: Activity_windows_visible id: ActivityRecord{328064af u0 com.test.thalitest/.MainActivity t4} time:106713
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/JsMessageQueue( 7445): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 7445): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358606336
D/JX-Cordova( 7445): jxcore cordova android initializing
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/Zygote  ( 7522): MountEmulatedStorage()
E/Zygote  ( 7522): v2
I/libpersona( 7522): KNOX_SDCARD checking this for 10098
I/libpersona( 7522): KNOX_SDCARD not a persona
I/ActivityManager(  896): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=7522 uid=10098 gids={50098, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  896): Killing 6280:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
I/SELinux ( 7522): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7522): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7522): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/GAV2    ( 7461): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/TimaKeyStoreProvider( 7522): TimaSignature is unavailable
D/ActivityThread( 7522): Added TimaKeyStore provider
D/ResourcesManager( 7522): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
W/ResourcesManager( 7522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/libprocessgroup(  896): failed to open /acct/uid_10004/pid_6280/cgroup.procs: No such file or directory
E/[CarMode]( 7522): [DLApplication]-onCreate: Applicatino Started!
D/SampleAppCoreManager( 7522): SampleAppCoreManager VACVersion '2.2.0.11867'
I/VlingoAndroidCore( 7522): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7546): MountEmulatedStorage()
E/Zygote  ( 7546): v2
I/libpersona( 7546): KNOX_SDCARD checking this for 10032
I/libpersona( 7546): KNOX_SDCARD not a persona
I/ActivityManager(  896): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=7546 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 7546): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7546): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7546): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7546): TimaSignature is unavailable
D/ActivityThread( 7546): Added TimaKeyStore provider
D/ResourcesManager( 7546): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
W/ResourcesManager( 7546): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/System.out( 7546): Inside onCreate() of WakeupTriggerProvide
I/System.out( 7546): Inside WakeupProvider
E/DatabaseUtils( 7546): Writing exception to parcel
E/DatabaseUtils( 7546): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7546): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7546): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7546): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7546): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7546): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7546): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7546): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7546): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7546): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7546): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 7522): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
I/VlingoApplication( 7546): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=XEO
W/System.err( 7522): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7522): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7522): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7522): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7522): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7522): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7522): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7522): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7522): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7522): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7522): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7522): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7522): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 7522): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 7522): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 7522): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 7522): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 7522): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 7522): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 7522): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7522): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7522): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7522): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7522): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7522): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7522): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7522): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7522): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7522): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/Atfwd_Sendcmd(  328): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  328): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
E/DatabaseUtils( 7546): Writing exception to parcel
E/DatabaseUtils( 7546): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7546): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7546): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7546): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7546): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7546): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7546): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7546): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7546): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7546): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7546): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 7522): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err( 7522): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7522): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7522): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7522): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7522): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7522): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7522): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7522): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7522): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7522): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7522): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7522): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7522): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 7522): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 7522): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 7522): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 7522): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7522): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7522): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7522): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7522): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7522): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7522): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7522): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7522): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7522): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode]( 7522): [DLApplication]-Init Called!:false
E/[CarMode]( 7522): [DLApplication]-Init Started!:true
I/[CarModeFW]( 7522): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 7522): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 7522): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 7522): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 7522): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 7522): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 7522): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 7522): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 7522): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 7522): ### android.os.Looper::loop(145)
I/[CarModeFW]( 7522): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 7522): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 7522): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 7522): ### com.android.internal.os.ZygoteInit::main(1194)
W/GAV2    ( 7461): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/VlingoAndroidCore( 7546): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
I/MessageDataHandler( 7522): initialize
D/[CarModeFW]( 7522): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 7522): CDH-initiazlieCaches : after sync
D/[CarModeFW]( 7522): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 7522): CDH-ContactDataHandler initiazlieCaches time : 15
D/[CarModeFW]( 7522): CDH-initiazlieCaches : end sync
D/[CarModeFW]( 7522): DrivingManager-initialize...
I/SensorService(  896): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
I/SensorService(  896): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  896): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
D/VlingoApplication( 7546): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication( 7546): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
I/MediaPlayer( 7522): Need to enable context aware info
V/MediaPlayer-JNI( 7522): native_setup
V/MediaPlayer( 7522): constructor
V/MediaPlayer( 7522): setListener
E/MediaPlayer-JNI( 7522): QCMediaPlayer mediaplayer NOT present
D/[CarModeFW]( 7522): PushMessageManager-bindPushMessageService
I/[CarModeFW]( 7522): DriveLinkServiceInterfaceImp-drivelink framework initialize end
D/[CarMode]( 7522): [DLServiceManager]-getOnDLLocationSuggestionListener..........
D/[CarModeFW]( 7522): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1449756744501
D/[CarModeFW]( 7522): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1449756744501
D/[CarModeFW]( 7522): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1449756744501
D/[CarMode]( 7522): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW]( 7522): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1449756744501
D/[CarModeFW]( 7522): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1449756744502
D/[CarModeFW]( 7522): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1449756744502
I/[CarMode]( 7522): [LogNotNull]-Package name is: com.google.android.apps.maps
E/[CarMode]( 7522): [DLApplication]-Init End!:true
D/[CarModeFW]( 7522): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 7522): RecommendHandler-selection = type = '3'
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
D/TP/SmsProvider( 1485): query,matched:2, calling pid = 7522
D/TP/SmsProvider( 1485): match 2:Elapsed time : 1.592 ms
E/Zygote  ( 7584): MountEmulatedStorage()
I/libpersona( 7584): KNOX_SDCARD checking this for 10019
E/Zygote  ( 7584): v2
I/libpersona( 7584): KNOX_SDCARD not a persona
I/ActivityManager(  896): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7584 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
,I/SELinux ( 7584): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7584): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/[CarMode]( 7522): [DLApplication]-GooglePlayServices SUCCESS.
E/SELinux ( 7584): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TP/SmsProvider( 1485): query,matched:2, calling pid = 7522
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,D/TP/SmsProvider( 1485): match 2:Elapsed time : 1.726 ms
,E/Zygote  ( 7593): MountEmulatedStorage()
I/libpersona( 7593): KNOX_SDCARD checking this for 10003
E/Zygote  ( 7593): v2
I/libpersona( 7593): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=7593 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,E/[CarMode]( 7522): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,I/UpdateManagerReceiver( 7522): Intent : android.intent.action.PACKAGE_ADDEDThu Dec 10 15:12:24 GMT+01:00 2015
,I/SELinux ( 7593): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 7584): TimaSignature is unavailable
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
I/SELinux ( 7593): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 7584): Added TimaKeyStore provider
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/SELinux ( 7593): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/MessageDataHandler( 7522):  getInboxList smsCursor : 158
,E/Zygote  ( 7607): MountEmulatedStorage()
E/Zygote  ( 7607): v2
I/libpersona( 7607): KNOX_SDCARD checking this for 1000
I/libpersona( 7607): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7607 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7607): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7607): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7593): TimaSignature is unavailable
,D/ActivityThread( 7593): Added TimaKeyStore provider
D/[CarModeFW]( 7522): CDH-buildContactCacheWireFrame : cur len =0
I/ActivityManager(  896): Killing 6354:com.sec.android.app.music:service/u0a43 (adj 15): bgCount ##41
D/TP/MmsProvider( 1485): Query uri=content://mms/inbox, match=2, calling pid = 7522
D/TimaKeyStoreProvider( 7607): TimaSignature is unavailable
D/ActivityThread( 7607): Added TimaKeyStore provider
D/TP/MmsProvider( 1485): Query uri=content://mms, match=0, calling pid = 7522
,D/MessageDataHandler( 7522):  getInboxList mmsCursor : 90
,D/[CarModeFW]( 7522): PushMessageService-onCreate
,I/ActivityManager(  896): Killing 6879:com.sec.android.fotaclient/u0a10 (adj 15): bgCount ##41
I/ActivityManager(  896): Killing 6713:com.google.android.gms:car/u0a11 (adj 15): bgCount ##42
,I/ActivityManager(  896): Killing 6245:com.google.android.music:main/u0a125 (adj 15): bgCount ##43
,D/ResourcesManager( 7584): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,D/[CarModeFW]( 7522): PushMessageManager-onServiceConnected
D/[CarModeFW]( 7522): PushMessageService-registerPushMessageServiceListener
,D/ResourcesManager( 7593): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/UserAnalysis.PlaceProvider( 7593): PlaceProvider onCreate()
,W/jxcore-log( 7445): Initializing JXcore engine
,W/jxcore-log( 7445): JXcore engine is ready
,W/jxcore-log( 7445): Starting JXcore engine
,I/art     (  896): Explicit concurrent mark sweep GC freed 239997(15MB) AllocSpace objects, 5(4MB) LOS objects, 31% free, 35MB/51MB, paused 1.471ms total 143.762ms
,D/UserAnalysis.SecureDbManager( 7593): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 7593): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 7593): Create SecureDbHelper
,D/ResourcesManager( 7607): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,D/[CarModeFW]( 7522): CDH-buildContactCacheWireFrame : cur len =0
,I/MessageDataHandler( 7522): getUnreadMessageCount :0
D/[CarModeFW]( 7522): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 419
,D/MessageDataHandler( 7522):  getInboxList mms,sms cursor join : 172
,D/IntelligenceServiceApplication( 7593): onCreate()
,D/[CarModeFW]( 7522): RecommendHandler-selection = type = '3'
,D/TP/MmsSmsProvider( 1485): query,matched:0, calling pid = 7522
E/auditd  ( 2187): In denial and Property audit_ondenial is set to 1 
V/TP/MmsSmsProvider( 1485): getSimpleConversations entered.
,I/SQLiteSecureOpenHelper( 7593): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 7593): getDatabaseLocked(b,b,pwd)...
D/SecurityLogAgent:SEDenialService(  896): Got Modify Event and sending Denial Intent foraudit.log
I/SQLiteSecureOpenHelper( 7593): Open Place.db in secure mode
,D/TP/MmsSmsProvider( 1485): match 0:Elapsed time : 1.602 ms
,W/ContextImpl( 7607): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  896): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,D/TP/MmsSmsProvider( 1485): query,matched:13, calling pid = 7522
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
D/TP/MmsSmsProvider( 1485): match 13:Elapsed time : 0.759 ms
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 7607): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,E/Zygote  ( 7630): MountEmulatedStorage()
E/Zygote  ( 7630): v2
I/libpersona( 7630): KNOX_SDCARD checking this for 10111
I/libpersona( 7630): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7630 uid=10111 gids={50111, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SQLiteSecureOpenHelper( 7593): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 7593): ...getDatabaseLocked(b,b,pwd)
,I/SELinux ( 7630): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7630): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/MessageDataHandler( 7522):  getInboxList address cursor : 54
E/FilterInstaller( 7607): There is no requred permission
,E/SELinux ( 7630): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  896): Killing 6898:com.samsung.klmsagent/u0a18 (adj 15): bgCount ##41
,D/[CarModeFW]( 7522): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 7522): MyPlaceProvider-=============
,D/[CarModeFW]( 7522): MyPlaceProvider-=============
,D/TP/MmsSmsProvider( 1485): query,matched:0, calling pid = 7522
V/TP/MmsSmsProvider( 1485): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1485): match 0:Elapsed time : 0.775 ms
,D/[CarModeFW]( 7522): MyPlaceProvider-=============
D/[CarModeFW]( 7522): MyPlaceProvider-=============
D/[CarModeFW]( 7522): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 7522): MyPlaceProvider-==============
D/[CarModeFW]( 7522): MyPlaceProvider-latitude is not valid
,D/[CarModeFW]( 7522): MyPlaceProvider-==============
D/[CarModeFW]( 7522): MyPlaceProvider-latitude is not valid
D/MessageDataHandler( 7522):  getInboxList thread cursor : 11
,D/MessageDataHandler( 7522):  thread, addr result: 2
I/[CarModeFW]( 7522): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 510
I/[CarModeFW]( 7522): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 7522): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 511
,D/[CarModeFW]( 7522): MyPlaceProvider-==============
D/[CarModeFW]( 7522): MyPlaceProvider-latitude is not valid
,D/TimaKeyStoreProvider( 7630): TimaSignature is unavailable
D/ActivityThread( 7630): Added TimaKeyStore provider
,D/[CarModeFW]( 7522): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 525
,D/[CarMode]( 7522): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@e70b50b5, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@24f9c707] LOCATIONS
,W/libprocessgroup(  896): failed to open /acct/uid_10043/pid_6354/cgroup.procs: No such file or directory
,W/libprocessgroup(  896): failed to open /acct/uid_10010/pid_6879/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10125/pid_6245/cgroup.procs: No such file or directory
,W/libprocessgroup(  896): failed to open /acct/uid_10011/pid_6713/cgroup.procs: No such file or directory
W/jxcore-log( 7445): Platform android
W/jxcore-log( 7445): 
W/jxcore-log( 7445): Process ARCH arm
W/jxcore-log( 7445): 
D/ResourcesManager( 7630): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
D/[CarModeFW]( 7522): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 548
,I/[CarModeFW]( 7522): -[snowdeer] Rec : Missed Call : 131
,I/[CarModeFW]( 7522): -[snowdeer] Rec : Favorite : 6
,I/[CarModeFW]( 7522): -[snowdeer] Rec : CallLog : 5
,D/PackageIntentReceiver( 7630): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 7630): Not GearManger package! 
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  896): failed to open /acct/uid_10018/pid_6898/cgroup.procs: No such file or directory
,E/Zygote  ( 7647): MountEmulatedStorage()
E/Zygote  ( 7647): v2
I/libpersona( 7647): KNOX_SDCARD checking this for 10117
I/libpersona( 7647): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=7647 uid=10117 gids={50117, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  896): Killing 6913:com.sec.android.soagent/u0a36 (adj 15): bgCount ##41
,I/art     (  318): Explicit concurrent mark sweep GC freed 8760(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 271us total 13.612ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 8.076ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 8.037ms
,I/SELinux ( 7647): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7647): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7647): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/[CarModeFW]( 7522): -[snowdeer] Rec : Schedule : 65
,I/[CarModeFW]( 7522): -[snowdeer] Rec : During DL app : 2
,I/[CarModeFW]( 7522): -[snowdeer] Rec : Location Sharing : 3
I/[CarModeFW]( 7522): -[snowdeer] Rec : POI : 0
I/[CarModeFW]( 7522): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7522): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7522): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
I/[CarModeFW]( 7522): -[snowdeer] Rec : getContactListFromHashMap : 1
D/[CarModeFW]( 7522): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 638
,I/[CarModeFW]( 7522): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7522): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7522): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 7522): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 638
,D/TimaKeyStoreProvider( 7647): TimaSignature is unavailable
,D/ActivityThread( 7647): Added TimaKeyStore provider
,D/ResourcesManager( 7647): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,W/ResourcesManager( 7647): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/MagazineService Version( 7647): Magazine-Administrator: 11
W/libprocessgroup(  896): failed to open /acct/uid_10036/pid_6913/cgroup.procs: No such file or directory
,D/MagazineService Version( 7647): Magazine-Provider: 14
,D/MagazineService Version( 7647): Magazine-Channel: 14
,D/HeadlinesChannelApplication( 7647): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 7647): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,I/MagazineService::MagazineService( 7647): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,E/Zygote  ( 7665): MountEmulatedStorage()
E/Zygote  ( 7665): v2
I/libpersona( 7665): KNOX_SDCARD checking this for 1000
I/libpersona( 7665): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7665 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/MagazineService::MagazineService( 7647): [onHandleIntent] Send broadcast to (com.test.thalitest).
,I/SELinux ( 7665): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7665): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7665): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  896): Killing 6950:com.samsung.android.scloud.sync/u0a66 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7665): TimaSignature is unavailable
,D/ActivityThread( 7665): Added TimaKeyStore provider
,D/ResourcesManager( 7665): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/libprocessgroup(  896): failed to open /acct/uid_10066/pid_6950/cgroup.procs: No such file or directory
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7680): MountEmulatedStorage()
E/Zygote  ( 7680): v2
I/libpersona( 7680): KNOX_SDCARD checking this for 1000
I/libpersona( 7680): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7680 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 6972:com.sec.android.widgetapp.ap.hero.accuweather/u0a70 (adj 15): bgCount ##41
,I/System.out( 7546): INFO:Resource not found:/Common.properties Using default values
,I/SELinux ( 7680): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7680): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7680): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7680): TimaSignature is unavailable
,D/ActivityThread( 7680): Added TimaKeyStore provider
,D/ResourcesManager( 7680): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,W/libprocessgroup(  896): failed to open /acct/uid_10070/pid_6972/cgroup.procs: No such file or directory
,D/AcmsPackageEventListener( 7680): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 7680): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/AcmsService( 7680): Enter Oncreate
,D/AcmsServiceMonitor( 7680): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 7680): creating AcmsCore
D/AcmsCore( 7680): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 7680): AcmsCore
,D/AcmsCore( 7680): init
D/AcmsCore( 7680): Looper handler is not null
D/AcmsCore( 7680): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7680): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7680): Incrementing - Counter value: 1
D/AcmsCore( 7680): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsCertificateMngr( 7680): AcmsCertificateMngr
D/AcmsService( 7680): onStartCommand
D/AcmsService( 7680): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 7680): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 7680): Incrementing - Counter value: 2
D/AcmsService( 7680): Incremented Counter Value : onStartCommand
D/AcmsRevocationMngr( 7680): AcmsRevocationMngr
,D/ActivityThread( 7680): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsService( 7680): Inside handle Intent
D/AcmsService( 7680): App added - package name: com.test.thalitest
D/AcmsCore( 7680): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7680): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7680): Incrementing - Counter value: 3
D/AcmsCore( 7680): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 7680): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 7680): Decrementing - Counter value: 2
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7700): MountEmulatedStorage()
E/Zygote  ( 7700): v2
I/libpersona( 7700): KNOX_SDCARD checking this for 10165
I/libpersona( 7700): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=7700 uid=10165 gids={50165, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7700): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7700): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7700): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7700): TimaSignature is unavailable
,D/ActivityThread( 7700): Added TimaKeyStore provider
,I/jxcore-log( 7445): JXcore Cordova bridge is ready!
I/jxcore-log( 7445): 
,W/jxcore-log( 7445): JXcore engine is started
,D/ResourcesManager( 7700): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,W/ResourcesManager( 7700): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/KidsPlatformStub( 7700): Package not found : com.sec.android.app.kidshome
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7715): MountEmulatedStorage()
I/libpersona( 7715): KNOX_SDCARD checking this for 10169
E/Zygote  ( 7715): v2
I/libpersona( 7715): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7715 uid=10169 gids={50169, 9997, 1023} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 6996:com.sec.android.app.clockpackage/u0a90 (adj 15): bgCount ##41
,I/SELinux ( 7715): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7715): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7715): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7715): TimaSignature is unavailable
,D/ActivityThread( 7715): Added TimaKeyStore provider
,D/ResourcesManager( 7715): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/SQLiteLog( 7715): (284) automatic index on shooting_modes(title_id)
,W/libprocessgroup(  896): failed to open /acct/uid_10090/pid_6996/cgroup.procs: No such file or directory
,D/Finsky  ( 6508): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/PackageBroadcastService( 2470): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/ActivityManager(  896): Killing 7011:com.sec.esdk.elm/u0a103 (adj 15): bgCount ##41
,D/ChimeraCfgMgr( 2470): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2470): Loading module APK com.google.android.play.games
,D/ResourcesManager( 2470): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,W/libprocessgroup(  896): failed to open /acct/uid_10103/pid_7011/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2470): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2470): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2470): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 2470): Submit a task: k
,D/ChimeraCfgMgr( 2470): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 2470): Loading module com.google.android.gms.vision from APK com.google.android.gms
,W/BaseAppContext( 2470): Using Auth Proxy for data requests.
,W/BaseAppContext( 2470): Using Auth Proxy for data requests.
,D/k       ( 2470): Processing package: com.test.thalitest
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,D/GassUtils( 2470): Found app info for package com.test.thalitest:18. Hash: 8d179c3391de64cb252217b95c8671d16c87cb117668119dbcd10fd1a66cc302
D/k       ( 2470): Found info for package com.test.thalitest in db.
,E/Zygote  ( 7740): MountEmulatedStorage()
E/Zygote  ( 7740): v2
I/libpersona( 7740): KNOX_SDCARD checking this for 10039
I/libpersona( 7740): KNOX_SDCARD not a persona
,E/SMD     (  294): DCD ON
,I/ActivityManager(  896): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7740 uid=10039 gids={50039, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7740): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7740): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7740): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7740): TimaSignature is unavailable
,D/ActivityThread( 7740): Added TimaKeyStore provider
,W/BaseAppContext( 2470): Using Auth Proxy for data requests.
,D/ResourcesManager( 7740): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,W/BaseAppContext( 2470): Using Auth Proxy for data requests.
,W/BaseAppContext( 2470): Using Auth Proxy for data requests.
,W/BaseAppContext( 2470): Using Auth Proxy for data requests.
,D/AcmsKeyStoreHelper( 7680):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 7680): Key Store exist
I/AcmsKeyStoreHelper( 7680): Hence loading the keystore file
,I/ActivityManager(  896): Killing 6008:com.sec.android.GeoLookout/u0a112 (adj 15): bgCount ##41
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BootupListener( 1485): ACTION_DRIVELINK
,D/SettingsProvider(  896): name = drivelink_navigation
D/SettingsProvider(  896): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  896): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  896): selectionArgs: false
D/SettingsProvider(  896): selectionArgs: 1001
D/SecContentProvider(  896): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  896): ret = -1
D/BootupListener( 1485): NAVI : com.google.android.apps.maps
D/SettingsProvider(  896): name = internet_call_settings_visibility
D/SettingsProvider(  896): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  896): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  896): selectionArgs: false
D/SettingsProvider(  896): selectionArgs: 1001
D/SecContentProvider(  896): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  896): ret = -1
,D/SecurityLogAgent( 7030):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7030):  SeDenialReceiver : File path = null
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 2248): Vacuum at: now=1449756746539 tag=VacuumService
,W/libprocessgroup(  896): failed to open /acct/uid_10112/pid_6008/cgroup.procs: No such file or directory
,V/GLSActivity( 2248): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AcmsKeyStoreHelper( 7680):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 7680): getKeyStoreForApplication success 
D/AcmsCore( 7680): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 7680): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7680): Decrementing - Counter value: 1
D/AcmsCore( 7680): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 7680): This is NOT a valid MirrorLink app
D/AcmsCore( 7680): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 7680): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7680): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 7680): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 7680): getSvcCounter - Counter value: 0
D/AcmsService( 7680): Enter onDestroy
I/AcmsService( 7680): cleanUp(): inside service clean up
D/AcmsCore( 7680): AcmsCore: inside DeInit
D/AcmsCore( 7680): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 7680): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 7680): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 7680): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 7680): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 7680): getSvcCounter - Counter value: 0
D/AcmsService( 7680): killing acms process
I/Process ( 7680): Sending signal. PID: 7680 SIG: 9
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  896): Process ACMS.Process (pid 7680)(adj 0) has died(75,571)
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/jxcore-log( 7445): Toggling radios to true
I/jxcore-log( 7445): 
,D/BluetoothAdapter( 7445): enable()
,D/BluetoothAdapter( 7445): enable(): BT is already enabled..!
,D/WifiService(  896): New client listening to asynchronous messages
,I/WifiManager( 7445): packageName : com.test.thalitest
,D/SecContentProvider(  896): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  896): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  896): mCursor = null
,D/WifiService(  896): setWifiEnabled: true pid=7445, uid=10356
,E/WifiService(  896): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  896): Permission Denial: getCurrentUser() from pid=7445, uid=10356 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  896): Failed getting userId using ActivityManagerNative
W/WifiService(  896): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7445, uid=10356 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  896): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  896): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2122)
W/WifiService(  896): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2110)
W/WifiService(  896): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  896): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  896): name = wifi_on
,I/WifiService(  896): disconnect: pid=7445, uid=10356
,I/jxcore-log( 7445): Radios toggled
I/jxcore-log( 7445): 
,I/wpa_supplicant( 1306): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7445): Got Device Bluetooth address: 7C:F9:0E:34:8A:A0
I/jxcore-log( 7445): 
,I/jxcore-log( 7445): Perf Test app loaded loaded
I/jxcore-log( 7445): 
,I/jxcore-log( 7445): check test folder
I/jxcore-log( 7445): 
,I/jxcore-log( 7445): found test : ./testFindPeers.js
I/jxcore-log( 7445): 
,I/wpa_supplicant( 1306): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1306): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1306): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1306): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  896): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1306): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1306): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1306): Disconnected - do not scan
I/wpa_supplicant( 1306): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  896): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
,E/WifiStateMachine(  896): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  896): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  896): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/PhenotypeConfigurator( 2248): Scheduling Phenotype for one-off execution 2817 seconds from now (1449756746935)
,I/jxcore-log( 7445): found test : ./testSendData.js
I/jxcore-log( 7445): 
,E/WifiStateMachine(  896): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  896): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  896): do suspend true
,D/WifiP2pService(  896): InactiveState{ what=143375 }
D/WifiP2pService(  896): P2pEnabledState{ what=143375 }
,D/CommandListener(  289): Clearing all IP addresses on wlan0
,D/GetConfigurationSnapshotOperation( 2248): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,E/WifiStateMachine(  896): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  896): updateNetworkInfo()
D/ConnectivityService(  896): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  896): updateNetworkInfo()
D/ConnectivityService(  896): ignoring duplicate network state non-change
,E/WifiConfigStore(  896): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller(  896): evaluateTrafficStatsPolling
D/ConnectivityService(  896): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,I/CLocInfoService(  896): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  896): Start Disconnecting Watchdog 1
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
I/wpa_supplicant( 1306): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1306): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1306): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1306): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1306): First Scan Start
,I/wpa_supplicant( 1306): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine(  896): ConnectModeState: Network connection lost 
D/StatusBar.NetworkController( 1180): applyOpen
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
E/WifiStateMachine(  896): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
E/WifiStateMachine(  896): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  896): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  896): do suspend true
,D/WifiP2pService(  896): InactiveState{ what=143375 }
,D/WifiP2pService(  896): P2pEnabledState{ what=143375 }
,V/NativeCrypto( 2248): Read error: ssl=0xaf68be00: I/O error during system call, Connection timed out
,V/NativeCrypto( 2248): SSL shutdown failed: ssl=0xaf68be00: I/O error during system call, Broken pipe
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  896): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  896): DefaultState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  896): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  896): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  896): Validated
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/Hs20UtilService( 1300): Starting #6
,I/PhenotypeFlagCommitter( 2248): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Hs20UtilService( 1300): Message received 5007
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GoogleURLConnFactory( 2248): Using platform SSLCertificateSocketFactory
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1300): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1300): MountReceiver.mPrefHandler - 7002
,D/ChimeraCfgMgr( 2470): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2470): Module APK com.google.android.play.games already loaded
,D/CommandListener(  289): Clearing all IP addresses on wlan0
,D/ConnectivityService(  896): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  896): calling update connectivity
D/ConnectivityService(  896):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  896):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine(  896): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/EntConnectivity(  896): Not allowed due to - mEnabled false
D/ConnectivityService(  896): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  896):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  896): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Nat464Xlat(  896): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  896): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  896): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  896): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524292
,D/ConnectivityService(  896): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiStateMachine(  896): updateConfiguredNetworkExpiration - currTime: 1449756747063
D/WifiStateMachine(  896): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,D/ConnectivityService(  896): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  896): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  896): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/WifiNetworkAgent(  896): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityManager.CallbackHandler( 2470): CM callback handler got msg 524292
D/TelephonyNetworkFactory( 1485): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine(  896): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  896): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/CSLegacyTypeTracker(  896): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  896): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
E/WifiStateMachine(  896): setDetailed state send new extra info"NG700"
D/ConnectivityService(  896): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  896): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SecContentProvider2(  896): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  896): mCursor = null
,I/WifiTrafficPoller(  896): evaluateTrafficStatsPolling
,I/CLocInfoService(  896): External Intent Received android.net.wifi.STATE_CHANGE
,D/SecContentProvider2(  896): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  896): mCursor = null
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/SmartBondingService(  896): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  896): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  896): getSBEnabled() enabled =false
D/SmartBondingService(  896): getSBEnabled() enabled =false
D/SmartBondingService(  896): getSBEnabled() enabled =false
,V/NetworkStats(  896): updateIfacesLocked()
D/NtpTrustedTime(  896): currentTimeMillis() cache hit
V/NetworkStats(  896): performPollLocked(flags=0x1)
,E/ConnectivityService(  896): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/NetworkStatsFactory(  896): UpdateStatsForKnox
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): 0
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1180): updateDataNetType()
D/StatusBar.NetworkController( 1180): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1180): updateLTEICONDataNetType:0
,D/NtpTrustedTime(  896): currentTimeMillis() cache hit
D/NtpTrustedTime(  896): currentTimeMillis() cache hit
D/NtpTrustedTime(  896): currentTimeMillis() cache hit
,V/NetworkStats(  896): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  896): currentTimeMillis() cache hit
,D/SmartBondingService(  896): getNetworkEnabled : wifi : true mobile : true
,D/StatusBar.NetworkController( 1180): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,V/NetworkStats(  896): performPollLocked() took 9ms
D/NtpTrustedTime(  896): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
,D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
,I/Hs20UtilService( 1300): Starting #7
,I/Hs20UtilService( 1300): Message received 5007
D/NtpTrustedTime(  896): currentTimeMillis() cache hit
D/NtpTrustedTime(  896): currentTimeMillis() cache hit
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1300): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1300): MountReceiver.mPrefHandler - 7002
,I/chromium( 7445): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/FileWriteThread_Telephony( 1485): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1485): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1485): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1485): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1485): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1485): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1485): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1485): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1485): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1485): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1485): FileWriteThread : threadType = 3
V/AlarmManager(  896): waitForAlarm result :4
D/FileWriteThread_Telephony( 1485): FileWriteThread : threadType = 3
D/KeyguardViewMediator( 1180): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
D/PersonaManager( 1180): isKioskContainerExistOnDevice
D/FileWriteThread_Telephony( 1485): FileWriteThread : threadType = 3
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/KeyguardViewMediator( 1180): doKeyguard: not showing because lockscreen is off
D/FileWriteThread_Telephony( 1485): FileWriteThread : threadType = 3
,I/chromium( 7445): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/LocationManagerService(  896): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/Uploader( 2248): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/LocationManagerService(  896): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/Uploader( 2248): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/chromium( 7445): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7445): 
,I/Icing   ( 2470): Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,D/ResourcesManager( 2470): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/Icing   ( 2470): Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,D/ConnectivityService(  896): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  896): updateDataUsageMap
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  896): MasterInitialState.processMessage what=3
D/SmartBondingService(  896): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  896): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  896): getSBEnabled() enabled =false
D/SmartBondingService(  896): getSBEnabled() enabled =false
D/SmartBondingService(  896): getSBEnabled() enabled =false
,D/SmartBondingService(  896): getNetworkEnabled : wifi : true mobile : true
,I/CLocInfoService(  896): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  896): CLoinfo wifi false
,D/accuweather( 2067): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,W/SLocation(  896): No Active Data Connection
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 7279): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7279): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 7279): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7279): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7279): noConnectivity : true
I/DBG_DM  ( 3705): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3705): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/Zygote  ( 7809): MountEmulatedStorage()
,E/Zygote  ( 7809): v2
I/libpersona( 7809): KNOX_SDCARD checking this for 10125
I/libpersona( 7809): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=7809 uid=10125 gids={50125, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SELinux ( 7809): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/PowerManagerService(  896): [PWL] Off : 5s ago
I/SELinux ( 7809): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/PowerManagerService(  896): [PWL]   PowerManagerService.WakeLocks: ref count=1
E/SELinux ( 7809): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/PowerManagerService(  896): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  896): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=896, ws=null) (elapsedTime=592)
I/PowerManagerService(  896): [PWL]       PARTIAL_WAKE_LOCK              'GpsLocationProvider' (uid=1000, pid=896, ws=null) (elapsedTime=45)
,D/TimaKeyStoreProvider( 7809): TimaSignature is unavailable
,D/ActivityThread( 7809): Added TimaKeyStore provider
,D/ResourcesManager( 7809): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore( 7809): Database version: 104
,D/ResourcesManager( 7809): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7809): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7809): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7809): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7809): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7809): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2d190e7c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7809): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7809): GMSCore installation verified
,I/ConfigStore( 7809): Config Database version: 1
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7809): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7809): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7809): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter(  896): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter(  896): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/AudioPolicyManager(  299): getOutputsForDevice device 0002 -> 0002
,I/AudioService(  896): getStreamVolume 3 index 0
,I/MediaRouter( 7809): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/FactoryTest( 6595): Not factory mode
,D/FactoryTest( 6595): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6595): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6595): still no open session command from host, so toast
,W/ContextImpl( 6595): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6595): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
I/Timeline( 6595): Timeline: Activity_launch_request id:com.android.settings time:111453
,E/PersonaManagerService(  896): inState():  stateMachine is null !!
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  896): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  896): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,E/MTPRx   ( 6595): started activity for popup
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,I/SQLiteSecureOpenHelper( 3486): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3486): getDatabaseLocked(b,b,pwd)...
,I/wpa_supplicant( 1306): nl80211: Received scan results (3 BSSes)
,I/wpa_supplicant( 1306): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1306): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 1306): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1306): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,E/Zygote  ( 7848): MountEmulatedStorage()
,E/Zygote  ( 7848): v2
I/libpersona( 7848): KNOX_SDCARD checking this for 10002
I/libpersona( 7848): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7848 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/WifiStateMachine(  896): [1,449,756,748,099 ms] noteScanEnd no scan source
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  896): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3d9228d6 sup_state=SCANNING debouncing=false
,I/SELinux ( 7848): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7848): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7848): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine(  896): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  896): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  896): setDetailed state send new extra info0x
D/SecContentProvider2(  896): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  896): mCursor = null
,I/CLocInfoService(  896): External Intent Received android.net.wifi.SCAN_RESULTS
,D/WifiDisplayAdapter(  896): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7809): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider( 7848): TimaSignature is unavailable
,D/ActivityThread( 7848): Added TimaKeyStore provider
,I/ActivityManager(  896): Killing 5689:com.sec.android.widgetapp.SPlannerAppWidget/u0a148 (adj 15): bgCount ##41
,D/ResourcesManager( 6595): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6595): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6595): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6595): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6595): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6595): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6595): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6595): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 7848): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,E/SettingsReceiverActivity( 6595): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/InputMethodManagerService(  896): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/wpa_supplicant( 1306): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 1306): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1306): Associated with C0.AA.48
,E/WifiStateMachine(  896): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  896): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,W/InputMethodManagerService(  896): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3ecf5f1f attribute=null, token = android.os.BinderProxy@53f3d6d
,D/SecContentProvider2(  896): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  896): mCursor = null
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,W/libprocessgroup(  896): failed to open /acct/uid_10148/pid_5689/cgroup.procs: No such file or directory
,I/wpa_supplicant( 1306): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1306): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  896): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  896): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  896): setDetailed state send new extra info"NG700"
V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/SecContentProvider2(  896): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  896): mCursor = null
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,I/wpa_supplicant( 1306): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,I/wpa_supplicant( 1306): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1306): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
E/WifiStateMachine(  896): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  896): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
I/wpa_supplicant( 1306): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1306): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,I/wpa_supplicant( 1306): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1306): Blacklist: Clear (temp) 
I/wpa_supplicant( 1306): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,D/SecContentProvider2(  896): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  896): mCursor = null
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,E/WifiStateMachine(  896): Network connection established
,D/WifiNative-HAL(  896): callSECApiVoid - ID [50]
V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
E/WifiStateMachine(  896): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,E/WifiStateMachine(  896): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,I/CLocInfoService(  896): External Intent Received android.net.wifi.STATE_CHANGE
V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
D/ConnectivityService(  896): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  896): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  896): Got NetworkAgent Messenger
V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
D/ConnectivityService(  896): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  896): updateNetworkInfo()
,D/ConnectivityService(  896): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  896): NetworkAgent connected
V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
E/WifiStateMachine(  896): L2ConnectedState "NG700" nid=0
,E/WifiConfigStore(  896): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,E/WifiStateMachine(  896): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  896): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  896): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  896): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6595): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6595): dev.kiessupport is : TRUE
,D/CommandListener(  289): Setting iface cfg
,E/WifiStateMachine(  896): Start Dhcp Watchdog 2
,I/ActivityManager(  896): Killing 4605:com.android.calendar/u0a149 (adj 15): bgCount ##41
,E/WifiStateMachine(  896): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  896): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  896): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,D/Activity( 6595): performCreate Call secproduct feature valuefalse
,D/Activity( 6595): performCreate Call debug elastic valuetrue
,E/Zygote  ( 7873): MountEmulatedStorage()
E/Zygote  ( 7873): v2
I/libpersona( 7873): KNOX_SDCARD checking this for 1000
I/libpersona( 7873): KNOX_SDCARD not a persona
,I/art     (  896): Explicit concurrent mark sweep GC freed 52909(2MB) AllocSpace objects, 1(16KB) LOS objects, 30% free, 35MB/51MB, paused 2.723ms total 142.299ms
,I/ActivityManager(  896): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7873 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7873): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7873): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7873): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/ActivityManager(  896): post active user change for 0
D/KnoxTimeoutHandler(  896): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  896): handleActiveUserChange for user 0
,W/libprocessgroup(  896): failed to open /acct/uid_10149/pid_4605/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7873): TimaSignature is unavailable
,D/ActivityThread( 7873): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/ResourcesManager( 7873): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/Timeline( 7445): Timeline: Activity_idle id: android.os.BinderProxy@16b0edb5 time:111747
,E/WifiStateMachine(  896): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  896): do suspend false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/SecContentProvider2(  896): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  896): mCursor = null
D/WifiP2pService(  896): InactiveState{ what=143375 }
D/WifiP2pService(  896): P2pEnabledState{ what=143375 }
,I/DIAGMON_AGENT( 7873): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7873): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7873): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7873): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7873): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7873): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7896): MountEmulatedStorage()
,E/Zygote  ( 7896): v2
I/libpersona( 7896): KNOX_SDCARD checking this for 10010
I/libpersona( 7896): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7896 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7896): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7896): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7896): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/dhcpcd  ( 7904): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/TimaKeyStoreProvider( 7896): TimaSignature is unavailable
,D/ActivityThread( 7896): Added TimaKeyStore provider
,I/dhcpcd  ( 7904): version 5.5.6 starting
,E/dhcpcd  ( 7904): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/ResourcesManager( 7896): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager(  896): Killing 7046:com.sec.android.app.taskmanager/u0a175 (adj 15): bgCount ##41
,I/FOTA_Client( 7896): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7896): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/dhcpcd  ( 7904): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7904): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7904): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7904): bssid match
,I/dhcpcd  ( 7904): wlan0: rebinding lease of 192.168.1.136
,I/FOTA_Client( 7896): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7921): MountEmulatedStorage()
E/Zygote  ( 7921): v2
I/libpersona( 7921): KNOX_SDCARD checking this for 10018
I/libpersona( 7921): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7921 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 7061:com.qualcomm.timeservice/1000 (adj 15): bgCount ##41
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7921): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7921): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7921): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7921): TimaSignature is unavailable
,D/ActivityThread( 7921): Added TimaKeyStore provider
,D/ResourcesManager( 7921): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,W/libprocessgroup(  896): failed to open /acct/uid_10175/pid_7046/cgroup.procs: No such file or directory
,W/libprocessgroup(  896): failed to open /acct/uid_1000/pid_7061/cgroup.procs: No such file or directory
,I/KLMS-2.4.503: ( 7921): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7921): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449756748728
,I/KLMS-2.4.503: ( 7921): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7921): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7921): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  896): Killing 6123:com.android.providers.calendar/u0a45 (adj 15): bgCount ##41
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7936): MountEmulatedStorage()
I/libpersona( 7936): KNOX_SDCARD checking this for 10036
E/Zygote  ( 7936): v2
I/libpersona( 7936): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7936 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/art     (  318): Explicit concurrent mark sweep GC freed 8731(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 275us total 12.306ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.507ms
,I/SELinux ( 7936): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7936): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7936): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 260us total 9.099ms
,D/TimaKeyStoreProvider( 7936): TimaSignature is unavailable
,D/ActivityThread( 7936): Added TimaKeyStore provider
,W/libprocessgroup(  896): failed to open /acct/uid_10045/pid_6123/cgroup.procs: No such file or directory
,D/ResourcesManager( 7936): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7936): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7316): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6929): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 6929): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6929): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 6929): [SLFUCHKMGR] constructor called
,I/SA      ( 6929): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6929): [OR] == isSIMCardReady false ==
,I/SA      ( 6929): [SCU] == networkStateCheck == false
,I/SA      ( 6929): [OR] onReceive END
,E/SPPClientService( 7316): [[SystemStateMonitorService]] No Active Internet
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7954): MountEmulatedStorage()
E/Zygote  ( 7954): v2
I/libpersona( 7954): KNOX_SDCARD checking this for 10070
I/libpersona( 7954): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7954 uid=10070 gids={50070, 9997, 3003, 1028} abi=armeabi-v7a
,I/dhcpcd  ( 7904): wlan0: acknowledged 192.168.1.136 from 192.168.1.1
,I/SELinux ( 7954): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7954): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/ActivityManager(  896): Killing 7136:com.sec.enterprise.knox.cloudmdm.smdms/u0a178 (adj 15): bgCount ##41
E/SELinux ( 7954): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7954): TimaSignature is unavailable
,D/ActivityThread( 7954): Added TimaKeyStore provider
,I/dhcpcd  ( 7904): wlan0: leased 192.168.1.136 for 86400 seconds
,E/WifiStateMachine(  896): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  896): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  896): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/ResourcesManager( 7954): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7954): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7954): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7954): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/GAV2    ( 7461): Thread[GAThread,5,main]: No campaign data found.
,D/comsamsunglog( 7954): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7954): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7954): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7954): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7954): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7954): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7954): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7954): [KK AccuPhone]>>> ==============================================================================================
,W/libprocessgroup(  896): failed to open /acct/uid_10178/pid_7136/cgroup.procs: No such file or directory
,D/SettingsProvider(  896): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  896): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  896): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  896): selectionArgs: false
D/SettingsProvider(  896): selectionArgs: 10070
D/SecContentProvider(  896): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  896): ret = -1
,D/daemonapp( 1350): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7954): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7954): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7954): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7954): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
D/accuweather( 7954): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 7954): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1350): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7954): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1350): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7954): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1350): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7954): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7954): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro( 6452): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 6452): premStatus:2
,I/KnoxUsageLogPro( 6452): isEulaShown : false
,I/KnoxUsageLogPro( 6452): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7993): MountEmulatedStorage()
E/Zygote  ( 7993): v2
I/libpersona( 7993): KNOX_SDCARD checking this for 10087
I/libpersona( 7993): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7993 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 6424:com.samsung.android.app.FileShareServer/u0a74 (adj 15): bgCount ##41
,I/SELinux ( 7993): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7993): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7993): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7993): TimaSignature is unavailable
,D/ActivityThread( 7993): Added TimaKeyStore provider
,D/ResourcesManager( 7993): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  896): failed to open /acct/uid_10074/pid_6424/cgroup.procs: No such file or directory
,E/WifiStateMachine(  896): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  896): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/native  (  896): do suspend true
,D/WifiP2pService(  896): InactiveState{ what=143375 }
D/WifiP2pService(  896): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  896): WifiStateMachine DHCP successful
,E/SMD     (  294): DCD ON
,E/WifiStateMachine(  896): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  896): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  896): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  896): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  896): Not connected state, yet.
E/WifiStateMachine(  896): VerifyingLinkState enter
,D/WifiStateMachine(  896): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  896): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  896): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  896): callSECApiInt - ID [210]
,E/WifiStateMachine(  896): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  896): updateNetworkInfo()
,D/ConnectivityService(  896): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  896): Adding iface wlan0 to network 503
,I/CLocInfoService(  896): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  896): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  896): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  896): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  896): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  896): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  896): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine(  896): Now, connected state.
E/WifiStateMachine(  896): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,D/ConnectivityService(  896): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  896): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
I/WifiTrafficPoller(  896): evaluateTrafficStatsPolling
,D/ConnectivityService(  896): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  896): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  896): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  896): updateSourceRoutes : add src route for:192.168.1.136
V/        (  289): QcRouteController
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
I/CLocInfoService(  896): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  896): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  896): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  896): mBoosterFLAG : 0
I/WifiTrafficPoller(  896): current booster mode : FullMode
,D/WifiNative-HAL(  896): callSECApiVoid - ID [212]
,I/CLocInfoService(  896): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  896): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,V/        (  289): QcRouteController
,E/WifiStateMachine(  896): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
I/WifiStateMachine(  896): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 1180): applyOpen
,D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
,D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
I/ActivityManager(  896): Killing 6492:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,D/Headlines( 5434): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5434): getCountryCode(): countryCode = PL
,D/Headlines( 5434): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5434): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5434): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5434): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5434): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5434): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5434): requestUpdateNewsWelcomeCard !!! no welcome card
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,V/        (  289): QcRouteController
,E/Zygote  ( 8021): MountEmulatedStorage()
E/Zygote  ( 8021): v2
I/libpersona( 8021): KNOX_SDCARD checking this for 10127
I/libpersona( 8021): KNOX_SDCARD not a persona
I/ActivityManager(  896): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8021 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/        (  289): QcRouteController
,V/        (  289): QcRouteController
,I/SELinux ( 8021): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,V/        (  289): QcRouteController
,I/SELinux ( 8021): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,V/        (  289): QcRouteController
,E/SELinux ( 8021): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  896): failed to open /acct/uid_1000/pid_6492/cgroup.procs: No such file or directory
,V/        (  289): QcRouteController
,D/TimaKeyStoreProvider( 8021): TimaSignature is unavailable
,D/ActivityThread( 8021): Added TimaKeyStore provider
,D/ConnectivityService(  896): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  896): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  896): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  896): updateNetworkInfo()
D/ConnectivityService(  896): calling update connectivity
E/ConnectivityService(  896): updateNetworkInfo()
D/ConnectivityService(  896): ignoring duplicate network state non-change
D/ConnectivityService(  896): ignoring duplicate network state non-change
D/ConnectivityService(  896): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  896): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  896): calling update connectivity
D/ConnectivityService(  896): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  896):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  896):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  896):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  896): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  896):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  896): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  896): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  896): Validated
,D/ResourcesManager( 8021): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ConnectivityService(  896): currentScore = 0, newScore = 60
D/ConnectivityService(  896):    accepting network in place of null
D/ConnectivityService(  896): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1485): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  896): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  896): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  896): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  896): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  896): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  896): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
V/NetworkStats(  896): updateIfacesLocked()
D/NtpTrustedTime(  896): currentTimeMillis() cache hit
V/NetworkStats(  896): performPollLocked(flags=0x1)
,D/SmartBondingService(  896): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  896): getSBEnabled() enabled =false
D/SmartBondingService(  896): getSBEnabled() enabled =false
D/NetworkStatsFactory(  896): UpdateStatsForKnox
D/SmartBondingService(  896): getSBEnabled() enabled =false
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1180): updateDataNetType()
D/StatusBar.NetworkController( 1180): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1180): updateLTEICONDataNetType:0
,D/SmartBondingService(  896): getNetworkEnabled : wifi : true mobile : true
V/NetworkStats(  896): performPollLocked() took 4ms
D/NtpTrustedTime(  896): currentTimeMillis() cache hit
D/NtpTrustedTime(  896): currentTimeMillis() cache hit
,D/NtpTrustedTime(  896): currentTimeMillis() cache hit
D/NtpTrustedTime(  896): currentTimeMillis() cache hit
D/NtpTrustedTime(  896): currentTimeMillis() cache hit
V/NetworkStats(  896): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 1180): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/EntConnectivity(  896): Not allowed due to - mEnabled false
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/ConnectivityService(  896): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  896): calling update connectivity
D/NtpTrustedTime(  896): currentTimeMillis() cache hit
D/NtpTrustedTime(  896): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): applyOpen
D/ConnectivityService(  896):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  896):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/StatusBar.NetworkController( 1180): refreshSignalCluster - setNWBoosterIndicators(false)
D/ConnectivityService(  896): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/StatusBar.NetworkController( 1180): applyOpen
D/ConnectivityService(  896):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  896): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524290
D/ConnectivityService(  896): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  896): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  896):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  896):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  896):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  896): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  896): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  896): calling update connectivity
,D/ConnectivityManager.CallbackHandler( 2470): CM callback handler got msg 524290
D/ConnectivityService(  896):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  896):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  896): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524290
D/ConnectivityService(  896):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
D/ConnectivityService(  896): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  896): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 2470): CM callback handler got msg 524290
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1180): updateDataNetType()
D/StatusBar.NetworkController( 1180): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1180): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1180): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8021): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8021): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8021): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8021): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WebViewFactory( 8021): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 8021): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 8021): Loading: webviewchromium
,I/LibraryLoader( 8021): Time to load native libraries: 4 ms (timestamps 2974-2978)
,I/LibraryLoader( 8021): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8021): Binding Chromium to main looper Looper (main, tid 1) {9fa5726}
,I/LibraryLoader( 8021): Expected native library version number "",actual native library version number ""
,I/chromium( 8021): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8021): Initializing chromium process, renderers=0
,W/art     ( 8021): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 8021): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 8021): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,W/AudioManagerAndroid( 8021): Requires BLUETOOTH permission
I/chromium( 8021): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/Adreno-EGL( 8021): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 8021): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8021): Build Date: 03/03/15 Tue
I/Adreno-EGL( 8021): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 8021): Remote Branch: 
I/Adreno-EGL( 8021): Local Patches: 
I/Adreno-EGL( 8021): Reconstruct Branch: 
,I/NSApplication( 8021): Starting up...
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8092): MountEmulatedStorage()
,E/Zygote  ( 8092): v2
I/libpersona( 8092): KNOX_SDCARD checking this for 10137
I/libpersona( 8092): KNOX_SDCARD not a persona
I/ActivityManager(  896): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=8092 uid=10137 gids={50137, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 7243:com.google.android.partnersetup/u0a14 (adj 15): bgCount ##41
,I/SELinux ( 8092): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8092): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8092): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8092): TimaSignature is unavailable
,D/ActivityThread( 8092): Added TimaKeyStore provider
,W/libprocessgroup(  896): failed to open /acct/uid_10014/pid_7243/cgroup.procs: No such file or directory
,D/ResourcesManager( 8092): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 8092): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8092): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8092): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 8092): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  896): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect( 8092): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  896): MasterInitialState.processMessage what=3
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/QuickConnect( 8092): PeriphStartReceiver.onReceive - no need to start
,D/SmartBondingService(  896): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  896): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  896): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  896): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  896): CLocinfo wifi true 
D/SmartBondingService(  896): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  896): getSBEnabled() enabled =false
D/SmartBondingService(  896): getSBEnabled() enabled =false
D/SmartBondingService(  896): getSBEnabled() enabled =false
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  896): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2272): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
W/ContextImpl( 2272): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/accuweather( 2067): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3705): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3705): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,I/NetworkMonitor( 7809): type=WIFI subType= reason=null isConnected=true
,E/Zygote  ( 8109): MountEmulatedStorage()
I/libpersona( 8109): KNOX_SDCARD checking this for 10162
E/Zygote  ( 8109): v2
I/libpersona( 8109): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=8109 uid=10162 gids={50162, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 7264:com.samsung.groupcast/u0a15 (adj 15): bgCount ##41
,I/SELinux ( 8109): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8109): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8109): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2(  896): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  896): mCursor = null
,D/TimaKeyStoreProvider( 8109): TimaSignature is unavailable
W/libprocessgroup(  896): failed to open /acct/uid_10015/pid_7264/cgroup.procs: No such file or directory
,D/ActivityThread( 8109): Added TimaKeyStore provider
,D/ResourcesManager( 8109): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8109): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8109): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8109): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8109): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManagerService(  896): exchangeData() failure , invalid userId
,D/RCPManagerService(  896): exchangeData() failure , invalid userId
,D/RCPManagerService(  896): exchangeData() failure , invalid userId
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  896): exchangeData() failure , invalid userId
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,E/Zygote  ( 8138): MountEmulatedStorage()
E/Zygote  ( 8138): v2
I/libpersona( 8138): KNOX_SDCARD checking this for 10077
I/libpersona( 8138): KNOX_SDCARD not a persona
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,I/ActivityManager(  896): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8138 uid=10077 gids={50077, 9997} abi=armeabi-v7a
V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,I/SELinux ( 8138): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
I/SELinux ( 8138): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,E/SELinux ( 8138): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,D/RCPManagerService(  896): exchangeData() failure , invalid userId
V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/RCPManagerService(  896): exchangeData() failure , invalid userId
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,D/TimaKeyStoreProvider( 8138): TimaSignature is unavailable
,D/ActivityThread( 8138): Added TimaKeyStore provider
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7030): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7030): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7030): StateMachine : Current State = 1
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7030): StateMachine : Changed Current State = 1
,I/ActivityManager(  896): Killing 6402:com.samsung.android.app.galaxyfinder/u0a33 (adj 15): bgCount ##41
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,I/ActivityManager(  896): Killing 4912:com.sec.android.app.shealth/u0a34 (adj 15): bgCount ##41
V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
D/ResourcesManager( 8138): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 8109): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,D/BadgeProvider( 8138): onCreate
,D/BadgeProvider( 8138): DatabaseHelper
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8153): MountEmulatedStorage()
E/Zygote  ( 8153): v2
I/libpersona( 8153): KNOX_SDCARD checking this for 10177
I/libpersona( 8153): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8153 uid=10177 gids={50177, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8153): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/BadgeProvider( 8138): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/SELinux ( 8153): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8153): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 8138): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8138): sendNotify, [notify] : null
D/BadgeProvider( 8138): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8138): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 8138): update, [UpdateCount] : 1
,D/Launcher.Model( 1499): reloadBadges entered.
,D/TimaKeyStoreProvider( 8153): TimaSignature is unavailable
,D/ActivityThread( 8153): Added TimaKeyStore provider
,W/libprocessgroup(  896): failed to open /acct/uid_10033/pid_6402/cgroup.procs: No such file or directory
,W/libprocessgroup(  896): failed to open /acct/uid_10034/pid_4912/cgroup.procs: No such file or directory
,D/ResourcesManager( 8153): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,W/ActivityManager(  896): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager(  896): Killing 7337:com.samsung.android.sdk.samsunglink/u0a41 (adj 15): bgCount ##41
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7740): notifyNetworkActivated
,W/ContextImpl( 7740): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  896): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/libprocessgroup(  896): failed to open /acct/uid_10041/pid_7337/cgroup.procs: No such file or directory
,D/ConnectivityService(  896): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/hcjo    ( 7740): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7740): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7740): exit::IDLE
D/InitializeManagerStateMachine( 7740): entry::NETWORK_CHECK
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7740): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7740): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7740): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7740): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7740): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7740): entry::SUCCESS
D/hcjo    ( 7740): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 1300): Starting #8
,I/Hs20UtilService( 1300): Message received 5007
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1300): MountReceiver.onReceive - Keep current state
,D/hcjo    ( 7740): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7740): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7740): exit::SUCCESS
I/Hs20UtilService( 1300): Starting #9
D/InitializeManagerStateMachine( 7740): entry::IDLE
,I/Hs20UtilService( 1300): Message received 5007
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1300): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1300): Starting #10
,I/Hs20UtilService( 1300): Message received 5007
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1300): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1300): Starting #11
,I/Hs20UtilService( 1300): Message received 5007
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1300): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  896): callSECApi what=220
,D/WifiStateMachine(  896): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 7279): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7279): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7279): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7279): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  257): id=17 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,I/DIAGMON_AGENT( 7873): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7873): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService(  896): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=896
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,I/FOTA_Client( 7896): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,I/FOTA_Client( 7896): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7896): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.503: ( 7921): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7921): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449756750531
,I/KLMS-2.4.503: ( 7921): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7921): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7921): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7921): NetworkChangeOperations(): uploadRequestLog().START 
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,I/KLMS-2.4.503: ( 7921): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7936): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7316): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6929): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 6929): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6929): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6929): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6929): [OR] == isSIMCardReady false ==
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6929): [SCU] == networkStateCheck == true
,I/SA      ( 6929): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6929): isChinaCountryCode : false
I/SA      ( 6929): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6929): [OR] == networkStateCheck true ==
,I/SA      ( 6929): [OR] GetMyCountryZoneTask
,I/SA      ( 6929): [OR] onReceive END
,I/SA      ( 6929): [SRS] prepareGetMyCountryZone
,I/SA      ( 6929): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6929): [SSP] query invoked
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 7954): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7954): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/SA      ( 6929): [TPMU] GetMccFromDB : null
I/SA      ( 6929): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6929): [TPM] isNoProxy(default) : true
,I/KnoxUsageLogPro( 6452): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 6452): premStatus:2
,I/KnoxUsageLogPro( 6452): isEulaShown : false
I/KnoxUsageLogPro( 6452): KnoxUsageReceiver onReceive : not Processible, just return
,E/File    ( 6929): fail readDirectory() errno=2
,D/Headlines( 5434): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5434): getCountryCode(): countryCode = PL
,D/Headlines( 5434): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5434): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5434): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Headlines( 5434): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5434): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5434): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5434): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 8092): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8092): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 8092): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  896): exchangeData() failure , invalid userId
D/RCPManagerService(  896): exchangeData() failure , invalid userId
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7030): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7030): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7030): StateMachine : Current State = 1
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7030): StateMachine : Changed Current State = 1
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7740): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7740): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7740): exit::IDLE
D/InitializeManagerStateMachine( 7740): entry::NETWORK_CHECK
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7740): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7740): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7740): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 7740): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7740): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7740): entry::SUCCESS
D/hcjo    ( 7740): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7740): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7740): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7740): exit::SUCCESS
D/InitializeManagerStateMachine( 7740): entry::IDLE
,W/ActivityManager(  896): mDVFSHelper.release()
,I/SA      ( 6929): [RC New] Execute method=[GET] start
,I/SA      ( 6929): [RC New] Security=[true]
,I/System.out( 6929): Thread-1085(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6929): Thread-1085(ApacheHTTPLog):isShipBuild true
,I/System.out( 6929): Thread-1085(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/SA      ( 6929): [RC New] [v2liruge] api execute + 651
,V/AlarmManager(  896): waitForAlarm result :4
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6929): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6929): AsyncTask #1 calls detatch()
,I/SA      ( 6929): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6929): [OCP] update openData : PL
,I/SA      ( 6929): [TPMU] getNetworkMcc : 
,I/SA      ( 6929): [SCU] saveMccToPreferece Start
,I/SA      ( 6929): [SCU] RegionMCC : 260
I/SA      ( 6929): [SSP] query invoked
,I/SA      ( 6929): [TPMU] GetMccFromDB : null
,I/SA      ( 6929): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6929): [SCU] saveMccToPreferece End
,I/SA      ( 6929): [RC New] executeRequest [v2liruge] end. 713
,I/SA      ( 6929): [RC New] Execute end
I/SA      ( 6929): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6929): [OR] GetMyCountryZoneTask Success
,I/jxcore-log( 7445): BLE supported!!
I/jxcore-log( 7445): 
,E/WifiStateMachine(  896): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  896): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  896): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  896): identical MTU - not setting
,D/ConnectivityService(  896): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  896): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe63:1186
,V/        (  289): QcRouteController
,E/WifiStateMachine(  896): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/SmartBondingService(  896): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  896): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  896): getSBEnabled() enabled =false
,D/SmartBondingService(  896): getSBEnabled() enabled =false
,D/SmartBondingService(  896): getSBEnabled() enabled =false
,E/SMD     (  294): DCD ON
,V/        (  289): QcRouteController
,W/NetworkManagementService(  896): route cmd failed: 
W/NetworkManagementService(  896): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe63:1186 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  896): '
W/NetworkManagementService(  896): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  896): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  896): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  896): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  896): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  896): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  896): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  896): 	at com.android.server.ConnectivityService.access$1900(ConnectivityService.java:230)
W/NetworkManagementService(  896): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  896): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Nat464Xlat(  896): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  896): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  896): calling update connectivity
D/ConnectivityService(  896):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  896):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  896): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524295
,D/ConnectivityService(  896):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  896): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  896): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  896): calling update connectivity
D/ConnectivityService(  896):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  896):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  896): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524295
,D/ConnectivityService(  896):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  896): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2470): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 2470): CM callback handler got msg 524295
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/SSRM:m  (  896): SIOP:: AP = 410, PST = 369, CUR = 450
,I/WifiStateMachine(  896): REQUEST_POWER_SAVE_ON
,D/PackageManager(  896): [MSG] MCS_UNBIND
,E/WifiStateMachine(  896): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/ActivityManager(  896): Killing 5903:com.sec.android.gallery3d/u0a47 (adj 15): bgCount ##41
,W/libprocessgroup(  896): failed to open /acct/uid_10047/pid_5903/cgroup.procs: No such file or directory
,I/dhcpcd  ( 7904): wlan0: sending IPv6 Router Solicitation
,D/WearableService( 2248): callingUid 10011, callindPid: 2248
,D/ResourcesManager( 7809): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7809): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7809): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 7809): Using the GMSCore's GoogleHttpClient
,D/WearableClient( 7809): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7809): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7809): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7809): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 7809): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 7809): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/MusicLeanback( 7809): Conditions not met for autocaching.
I/MusicLeanback( 7809): Stop autocaching.
,E/ActivityThread( 7809): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@14ee99e6 that was originally bound here
E/ActivityThread( 7809): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@14ee99e6 that was originally bound here
E/ActivityThread( 7809): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 7809): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 7809): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 7809): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 7809): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 7809): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 7809): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7809): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7809): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7809): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 7809): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 7809): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 7809): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 7809): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 7809): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 7809): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 7809): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 7809): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 7809): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7809): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 7809): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 7809): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7809): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7809): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 7809): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  257): id=17 Removed Toast (8/9)
,I/SurfaceFlinger(  257): id=17 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,D/PowerManagerService(  896): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 896) eventTime = 117387
,D/PowerManagerService(  896): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=896 (0x0)
,D/PowerManagerService(  896): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=896, ws=WorkSource{10058}) (elapsedTime=3525)
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 1
,I/GAV4    ( 8021): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  294): DCD ON
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7279): mConnectivityHandler : connected
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7279): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7279): [GetString-S]
,I/ReactiveServiceManager( 7279): Supported : 1
,D/QSEECOMAPI: (  896): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: (  896): App is not loaded in QSEE
,D/QSEECOMAPI: (  896): Loaded image: APP id = 2
,D/QSEECOMAPI: (  896): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  896): QSEECom_shutdown_app, app_id = 2
E/terrier (  896): handleString: Failed to handle string(-4)
E/terrier (  896): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 7279): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7279): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7279): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7279): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7279): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7279): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 7904): wlan0: sending IPv6 Router Solicitation
,I/PowerManagerService(  896): [PWL] Off : 15s ago
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/PreloadUpdateManagerStateMachine( 7740): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7740): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7740): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7740): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7740): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7740): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7740): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 7740): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7740): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7740): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7740): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7740): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7740): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7740): entry::IDLE
,I/dhcpcd  ( 7904): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 7904): wlan0: no IPv6 Routers available
,V/AlarmManager(  896): waitForAlarm result :4
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  896): stay LED for fully charged
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/Finsky  ( 6508): [1060] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6508): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/SSRM:m  (  896): SIOP:: AP = 340, PST = 359, CUR = 450
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 2
,I/ActivityManager(  896): Waited long enough for: ServiceRecord{30decae8 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/SMD     (  294): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,E/Watchdog(  896): !@Sync 4
,V/AlarmManager(  896): waitForAlarm result :4
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  896): stay LED for fully charged
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  896): SIOP:: AP = 320, PST = 350, CUR = 450
,I/PowerManagerService(  896): [PWL] Off : 30s ago
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager(  896): waitForAlarm result :8
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:m  (  896): SIOP:: AP = 310, PST = 344, CUR = 450
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/art     (  896): Explicit concurrent mark sweep GC freed 51748(3MB) AllocSpace objects, 14(224KB) LOS objects, 30% free, 35MB/51MB, paused 2.211ms total 145.556ms
,E/SMD     (  294): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 50s ago
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/SSRM:m  (  896): SIOP:: AP = 300, PST = 340, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  294): DCD ON
,E/Watchdog(  896): !@Sync 5
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/SSRM:m  (  896): SIOP:: AP = 300, PST = 336, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 331, CUR = 450
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 75s ago
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 327, CUR = 450
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  294): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,E/Watchdog(  896): !@Sync 6
,I/ClearcutLoggerApiImpl( 2248): disconnect managed GoogleApiClient
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 322, CUR = 450
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 314, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  896): [PWL] Off : 105s ago
,E/SMD     (  294): DCD ON
,I/Atfwd_Sendcmd(  328): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  328): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 302, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,E/Watchdog(  896): !@Sync 7
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 297, CUR = 450
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,V/AlarmManager(  896): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  294): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/jxcore-log( 7445): Connected to the server!
I/jxcore-log( 7445): 
,I/chromium( 7445): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 294, CUR = 450
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 140s ago
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 292, CUR = 450
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  294): DCD ON
,E/Watchdog(  896): !@Sync 8
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 291, CUR = 450
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,V/AlarmManager(  896): waitForAlarm result :8
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 288, CUR = 450
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 286, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  896): !@Sync 9
,I/PowerManagerService(  896): [PWL] Off : 180s ago
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 284, CUR = 450
,E/SMD     (  294): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 282, CUR = 450
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 280, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  896): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  896): TimaServiceHandler.handleMessage what =1
,D/TimaService(  896): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  896): initializing...
,I/TLC_TIMA_PKM_initialize(  896): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  896): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  896): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  896): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  896): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  896): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  896): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  896): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  896): App is not loaded in QSEE
,D/QSEECOMAPI: (  896): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  896): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  896): Trustlet response is completed
,E/Watchdog(  896): !@Sync 10
,E/SMD     (  294): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 280, CUR = 450
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED,
I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/Atfwd_Sendcmd(  328): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  328): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 278, CUR = 450
,E/SMD     (  294): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8297): MountEmulatedStorage()
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  896): stay LED for fully charged
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,E/Zygote  ( 8297): v2
,I/libpersona( 8297): KNOX_SDCARD checking this for 10080
I/libpersona( 8297): KNOX_SDCARD not a persona
,I/SELinux ( 8297): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  896): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8297 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8297): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8297): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  896): [PWL] Off : 225s ago
I/PowerManagerService(  896): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  896): [PWL]     mWakeLockSummary : 0x1
,D/TimaKeyStoreProvider( 8297): TimaSignature is unavailable
,D/ActivityThread( 8297): Added TimaKeyStore provider
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ResourcesManager( 8297): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ActivityManager(  896): Killing 5792:com.android.mms/u0a49 (adj 15): bgCount ##41
,D/CountryDetector(  896): No listener is left
,W/libprocessgroup(  896): failed to open /acct/uid_10049/pid_5792/cgroup.procs: No such file or directory
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 276, CUR = 450,
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  896): !@Sync 11
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 274, CUR = 450
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 272, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 271, CUR = 450
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  294): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  896): !@Sync 12
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 270, CUR = 450
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 275s ago
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,V/AlarmManager(  896): waitForAlarm result :8
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 269, CUR = 450
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  294): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 268, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 13
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 267, CUR = 450
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 264, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 263, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  896): !@Sync 14
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 330s ago
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 262, CUR = 450
,I/Atfwd_Sendcmd(  328): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  328): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 261, CUR = 450
,E/SMD     (  294): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  896): !@Sync 15
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
I/bootchecker(  324): bootchecker wake up!!
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  294): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 16
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 390s ago
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  294): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 17
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD ON
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,E/SMD     (  294): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 18
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/Atfwd_Sendcmd(  328): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  328): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 455s ago
,E/SMD     (  294): DCD ON
,V/AlarmManager(  896): waitForAlarm result :8
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,I/Atfwd_Daemon(  328): Stop the daemon....
,E/Watchdog(  896): !@Sync 19,
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  896): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  896): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  896): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  896): !@Sync 20
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 525s ago
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD ON
,I/ActivityManager(  896): Killing 7380:com.sec.android.app.myfiles/u0a50 (adj 15): bgCount ##41
,W/libprocessgroup(  896): failed to open /acct/uid_10050/pid_7380/cgroup.procs: No such file or directory
,E/SMD     (  294): DCD ON
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/Watchdog(  896): !@Sync 21
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/Watchdog(  896): !@Sync 22
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/Watchdog(  896): !@Sync 23
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  896): [PWL] Off : 600s ago
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/Watchdog(  896): !@Sync 24
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,V/AlarmManager(  896): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/Watchdog(  896): !@Sync 25
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 680s ago
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/Watchdog(  896): !@Sync 26
,E/SMD     (  294): DCD ON
,V/AlarmManager(  896): waitForAlarm result :8
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,V/AlarmManager(  896): waitForAlarm result :8
,D/LightsService(  896): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  896): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  896): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/LightsService(  896): [SvcLED]  onSensorChanged::light value = 1
,E/LightSensor(  896): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  896): unregisterListener ::   
,D/LightsService(  896): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/Watchdog(  896): !@Sync 27
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/Watchdog(  896): !@Sync 28
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,V/AlarmManager(  896): waitForAlarm result :8
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  896): [PWL] Off : 765s ago
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/Watchdog(  896): !@Sync 29
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/TimaService(  896): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  896): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  896): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  896): !@Sync 30
,E/SMD     (  294): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 31
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,I/PowerManagerService(  896): [PWL] Off : 855s ago
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/Watchdog(  896): !@Sync 32
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/Watchdog(  896): !@Sync 33
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 34
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 950s ago
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 35
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 36
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 37
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 38
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 1050s ago
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/Watchdog(  896): !@Sync 39
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,D/TimaService(  896): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  896): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  896): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  896): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  896): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  896): Updating Usage Statistics in DB @ 1449757848311
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  896): Done Updating Usage Statistics in DB @ 1449757848551
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 40
,E/SMD     (  294): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  896): !@Sync 41
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,I/PowerManagerService(  896): [PWL] Off : 1155s ago
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  896): !@Sync 42
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  896): !@Sync 43
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  896): !@Sync 44
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  896): !@Sync 45
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 1265s ago
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  896): !@Sync 46
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  896): !@Sync 47
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  896): !@Sync 48
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  896): !@Sync 49
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  896): [PWL] Off : 1380s ago
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/TimaService(  896): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  896): TimaServiceHandler.handleMessage what =1
,D/TimaService(  896): TIMA: checkEvent, operation: 50000 subject: 10000
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  896): !@Sync 50
,E/SMD     (  294): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  896): !@Sync 51
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,I/art     (  896): Background sticky concurrent mark sweep GC freed 73608(9MB) AllocSpace objects, 425(6MB) LOS objects, 18% free, 35MB/43MB, paused 2.350ms total 142.967ms
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  896): !@Sync 52
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  896): !@Sync 53
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 1500s ago
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  896): !@Sync 54
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  896): !@Sync 55
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  896): !@Sync 56
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  896): !@Sync 57
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 1625s ago
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  896): !@Sync 58
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  896): !@Sync 59
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,D/NetworkStatsFactory(  896): UpdateStatsForKnox
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,D/TimaService(  896): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  896): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  896): TimaServiceHandler.handleMessage what =1
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  896): !@Sync 60
,E/SMD     (  294): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/LightsService(  896): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  896): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  896): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,I/ProcessStatsService(  896): Prepared write state in 23ms
,I/ProcessStatsService(  896): Prepared write state in 12ms
,V/NetworkStats(  896): performPollLocked(flags=0x3)
,D/NtpTrustedTime(  896): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  896): UpdateStatsForKnox
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  896): performPollLocked() took 7ms
,D/NtpTrustedTime(  896): currentTimeMillis() cache hit
,D/NtpTrustedTime(  896): currentTimeMillis() cache hit
,D/NtpTrustedTime(  896): currentTimeMillis() cache hit
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2470): Aggregate from 1449756671643 (log), 1449756671643 (data)
,V/GLSActivity( 2248): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2248): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NativeCrypto( 2248): SSL shutdown failed: ssl=0xaf23b000: I/O error during system call, Connection timed out
,I/qtaguid ( 2248): Tagging socket 51 with tag 1000040100000000{268436481,0} uid 10011, pid: 2248, getuid(): 10011
,I/qtaguid ( 2248): Tagging socket 63 with tag 1000040100000000{268436481,0} uid 10011, pid: 2248, getuid(): 10011
,E/LightSensor(  896): RED : 4, GREEN : 3, BLUE : 3, CLEAR : 6, CALCULATED LUX : 0.000000, CCT : 3267.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=2, rp1=2, gp1=1, bp1=1, cp1=4, cpl=3202560
,D/LightsService(  896): [SvcLED]  onSensorChanged::light value = 0
E/LightSensor(  896): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  896): unregisterListener ::   
,D/LightsService(  896): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ProcessStatsService(  896): Pruning old procstats: /data/system/procstats/state-2015-12-09-18-53-25.bin
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  896): !@Sync 61
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  896): [PWL] Off : 1755s ago
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  896): !@Sync 62
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,V/AlarmManager(  896): waitForAlarm result :8
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,E/Watchdog(  896): !@Sync 63
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  294): DCD ON,
,E/SMD     (  294): DCD ON
,E/SMD     (  294): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  294): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  294): DCD ON
D/AndroidRuntime( 8442): 
D/AndroidRuntime( 8442): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8442): CheckJNI is OFF
D/AndroidRuntime( 8442): setted country_code = Poland
D/AndroidRuntime( 8442): setted countryiso_code = PL
D/AndroidRuntime( 8442): setted sales_code = XEO
D/AndroidRuntime( 8442): readGMSProperty: start
D/AndroidRuntime( 8442): readGMSProperty: already setted!!
D/AndroidRuntime( 8442): readGMSProperty: end
D/AndroidRuntime( 8442): addProductProperty: start
E/AffinityControl( 8442): AffinityControl: registerfunction enter
D/AndroidRuntime( 8442): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  896): START PACKAGE DELETE: observer{724297375}
D/PackageManager(  896): pkg{<packageName>}
D/PackageManager(  896): user{0}
D/PackageManager(  896): caller{2000}
D/PackageManager(  896): flags{3}
D/PersonaManagerService(  896): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  896): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  896): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  896): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  896): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  896): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  896): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  896): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  896): getApplicationUninstallationEnabled
D/ApplicationPolicy(  896): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  896): !@killApplicatoin: 10356, uninstall pkg
I/ActivityManager(  896): Force stopping com.test.thalitest appid=10356 user=-1: uninstall pkg
I/ActivityManager(  896): Killing 7445:com.test.thalitest/u0a356 (adj 0): stop com.test.thalitest
I/ActivityManager(  896): Killing 8092:com.samsung.android.sconnect/u0a137 (adj 15): empty for 1807s
I/ActivityManager(  896): Killing 5528:com.google.android.apps.plus/u0a134 (adj 15): empty for 1807s
I/ActivityManager(  896): Killing 8021:com.google.android.apps.magazines/u0a127 (adj 15): empty for 1807s
I/ActivityManager(  896): Killing 7993:com.android.chrome/u0a87 (adj 15): empty for 1807s
I/ActivityManager(  896): Killing 6471:com.sec.chaton/u0a85 (adj 15): empty for 1807s
I/ActivityManager(  896): Killing 6452:com.sec.knox.bridge/1000 (adj 15): empty for 1807s
I/ActivityManager(  896): Killing 7954:com.sec.android.widgetapp.ap.hero.accuweather/u0a70 (adj 15): empty for 1807s
I/ActivityManager(  896): Killing 6929:com.osp.app.signin/u0a44 (adj 15): empty for 1807s
I/ActivityManager(  896): Killing 7296:com.policydm/1000 (adj 15): empty for 1807s
I/ActivityManager(  896): Killing 7936:com.sec.android.soagent/u0a36 (adj 15): empty for 1807s
I/ActivityManager(  896): Killing 7921:com.samsung.klmsagent/u0a18 (adj 15): empty for 1807s
I/ActivityManager(  896): Killing 7896:com.sec.android.fotaclient/u0a10 (adj 15): empty for 1807s
I/ActivityManager(  896): Killing 7873:com.sec.android.diagmonagent/1000 (adj 15): empty for 1807s
I/ActivityManager(  896): Killing 7848:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1807s
I/ActivityManager(  896): Killing 7279:com.sec.pcw.device/1000 (adj 15): empty for 1807s
I/ActivityManager(  896): Killing 8138:com.sec.android.provider.badge/u0a77 (adj 15): empty for 1807s
I/ActivityManager(  896): Killing 7715:com.samsung.android.provider.shootingmodeprovider/u0a169 (adj 15): empty for 1811s
I/ActivityManager(  896): Killing 7700:com.sec.kidsplat.installer/u0a165 (adj 15): empty for 1812s
I/ActivityManager(  896): Killing 7665:com.samsung.helphub/1000 (adj 15): empty for 1812s
D/WifiService(  896): Client connection lost with reason: 4
I/WindowState(  896): WIN DEATH: Window{2ff28da2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  896): Killing 7647:com.samsung.android.magazine.service/u0a117 (adj 15): empty for 1812s
I/ActivityManager(  896): Killing 7630:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): empty for 1812s
I/ActivityManager(  896): Killing 7607:com.samsung.android.app.filterinstaller/1000 (adj 15): empty for 1812s
I/ActivityManager(  896): Killing 7593:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty for 1813s
I/SurfaceFlinger(  257): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
I/ActivityManager(  896): Killing 7584:com.sec.android.provider.logsprovider/u0a19 (adj 15): empty for 1813s
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
I/SurfaceFlinger(  257): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1180): value : false
I/ActivityManager(  896): Killing 7522:com.sec.android.automotive.drivelink/u0a98 (adj 15): empty for 1813s
I/ActivityManager(  896): Killing 7546:com.vlingo.midas/u0a32 (adj 15): empty for 1813s
I/ActivityManager(  896): Killing 7461:com.google.android.apps.docs/u0a97 (adj 15): empty for 1813s
I/ActivityManager(  896): Killing 7428:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1815s
I/ActivityManager(  896): Killing 7400:com.sec.android.app.soundalive/u0a57 (adj 15): empty for 1815s
I/ActivityManager(  896):   Force finishing activity ActivityRecord{328064af u0 com.test.thalitest/.MainActivity t4}
W/ActivityManager(  896): mDVFSHelper.acquire()
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
W/PackageSettings(  896): Skipping PackageSetting{2b82132d com.example.hello/10191} due to missing metadata
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
I/ActivityManager(  896): Force stopping com.test.thalitest appid=10356 user=0: pkg removed
I/ActivityManager(  896):   Force finishing activity ActivityRecord{328064af u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager(  896): Duplicate finish request for ActivityRecord{328064af u0 com.test.thalitest/.MainActivity t4 f}
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/FocusedStackFrame(  896): Set to : 0
I/art     ( 6327): Explicit concurrent mark sweep GC freed 28790(1607KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 14MB/24MB, paused 402us total 30.587ms
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/art     ( 1679): Explicit concurrent mark sweep GC freed 51932(3MB) AllocSpace objects, 1(39KB) LOS objects, 39% free, 16MB/27MB, paused 472us total 51.788ms
I/DBG_DM  ( 3705): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
I/art     ( 2470): Explicit concurrent mark sweep GC freed 42895(2MB) AllocSpace objects, 10(160KB) LOS objects, 24% free, 21MB/28MB, paused 4.483ms total 66.569ms
I/DBG_DM  ( 3705): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/DBG_DM  ( 3705): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/InputReader(  896): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1760): mOCRHelper is null
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
W/GeofencerStateMachine( 2248): Ignoring removeGeofence because network location is disabled.
E/Zygote  ( 8471): MountEmulatedStorage()
E/Zygote  ( 8471): v2
I/libpersona( 8471): KNOX_SDCARD checking this for 10018
I/libpersona( 8471): KNOX_SDCARD not a persona
I/ActivityManager(  896): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8471 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3705): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3705): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 10
I/DBG_DM  ( 3705): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
I/SELinux ( 8471): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8471): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8471): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  896): Explicit concurrent mark sweep GC freed 44080(4MB) AllocSpace objects, 118(2MB) LOS objects, 30% free, 35MB/51MB, paused 1.299ms total 164.712ms
D/ResourcesManager(  896): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/DBG_DM  ( 3705): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
I/art     (  896): WaitForGcToComplete blocked for 146.870ms for cause Explicit
I/DBG_DM  ( 3705): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
D/TimaKeyStoreProvider( 8471): TimaSignature is unavailable
D/ActivityThread( 8471): Added TimaKeyStore provider
D/SecContentProvider2(  896): uri = 14 selection = getSealedState
D/SecContentProvider2(  896): mCursor = null
D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
I/DBG_DM  ( 3705): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
I/DBG_DM  ( 3705): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/SurfaceWidgetView( 1499): destroyHardwareResources():242881194
I/DBG_DM  ( 3705): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/DBG_DM  ( 3705): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3705): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 3705): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
D/ActivityManager(  896): post active user change for 0
D/KnoxTimeoutHandler(  896): postActiveUserChange for user 0
D/ResourcesManager( 8471): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
V/WindowOrientationListener(  896): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  896): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  896): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  896): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  896): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
I/DBG_DM  ( 3705): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/Launcher( 1499): onRestart, Launcher: 1067094100
D/Launcher( 1499): onStart, Launcher: 1067094100
D/Launcher.HomeView( 1499): onStart
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/SecContentProvider2(  896): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  896): mCursor = null
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2067): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 2067): [237392/6] SurfaceWidget drawing first frame
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
I/SurfaceFlinger(  257): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
D/StatusBarManagerService(  896): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/StatusBarManagerService(  896): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/RegisteredServicesCache( 1478): empty dynamic service
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
E/ActivityThread( 3705): Performing stop of activity that is not resumed: {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}
E/ActivityThread( 3705): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}
E/ActivityThread( 3705): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3743)
E/ActivityThread( 3705): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3824)
E/ActivityThread( 3705): 	at android.app.ActivityThread.access$1200(ActivityThread.java:172)
E/ActivityThread( 3705): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1451)
E/ActivityThread( 3705): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3705): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3705): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 3705): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3705): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3705): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 3705): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/Launcher.HomeView( 1499): onStop
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
I/KLMS-2.4.503: ( 8471): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/Timeline( 3705): Timeline: Activity_idle id: android.os.BinderProxy@3247351e time:1921775
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
I/KLMS-2.4.503: ( 8471): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449758558372
I/ActivityManager(  896): Activity reported stop, but no longer stopping: ActivityRecord{30297345 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t3}
I/KLMS-2.4.503: ( 8471): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.503: ( 8471): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/InputMethodManagerService(  896): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Videos/Videos.apk
W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService(  896): Got RemoteException sending setActive(false) notification to pid 7445 uid 10356
E/Zygote  ( 8490): MountEmulatedStorage()
E/Zygote  ( 8490): v2
I/libpersona( 8490): KNOX_SDCARD checking this for 10103
I/libpersona( 8490): KNOX_SDCARD not a persona
I/ActivityManager(  896): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8490 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  896): Killing 8109:com.android.email/u0a162 (adj 15): empty for 1807s
I/art     (  896): Explicit concurrent mark sweep GC freed 12301(586KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 35MB/51MB, paused 6.913ms total 244.008ms
D/ResourcesManager(  896): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/RCPManagerService(  896): PackageReceiver onReceive()
I/HarmonyEASService(  896): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  896): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/SELinux ( 8490): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/BackupManagerService(  896): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/SELinux ( 8490): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/JobSchedulerService(  896): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  896): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  896): uID is 10356
V/EnterpriseBillingPolicy(  896): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  896): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  896): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  896): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  896): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  896): getBillingProfileForVpnEngine - start - com.test.thalitest
E/SELinux ( 8490): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/EnterpriseBillingPolicyStorage(  896): getBillingProfileForVpnEngine - end - null
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/TaskPersister(  896): removeObsoleteFile: deleting file=4_task.xml
D/TaskPersister(  896): removeObsoleteFile: deleting file=3_task.xml
D/KnoxTimeoutHandler(  896): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/TimaKeyStoreProvider( 8490): TimaSignature is unavailable
D/ActivityThread( 8490): Added TimaKeyStore provider
D/ResourcesManager( 8490): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
W/ActivityManager(  896): mDVFSHelper.release()
I/Timeline(  896): Timeline: Activity_windows_visible id: ActivityRecord{3e4b43e1 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:1921955
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/EnterpriseDeviceManagerService(  896): Package has changed for user 0
D/EnterpriseDeviceManagerService(  896): Admin package name: com.google.android.gms
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/PackageManager(  896): delete codoeFile: 
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/elm:14451( 8490): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/PackageManager(  896): result of delete: 1{724297375}
D/elm:14451( 8490): ELMEngine.ELMEngine( context ).
D/elm:14451( 8490): MDMBridge.setEnterpriseBridge()
D/AndroidRuntime( 8442): Shutting down VM
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14451( 8490): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Books/Books.apk
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/elm:14451( 8490): ElmAgentService : onCreate()
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Music2/Music2.apk
E/Zygote  ( 8507): MountEmulatedStorage()
I/libpersona( 8507): KNOX_SDCARD checking this for 10016
E/Zygote  ( 8507): v2
I/libpersona( 8507): KNOX_SDCARD not a persona
D/elm:14451( 8490): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8490): MainReceiver.listeningToPackageRemoved()
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/elm:14451( 8490): MDMBridge.getInstance()
D/elm:14451( 8490): MDMBridge.getAllLicenseInfoFromSDK()
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
I/ActivityManager(  896): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8507 uid=10016 gids={50016, 9997} abi=armeabi-v7a
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
I/art     (  318): Explicit concurrent mark sweep GC freed 8698(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 289us total 11.718ms
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 245us total 7.996ms
I/SELinux ( 8507): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8507): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8507): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/SMD     (  294): DCD ON
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 256us total 7.810ms
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/elm:14451( 8490): MDMBridge.getAllLicenseInfoFromSDK()
D/TimaKeyStoreProvider( 8507): TimaSignature is unavailable
D/ActivityThread( 8507): Added TimaKeyStore provider
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/elm:14451( 8490): ElmAgentService : onDestroy().
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
I/ActivityManager(  896): Killing 7030:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1807s
D/ResourcesManager( 8507): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk

```
