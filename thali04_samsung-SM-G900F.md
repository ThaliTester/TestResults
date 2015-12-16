#### Test 50650278cd699a4_thali04_samsung-SM-G900F Logs


```
--------- beginning of main
E/WifiStateMachine(  893): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/WifiStateMachine(  893): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  893): do suspend true
D/SensorManager(  893): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/SensorManager(  893): unregisterListener ::   
D/audio_hw_primary(  301): adev_set_parameters: enter: screen_state=off
V/voice   (  301): voice_set_parameters: enter: screen_state=off
V/voice   (  301): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  301): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  301): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  301): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  301): adev_set_parameters: exit
--------- beginning of system
D/LightsService(  893): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/SecExternalDisplayIntents_Java(  893): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
D/VolumePanel( 1181): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1181): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/VolumePanel( 1181): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1181): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
D/IpRemoteDisplayController(  893): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  893): Bridge Server is not available
D/Mms/FreeMessageReceiver( 5699): onReceive, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5699): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5699): onHandleIntent: ACTION_PACKAGE_ADDED
D/PersonaManagerService(  893): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler(  893): MSG_ACTION_SCREEN_OFF called
D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  893): stay LED for fully charged
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7233): MountEmulatedStorage()
E/Zygote  ( 7233): v2
E/LightSensor(  893): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
I/libpersona( 7233): KNOX_SDCARD checking this for 10050
I/libpersona( 7233): KNOX_SDCARD not a persona
D/AutomaticBrightnessController(  893): mCallbacks.updateBrightness()
D/DisplayPowerController(  893): getFinalBrightness : 8 -> 0
I/ActivityManager(  893): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7233 uid=10050 gids={50050, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
D/DisplayPowerState(  893): !@ ColorFade entry
D/DisplayPowerController(  893): ColorFade: onAnimationEnd
D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  893): Plugged
I/MotionRecognitionService(  893): setPowerConnected  = true
I/SELinux ( 7233): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
E/LightSensor(  893): Light old sensor_state 513, new sensor_state : 1 en : 0
D/HeadsetStateMachine( 3230): Disconnected process message: 10
I/SELinux ( 7233): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7233): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb6a62000
D/AutomaticBrightnessController(  893): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  893): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
D/AutomaticBrightnessController(  893): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
I/AutomaticBrightnessController(  893): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/DisplayPowerController(  893): getFinalBrightness : 0 -> 0
D/DisplayPowerController(  893): getFinalBrightness : 0 -> 0
I/ActivityManager(  893): Killing 6380:com.samsung.android.app.FileShareServer/u0a74 (adj 15): bgCount ##41
I/DisplayManagerService(  893): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  893): Display changed displayId=0
D/qdhwcomposer(  257): hwc_blank: Blanking display: 0
D/SensorManager(  893): unregisterListener ::   
E/Sensors (  893): Acc old sensor_state 1, new sensor_state : 0 en : 0
D/SensorManager(  893): unregisterListener ::   
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/NfcService( 1483): call the applyRotuiing
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/STATUSBAR-PhoneStatusBar( 1181):      ACTION_SCREEN_OFF is finished!!!! 
D/TimaKeyStoreProvider( 7233): TimaSignature is unavailable
D/ActivityThread( 7233): Added TimaKeyStore provider
E/StatusBar( 1181): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1181): dismissHelpPopup 
D/StatusBar.NetworkController( 1181): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/accuweather( 2243): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 2243): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2243): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
D/ResourcesManager( 7233): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/ResourcesManager( 7233): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7233): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/libprocessgroup(  893): failed to open /acct/uid_10074/pid_6380/cgroup.procs: No such file or directory
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SystemBroadcastReceiver( 6187): [#DCM#] [DCM_Performance] onReceive completed in time  316 microsec. 
I/SystemBroadcastReceiver( 6187): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 6187): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 6187): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
W/ActivityManager(  893): getTasks: caller 10085 does not hold GET_TASKS; limiting output
W/ActivityManager(  893): getTasks: caller 10085 does not hold GET_TASKS; limiting output
D/PowerManagerService(  893): [PWL] sb release: PowerManagerService.Broadcasts
D/SSRM:m  (  893): SIOP:: AP = 370, PST = 374, CUR = 450
D/MyFiles ( 7233): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
I/rmt_storage(  285): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6c01090
I/rmt_storage(  285): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  285): wakelock acquired: 1, error no: 42
I/rmt_storage(  285): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1228406656)
E/installd(  304): system dir 0 : /system/app/
E/installd(  304): system dir 1 : /system/priv-app/
E/installd(  304): system dir 2 : /vendor/app/
E/installd(  304): system dir 3 : /oem/app/
I/TactileAssist(  893): enable value -1
I/TactileAssist(  893): internal enable value -1
I/TactileAssist(  893): intensity value -1
I/TactileAssist(  893): saveAppList value true
I/TactileAssist(  893): List of disabled apps :
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7254): MountEmulatedStorage()
E/Zygote  ( 7254): v2
I/libpersona( 7254): KNOX_SDCARD checking this for 10057
I/libpersona( 7254): KNOX_SDCARD not a persona
D/PackageManager(  893): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
I/ActivityManager(  893): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7254 uid=10057 gids={50057, 9997, 3003, 3002} abi=armeabi-v7a
I/rmt_storage(  285): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  285): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  285): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1228406656) wakelock released: 1, error no: 22
I/rmt_storage(  285): 
I/rmt_storage(  285): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6c01090
I/SELinux ( 7254): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7254): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7254): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7254): TimaSignature is unavailable
D/ActivityThread( 7254): Added TimaKeyStore provider
D/ResourcesManager( 7254): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
W/ResourcesManager( 7254): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/AndroidRuntime( 7250): 
D/AndroidRuntime( 7250): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7250): CheckJNI is OFF
D/AndroidRuntime( 7250): setted country_code = Poland
D/AndroidRuntime( 7250): setted countryiso_code = PL
D/AndroidRuntime( 7250): setted sales_code = XEO
D/AndroidRuntime( 7250): readGMSProperty: start
D/AndroidRuntime( 7250): readGMSProperty: already setted!!
D/AndroidRuntime( 7250): readGMSProperty: end
D/AndroidRuntime( 7250): addProductProperty: start
D/Compatibility( 7254): onReceive() it will make start service
D/Compatibility( 7254): onHandleIntent()
D/Compatibility( 7254): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10356, android.intent.extra.user_handle=0}]
I/UpdateIcingCorporaServi( 1568): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
D/Compatibility( 7254): found: 2
D/Compatibility( 7254): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7254): skipping ResolveInfo{df964dd com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 7254): considering ResolveInfo{fd97852 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 7254): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7254): enabling receiver ResolveInfo{23ad6723 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/qdhwcomposer(  257): hwc_blank: Done blanking display: 0
I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
E/Zygote  ( 7273): MountEmulatedStorage()
E/Zygote  ( 7273): v2
I/libpersona( 7273): KNOX_SDCARD checking this for 1000
I/libpersona( 7273): KNOX_SDCARD not a persona
D/SurfaceControl(  893): Excessive delay in setPowerMode(): 289ms
D/PowerManagerService(  893): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  893): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  893): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL(  893): Got set_interactive hint
I/PowerManagerService(  893): [PWL] Off : 0s ago
I/PowerManagerService(  893): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  893): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  893): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=893, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=399)
I/PowerManagerService(  893): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  893): [PWL]     mDisplayReady : false
D/DisplayPowerController(  893): getFinalBrightness : 0 -> 0
D/PowerManagerService(  893): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  893): [PWL] sb release: PowerManagerService.Display
I/ActivityManager(  893): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7273 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7273): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7273): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7273): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 7254): enabling receiver ResolveInfo{2e53c420 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 7254): enabling receiver ResolveInfo{102c71d9 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 7254): enabling receiver ResolveInfo{1472c79e com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/TimaKeyStoreProvider( 7273): TimaSignature is unavailable
D/ActivityThread( 7273): Added TimaKeyStore provider
D/Compatibility( 7254): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
I/ActivityManager(  893): Killing 6398:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
D/ResourcesManager( 1568): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/ResourcesManager( 7273): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
I/UpdateIcingCorporaServi( 1568): UpdateCorporaTask done [took 79 ms] updated apps [took 79 ms] 
E/AffinityControl( 7250): AffinityControl: registerfunction enter
W/ContextImpl( 7273): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
D/AndroidRuntime( 7250): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  893): failed to open /acct/uid_1000/pid_6398/cgroup.procs: No such file or directory
E/PersonaManagerService(  893): inState():  stateMachine is null !!
V/ApplicationPolicy(  893): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  893): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  893): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  893): mDVFSHelper.acquire()
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7298): MountEmulatedStorage()
E/Zygote  ( 7298): v2
I/libpersona( 7298): KNOX_SDCARD checking this for 10356
I/libpersona( 7298): KNOX_SDCARD not a persona
I/ActivityManager(  893): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7298 uid=10356 gids={50356, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SELinux ( 7298): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/AndroidRuntime( 7250): Shutting down VM
I/SELinux ( 7298): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7298): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7311): MountEmulatedStorage()
E/Zygote  ( 7311): v2
I/libpersona( 7311): KNOX_SDCARD checking this for 10097
I/libpersona( 7311): KNOX_SDCARD not a persona
I/ActivityManager(  893): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7311 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  893): Killing 6438:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
I/SELinux ( 7311): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SELinux ( 7311): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/TimaKeyStoreProvider( 7298): TimaSignature is unavailable
E/SELinux ( 7311): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityThread( 7298): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/TimaKeyStoreProvider( 7311): TimaSignature is unavailable
D/ActivityThread( 7311): Added TimaKeyStore provider
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7298): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SurfaceFlinger(  257): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (5/8)
I/SurfaceFlinger(  257): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/8)
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SQLiteSecureOpenHelper( 3492): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3492): getDatabaseLocked(b,b,pwd)...
D/ResourcesManager( 7311): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
W/libprocessgroup(  893): failed to open /acct/uid_1000/pid_6438/cgroup.procs: No such file or directory
D/DocsApplication( 7311): Installing DEX configuration.
D/DexInstaller( 7311): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/PackageInfoHelper( 7311): Provided clientMode=RELEASE, packageInfo=PackageInfo{92850b4 com.google.android.apps.docs}
I/WebViewFactory( 7298): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7298): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/TAG     ( 7311): onCreate()
I/LibraryLoader( 7298): Loading: webviewchromium
I/LibraryLoader( 7298): Time to load native libraries: 2 ms (timestamps 5978-5980)
I/LibraryLoader( 7298): Expected native library version number "",actual native library version number ""
D/CrossAppStateProvider( 7311): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
V/WebViewChromiumFactoryProvider( 7298): Binding Chromium to main looper Looper (main, tid 1) {102c71d9}
I/LibraryLoader( 7298): Expected native library version number "",actual native library version number ""
I/chromium( 7298): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7298): Initializing chromium process, renderers=0
W/art     ( 7298): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7298): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7298): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium( 7298): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,I/Adreno-EGL( 7298): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7298): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7298): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7298): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7298): Remote Branch: 
I/Adreno-EGL( 7298): Local Patches: 
I/Adreno-EGL( 7298): Reconstruct Branch: 
,W/chromium( 7298): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7298): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7298): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7298): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7298): CordovaWebView is running on device made by: samsung
,W/art     ( 7298): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7298): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity( 7298): performCreate Call secproduct feature valuefalse
D/Activity( 7298): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 7298): Render dirty regions requested: true
D/ActivityManager(  893): post active user change for 0
D/KnoxTimeoutHandler(  893): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  893): handleActiveUserChange for user 0
I/SurfaceFlinger(  257): id=16 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/StatusBarManagerService(  893): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/StatusBarManagerService(  893): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/OpenGLRenderer( 7298): Initialized EGL, version 1.4
I/OpenGLRenderer( 7298): HWUI protection enabled for context ,  &this =0xa1753060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7298): Enabling debug mode 0
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/InputMethodManagerService(  893): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
W/ActivityManager(  893): mDVFSHelper.release()
W/IInputConnectionWrapper( 7298): showStatusIcon on inactive InputConnection
I/Timeline( 7298): Timeline: Activity_idle id: android.os.BinderProxy@30707550 time:106323
I/Timeline(  893): Timeline: Activity_windows_visible id: ActivityRecord{3c0a8135 u0 com.test.thalitest/.MainActivity t4} time:106324
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/JsMessageQueue( 7298): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 7298): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1361762944
D/JX-Cordova( 7298): jxcore cordova android initializing
E/SMD     (  295): DCD ON
I/Atfwd_Sendcmd(  347): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  347): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7374): MountEmulatedStorage()
E/Zygote  ( 7374): v2
I/libpersona( 7374): KNOX_SDCARD checking this for 10098
I/libpersona( 7374): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=7374 uid=10098 gids={50098, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 5941:com.sec.providers.settingsearch/u0a167 (adj 15): bgCount ##41
,I/art     (  323): Explicit concurrent mark sweep GC freed 8760(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 270us total 13.676ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.710ms
,I/SELinux ( 7374): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7374): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 7.958ms
,E/SELinux ( 7374): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/GAV2    ( 7311): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/libprocessgroup(  893): failed to open /acct/uid_10167/pid_5941/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7374): TimaSignature is unavailable
,D/ActivityThread( 7374): Added TimaKeyStore provider
,D/ResourcesManager( 7374): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
,W/ResourcesManager( 7374): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/[CarMode]( 7374): [DLApplication]-onCreate: Applicatino Started!
,D/SampleAppCoreManager( 7374): SampleAppCoreManager VACVersion '2.2.0.11867'
,I/VlingoAndroidCore( 7374): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7404): MountEmulatedStorage()
E/Zygote  ( 7404): v2
I/libpersona( 7404): KNOX_SDCARD checking this for 10032
I/libpersona( 7404): KNOX_SDCARD not a persona
I/ActivityManager(  893): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=7404 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 7404): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7404): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7404): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7404): TimaSignature is unavailable
D/ActivityThread( 7404): Added TimaKeyStore provider
D/ResourcesManager( 7404): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
W/ResourcesManager( 7404): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/System.out( 7404): Inside onCreate() of WakeupTriggerProvide
I/System.out( 7404): Inside WakeupProvider
E/DatabaseUtils( 7404): Writing exception to parcel
E/DatabaseUtils( 7404): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7404): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7404): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7404): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7404): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7404): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7404): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7404): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7404): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7404): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7404): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 7374): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
I/VlingoApplication( 7404): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=XEO
W/System.err( 7374): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7374): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7374): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7374): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7374): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7374): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7374): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7374): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7374): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7374): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7374): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7374): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7374): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 7374): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 7374): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 7374): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 7374): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 7374): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 7374): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 7374): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7374): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7374): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7374): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7374): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7374): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7374): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7374): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7374): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7374): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7374): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7374): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/GAV2    ( 7311): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
E/DatabaseUtils( 7404): Writing exception to parcel
E/DatabaseUtils( 7404): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7404): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7404): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7404): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7404): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7404): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7404): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7404): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7404): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7404): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7404): 	at android.os.Binder.execTransact(Binder.java:446)
I/VlingoAndroidCore( 7404): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
W/System.err( 7374): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err( 7374): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7374): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7374): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7374): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7374): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7374): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7374): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7374): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7374): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7374): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7374): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7374): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7374): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 7374): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 7374): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 7374): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 7374): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7374): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7374): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7374): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7374): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7374): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7374): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7374): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7374): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7374): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7374): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7374): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode]( 7374): [DLApplication]-Init Called!:false
E/[CarMode]( 7374): [DLApplication]-Init Started!:true
I/[CarModeFW]( 7374): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 7374): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 7374): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 7374): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 7374): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 7374): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 7374): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 7374): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 7374): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 7374): ### android.os.Looper::loop(145)
I/[CarModeFW]( 7374): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 7374): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 7374): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 7374): ### com.android.internal.os.ZygoteInit::main(1194)
I/MessageDataHandler( 7374): initialize
D/[CarModeFW]( 7374): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 7374): CDH-initiazlieCaches : after sync
D/[CarModeFW]( 7374): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW]( 7374): CDH-ContactDataHandler initiazlieCaches time : 30
D/[CarModeFW]( 7374): CDH-initiazlieCaches : end sync
D/[CarModeFW]( 7374): DrivingManager-initialize...
D/VlingoApplication( 7404): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication( 7404): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
I/SensorService(  893): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
I/SensorService(  893): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  893): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
I/MediaPlayer( 7374): Need to enable context aware info
V/MediaPlayer-JNI( 7374): native_setup
V/MediaPlayer( 7374): constructor
V/MediaPlayer( 7374): setListener
E/MediaPlayer-JNI( 7374): QCMediaPlayer mediaplayer NOT present
D/[CarModeFW]( 7374): PushMessageManager-bindPushMessageService
I/[CarModeFW]( 7374): DriveLinkServiceInterfaceImp-drivelink framework initialize end
D/[CarMode]( 7374): [DLServiceManager]-getOnDLLocationSuggestionListener..........
D/[CarMode]( 7374): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW]( 7374): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1450240743504
D/[CarModeFW]( 7374): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1450240743504
D/[CarModeFW]( 7374): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1450240743504
D/[CarModeFW]( 7374): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1450240743505
D/[CarModeFW]( 7374): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1450240743505
I/[CarMode]( 7374): [LogNotNull]-Package name is: com.google.android.apps.maps
D/[CarModeFW]( 7374): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1450240743512
D/TP/SmsProvider( 1489): query,matched:2, calling pid = 7374
D/TP/SmsProvider( 1489): match 2:Elapsed time : 1.594 ms
D/[CarModeFW]( 7374): CDH-buildContactCacheWireFrame : cur len =0
E/[CarMode]( 7374): [DLApplication]-Init End!:true
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7437): MountEmulatedStorage()
I/libpersona( 7437): KNOX_SDCARD checking this for 10019
E/Zygote  ( 7437): v2
I/libpersona( 7437): KNOX_SDCARD not a persona
I/ActivityManager(  893): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7437 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7443): MountEmulatedStorage()
I/libpersona( 7443): KNOX_SDCARD checking this for 10003
E/Zygote  ( 7443): v2
I/libpersona( 7443): KNOX_SDCARD not a persona
I/ActivityManager(  893): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=7443 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
I/SELinux ( 7437): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7437): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7437): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/SELinux ( 7443): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7443): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/TP/SmsProvider( 1489): query,matched:2, calling pid = 7374
E/SELinux ( 7443): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TP/SmsProvider( 1489): match 2:Elapsed time : 0.987 ms
D/[CarMode]( 7374): [DLApplication]-GooglePlayServices SUCCESS.
D/TimaKeyStoreProvider( 7437): TimaSignature is unavailable
D/ActivityThread( 7437): Added TimaKeyStore provider
D/[CarModeFW]( 7374): CDH-buildContactCacheWireFrame : cur len =0
D/TP/MmsProvider( 1489): Query uri=content://mms, match=0, calling pid = 7374
D/MessageDataHandler( 7374):  getInboxList smsCursor : 118
E/[CarMode]( 7374): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
D/[CarModeFW]( 7374): RecommendHandler-selection = type = '3'
D/TP/MmsProvider( 1489): Query uri=content://mms/inbox, match=2, calling pid = 7374
D/MessageDataHandler( 7374):  getInboxList mmsCursor : 6
D/TimaKeyStoreProvider( 7443): TimaSignature is unavailable
D/ActivityThread( 7443): Added TimaKeyStore provider
I/UpdateManagerReceiver( 7374): Intent : android.intent.action.PACKAGE_ADDEDWed Dec 16 05:39:03 GMT+01:00 2015
D/[CarModeFW]( 7374): CDH-buildContactCacheWireFrame : cur len =0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 7443): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
D/ResourcesManager( 7437): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
E/Zygote  ( 7467): MountEmulatedStorage()
I/libpersona( 7467): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7467): v2
I/libpersona( 7467): KNOX_SDCARD not a persona
I/ActivityManager(  893): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7467 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7467): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7467): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/ActivityManager(  893): Killing 5583:com.sec.android.app.samsungapps/u0a39 (adj 15): bgCount ##41
E/SELinux ( 7467): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/MessageDataHandler( 7374):  getInboxList mms,sms cursor join : 77
D/[CarModeFW]( 7374): RecommendHandler-selection = type = '3'
I/MessageDataHandler( 7374): getUnreadMessageCount :0
D/TimaKeyStoreProvider( 7467): TimaSignature is unavailable
D/[CarModeFW]( 7374): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 223
D/TP/MmsSmsProvider( 1489): query,matched:0, calling pid = 7374
V/TP/MmsSmsProvider( 1489): getSimpleConversations entered.
D/ActivityThread( 7467): Added TimaKeyStore provider
D/TP/MmsSmsProvider( 1489): match 0:Elapsed time : 0.951 ms
D/[CarModeFW]( 7374): PushMessageService-onCreate
I/ActivityManager(  893): Killing 5903:com.google.android.gm/u0a113 (adj 15): bgCount ##41
I/ActivityManager(  893): Killing 6245:com.sec.android.app.music:service/u0a43 (adj 15): bgCount ##42
I/ActivityManager(  893): Killing 6187:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##43
D/ResourcesManager( 7467): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
D/TP/MmsSmsProvider( 1489): query,matched:13, calling pid = 7374
D/TP/MmsSmsProvider( 1489): match 13:Elapsed time : 1.075 ms
D/UserAnalysis.PlaceProvider( 7443): PlaceProvider onCreate()
D/MessageDataHandler( 7374):  getInboxList address cursor : 15
D/TP/MmsSmsProvider( 1489): query,matched:0, calling pid = 7374
V/TP/MmsSmsProvider( 1489): getSimpleConversations entered.
D/[CarModeFW]( 7374): PushMessageManager-onServiceConnected
D/[CarModeFW]( 7374): PushMessageService-registerPushMessageServiceListener
D/TP/MmsSmsProvider( 1489): match 0:Elapsed time : 2.678 ms
D/MessageDataHandler( 7374):  getInboxList thread cursor : 5
D/MessageDataHandler( 7374):  thread, addr result: 9
I/[CarModeFW]( 7374): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 278
I/[CarModeFW]( 7374): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 7374): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 279
W/ContextImpl( 7467): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7483): MountEmulatedStorage()
E/Zygote  ( 7483): v2
I/libpersona( 7483): KNOX_SDCARD checking this for 10111
I/libpersona( 7483): KNOX_SDCARD not a persona
W/jxcore-log( 7298): Initializing JXcore engine
W/jxcore-log( 7298): JXcore engine is ready
I/ActivityManager(  893): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7483 uid=10111 gids={50111, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
W/jxcore-log( 7298): Starting JXcore engine
D/UserAnalysis.SecureDbManager( 7443): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 7443): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 7443): Create SecureDbHelper
I/SELinux ( 7483): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7483): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7483): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/auditd  ( 2035): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService(  893): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
D/SecurityLogAgent:SEDenialService(  893): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
D/TimaKeyStoreProvider( 7483): TimaSignature is unavailable
D/ActivityThread( 7483): Added TimaKeyStore provider
D/ResourcesManager( 7467): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
E/FilterInstaller( 7467): There is no requred permission
I/ActivityManager(  893): Killing 6143:com.google.android.music:main/u0a125 (adj 15): bgCount ##41
W/jxcore-log( 7298): Platform android
W/jxcore-log( 7298): 
W/jxcore-log( 7298): Process ARCH arm
W/jxcore-log( 7298): 
I/art     (  893): Explicit concurrent mark sweep GC freed 229430(15MB) AllocSpace objects, 5(4MB) LOS objects, 31% free, 35MB/51MB, paused 1.480ms total 115.112ms
D/IntelligenceServiceApplication( 7443): onCreate()
D/ResourcesManager( 7483): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
I/SQLiteSecureOpenHelper( 7443): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 7443): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 7443): Open Place.db in secure mode
D/PackageIntentReceiver( 7483): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 7483): Not GearManger package! 
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,I/SQLiteSecureOpenHelper( 7443): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 7443): ...getDatabaseLocked(b,b,pwd)
,E/Zygote  ( 7499): MountEmulatedStorage()
E/Zygote  ( 7499): v2
I/libpersona( 7499): KNOX_SDCARD checking this for 10117
I/libpersona( 7499): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=7499 uid=10117 gids={50117, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 5475:com.google.android.apps.plus/u0a134 (adj 15): bgCount ##41
,I/SELinux ( 7499): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7499): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7499): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  893): failed to open /acct/uid_10004/pid_6187/cgroup.procs: No such file or directory
,W/libprocessgroup(  893): failed to open /acct/uid_10039/pid_5583/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_10043/pid_6245/cgroup.procs: No such file or directory
,W/libprocessgroup(  893): failed to open /acct/uid_10113/pid_5903/cgroup.procs: No such file or directory
,D/[CarModeFW]( 7374): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 7374): MyPlaceProvider-=============
D/[CarModeFW]( 7374): MyPlaceProvider-=============
,D/[CarModeFW]( 7374): MyPlaceProvider-=============
,D/[CarModeFW]( 7374): MyPlaceProvider-=============
D/[CarModeFW]( 7374): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 7374): MyPlaceProvider-==============
,D/[CarModeFW]( 7374): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7374): MyPlaceProvider-==============
D/[CarModeFW]( 7374): MyPlaceProvider-latitude is not valid
,D/[CarModeFW]( 7374): MyPlaceProvider-==============
D/[CarModeFW]( 7374): MyPlaceProvider-latitude is not valid
,D/[CarModeFW]( 7374): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 613
,D/[CarMode]( 7374): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@26ccc4d1, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@6560bef3] LOCATIONS
,D/TimaKeyStoreProvider( 7499): TimaSignature is unavailable
,D/ActivityThread( 7499): Added TimaKeyStore provider
,W/libprocessgroup(  893): failed to open /acct/uid_10125/pid_6143/cgroup.procs: No such file or directory
,I/[CarModeFW]( 7374): -[snowdeer] Rec : Missed Call : 425
,D/[CarModeFW]( 7374): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 649
,D/ResourcesManager( 7499): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,I/[CarModeFW]( 7374): -[snowdeer] Rec : Favorite : 14
,W/ResourcesManager( 7499): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/[CarModeFW]( 7374): -[snowdeer] Rec : CallLog : 9
,I/[CarModeFW]( 7374): -[snowdeer] Rec : Schedule : 5
,I/[CarModeFW]( 7374): -[snowdeer] Rec : During DL app : 3
,I/[CarModeFW]( 7374): -[snowdeer] Rec : Location Sharing : 1
I/[CarModeFW]( 7374): -[snowdeer] Rec : POI : 0
I/[CarModeFW]( 7374): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7374): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7374): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
I/[CarModeFW]( 7374): -[snowdeer] Rec : getContactListFromHashMap : 1
D/[CarModeFW]( 7374): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 682
,I/[CarModeFW]( 7374): -[snowdeer] Rec : getContactListFromHashMap - core : 0
,I/[CarModeFW]( 7374): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7374): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 7374): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 683
,D/MagazineService Version( 7499): Magazine-Administrator: 11
,D/MagazineService Version( 7499): Magazine-Provider: 14
,D/MagazineService Version( 7499): Magazine-Channel: 14
,D/HeadlinesChannelApplication( 7499): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 7499): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,I/MagazineService::MagazineService( 7499): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,W/libprocessgroup(  893): failed to open /acct/uid_10134/pid_5475/cgroup.procs: No such file or directory
,E/Zygote  ( 7518): MountEmulatedStorage()
I/libpersona( 7518): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7518): v2
I/libpersona( 7518): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7518 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/MagazineService::MagazineService( 7499): [onHandleIntent] Send broadcast to (com.test.thalitest).
,I/SELinux ( 7518): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7518): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7518): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  893): Killing 6624:com.google.android.gms:car/u0a11 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7518): TimaSignature is unavailable
,D/ActivityThread( 7518): Added TimaKeyStore provider
,D/ResourcesManager( 7518): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/libprocessgroup(  893): failed to open /acct/uid_10011/pid_6624/cgroup.procs: No such file or directory
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7533): MountEmulatedStorage()
E/Zygote  ( 7533): v2
I/libpersona( 7533): KNOX_SDCARD checking this for 1000
I/libpersona( 7533): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7533 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 6454:com.android.vending/u0a29 (adj 15): bgCount ##41
,I/System.out( 7404): INFO:Resource not found:/Common.properties Using default values
,I/SELinux ( 7533): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7533): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7533): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7533): TimaSignature is unavailable
,D/ActivityThread( 7533): Added TimaKeyStore provider
,D/ResourcesManager( 7533): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,D/AcmsPackageEventListener( 7533): Received: android.intent.action.PACKAGE_ADDED
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  893): failed to open /acct/uid_10029/pid_6454/cgroup.procs: No such file or directory
,W/ContextImpl( 7533): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,E/Zygote  ( 7550): MountEmulatedStorage()
,E/Zygote  ( 7550): v2
I/libpersona( 7550): KNOX_SDCARD checking this for 10134
I/libpersona( 7550): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7550 uid=10134 gids={50134, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 6786:com.sec.android.fotaclient/u0a10 (adj 15): bgCount ##41
,I/SELinux ( 7550): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/AcmsService( 7533): Enter Oncreate
D/AcmsServiceMonitor( 7533): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
I/SELinux ( 7550): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/AcmsService( 7533): creating AcmsCore
D/AcmsCore( 7533): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 7533): AcmsCore
,E/SELinux ( 7550): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/AcmsCore( 7533): init
,D/AcmsCore( 7533): Looper handler is not null
,D/AcmsCore( 7533): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7533): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7533): Incrementing - Counter value: 1
D/AcmsCore( 7533): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 7533): onStartCommand
D/AcmsService( 7533): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 7533): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 7533): Incrementing - Counter value: 2
D/AcmsService( 7533): Incremented Counter Value : onStartCommand
,D/ActivityThread( 7533): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsCertificateMngr( 7533): AcmsCertificateMngr
,D/TimaKeyStoreProvider( 7550): TimaSignature is unavailable
D/AcmsRevocationMngr( 7533): AcmsRevocationMngr
,D/ActivityThread( 7550): Added TimaKeyStore provider
,D/ResourcesManager( 7550): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourcesManager( 7550): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AcmsService( 7533): Inside handle Intent
D/AcmsService( 7533): App added - package name: com.test.thalitest
D/AcmsCore( 7533): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7533): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7533): Incrementing - Counter value: 3
D/AcmsCore( 7533): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 7533): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 7533): Decrementing - Counter value: 2
,W/libprocessgroup(  893): failed to open /acct/uid_10010/pid_6786/cgroup.procs: No such file or directory
,I/jxcore-log( 7298): JXcore Cordova bridge is ready!
I/jxcore-log( 7298): 
,W/jxcore-log( 7298): JXcore engine is started
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7580): MountEmulatedStorage()
E/Zygote  ( 7580): v2
I/libpersona( 7580): KNOX_SDCARD checking this for 10165
I/libpersona( 7580): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=7580 uid=10165 gids={50165, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7580): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7580): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7580): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7580): TimaSignature is unavailable
,D/ActivityThread( 7580): Added TimaKeyStore provider
,D/ResourcesManager( 7580): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,W/ResourcesManager( 7580): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/KidsPlatformStub( 7580): Package not found : com.sec.android.app.kidshome
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7598): MountEmulatedStorage()
E/Zygote  ( 7598): v2
I/libpersona( 7598): KNOX_SDCARD checking this for 10169
I/libpersona( 7598): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7598 uid=10169 gids={50169, 9997, 1023} abi=armeabi-v7a
,I/art     (  323): Explicit concurrent mark sweep GC freed 8756(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 282us total 17.277ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 299us total 8.068ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 292us total 7.867ms
,I/SELinux ( 7598): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7598): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7598): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/FactoryTest( 6311): Not factory mode
D/FactoryTest( 6311): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6311): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6311): still no open session command from host, so toast
,W/ContextImpl( 6311): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6311): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
I/Timeline( 6311): Timeline: Activity_launch_request id:com.android.settings time:109123
,E/PersonaManagerService(  893): inState():  stateMachine is null !!
,V/ApplicationPolicy(  893): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  893): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  893): mDVFSHelper.acquire()
,D/TimaKeyStoreProvider( 7598): TimaSignature is unavailable
,D/ActivityThread( 7598): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
E/MTPRx   ( 6311): started activity for popup
,I/SQLiteSecureOpenHelper( 3492): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3492): getDatabaseLocked(b,b,pwd)...
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ResourcesManager( 7598): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/SQLiteLog( 7598): (284) automatic index on shooting_modes(title_id)
,D/ResourcesManager( 6311): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6311): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6311): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6311): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6311): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6311): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6311): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6311): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7613): MountEmulatedStorage()
E/Zygote  ( 7613): v2
I/libpersona( 7613): KNOX_SDCARD checking this for 10029
I/libpersona( 7613): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7613 uid=10029 gids={50029, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 6807:com.samsung.klmsagent/u0a18 (adj 15): bgCount ##41
,E/SettingsReceiverActivity( 6311): PREF_DONT_ASK_AGAIN : true
,I/SELinux ( 7613): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SELinux ( 7613): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7613): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6311): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,W/libprocessgroup(  893): failed to open /acct/uid_10018/pid_6807/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7613): TimaSignature is unavailable
,D/ActivityThread( 7613): Added TimaKeyStore provider
,D/SettingsReceiverActivity( 6311): dev.kiessupport is : TRUE
,D/ResourcesManager( 7613): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/Activity( 6311): performCreate Call secproduct feature valuefalse
D/Activity( 6311): performCreate Call debug elastic valuetrue
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
,D/Finsky  ( 7613): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,E/SMD     (  295): DCD ON
,D/Finsky  ( 7613): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7613): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7613): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 7613): Skipping gmscore version check
,D/Finsky  ( 7613): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7613): [1] Libraries$2.run: Finished loading 1 libraries.
,D/PackageBroadcastService( 2549): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/Finsky  ( 7613): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ChimeraCfgMgr( 2549): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2549): Loading module APK com.google.android.play.games
,D/Finsky  ( 7613): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 7613): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/ResourcesManager( 2549): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,I/jxcore-log( 7298): Toggling radios to true
I/jxcore-log( 7298): 
,D/BluetoothAdapter( 7298): enable()
,D/BluetoothAdapter( 7298): enable(): BT is already enabled..!
,D/WifiService(  893): New client listening to asynchronous messages
,I/WifiManager( 7298): packageName : com.test.thalitest
,D/SecContentProvider(  893): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  893): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  893): mCursor = null
,D/WifiService(  893): setWifiEnabled: true pid=7298, uid=10356
,E/WifiService(  893): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  893): Permission Denial: getCurrentUser() from pid=7298, uid=10356 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  893): Failed getting userId using ActivityManagerNative
W/WifiService(  893): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7298, uid=10356 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  893): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  893): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2122)
W/WifiService(  893): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2110)
W/WifiService(  893): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  893): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  893): name = wifi_on
,I/WifiService(  893): disconnect: pid=7298, uid=10356
,I/jxcore-log( 7298): Radios toggled
I/jxcore-log( 7298): 
,I/wpa_supplicant( 1278): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7298): Got Device Bluetooth address: 7C:F9:0E:34:8A:A0
I/jxcore-log( 7298): 
,I/jxcore-log( 7298): Perf Test app loaded loaded
I/jxcore-log( 7298): 
,I/jxcore-log( 7298): check test folder
I/jxcore-log( 7298): 
,I/jxcore-log( 7298): found test : ./testFindPeers.js
I/jxcore-log( 7298): 
,I/wpa_supplicant( 1278): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1278): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1278): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  893): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1278): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1278): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1278): Disconnected - do not scan
I/wpa_supplicant( 1278): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  893): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
,E/WifiStateMachine(  893): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  893): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  893): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  893): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  893): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  893): do suspend true
,D/WifiP2pService(  893): InactiveState{ what=143375 }
,D/WifiP2pService(  893): P2pEnabledState{ what=143375 }
,I/jxcore-log( 7298): found test : ./testSendData.js
I/jxcore-log( 7298): 
D/CommandListener(  290): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/NativeCrypto( 2121): Read error: ssl=0x9b52de00: I/O error during system call, Connection timed out
,V/NativeCrypto( 2121): SSL shutdown failed: ssl=0x9b52de00: I/O error during system call, Broken pipe
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): DefaultState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): Validated
D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  893): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  893): rematching NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  893):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  893):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  893):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  893): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,D/ConnectivityService(  893): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  893): calling update connectivity
D/ConnectivityService(  893):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  893):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine(  893): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityService(  893): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  893):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524290
E/WifiConfigStore(  893): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/WifiTrafficPoller(  893): evaluateTrafficStatsPolling
,E/ConnectivityService(  893): updateNetworkInfo()
D/ConnectivityService(  893): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  893): updateNetworkInfo()
,D/ConnectivityService(  893): ignoring duplicate network state non-change
D/ConnectivityService(  893): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
D/ConnectivityManager.CallbackHandler( 2549): CM callback handler got msg 524290
I/CLocInfoService(  893): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  893): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1278): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1278): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1278): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1278): First Scan Start
,I/wpa_supplicant( 1278): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  893): ConnectModeState: Network connection lost 
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
E/WifiStateMachine(  893): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
E/WifiStateMachine(  893): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
E/WifiStateMachine(  893): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
E/native  (  893): do suspend true
,D/WifiP2pService(  893): InactiveState{ what=143375 }
,D/WifiP2pService(  893): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,W/ActivityManager(  893): Activity pause timeout for ActivityRecord{3c0a8135 u0 com.test.thalitest/.MainActivity t4}
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,D/ConnectivityService(  893): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  893): calling update connectivity
,D/ConnectivityService(  893):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  893):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  893): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  893):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  893): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Nat464Xlat(  893): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  893): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  893): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): Disconnected - quitting
,D/CSLegacyTypeTracker(  893): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  893): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/TelephonyNetworkFactory( 1489): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  893): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/EntConnectivity(  893): Not allowed due to - mEnabled false
,E/WifiStateMachine(  893): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524292
,D/ConnectivityManager.CallbackHandler( 2549): CM callback handler got msg 524292
D/WifiStateMachine(  893): updateConfiguredNetworkExpiration - currTime: 1450240745949
D/WifiStateMachine(  893): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine(  893): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  893): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
I/WifiTrafficPoller(  893): evaluateTrafficStatsPolling
D/WifiNetworkAgent(  893): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  893): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  893): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  893): setDetailed state send new extra info"NG700"
I/CLocInfoService(  893): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  893): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  893): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  893): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  893): getSBEnabled() enabled =false
D/SmartBondingService(  893): getSBEnabled() enabled =false
D/SmartBondingService(  893): getSBEnabled() enabled =false
V/NetworkStats(  893): updateIfacesLocked()
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
V/NetworkStats(  893): performPollLocked(flags=0x1)
D/SmartBondingService(  893): getNetworkEnabled : wifi : true mobile : true
D/NetworkStatsFactory(  893): UpdateStatsForKnox
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1181): updateDataNetType()
D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
,D/NtpTrustedTime(  893): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1181): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
D/SecContentProvider2(  893): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  893): mCursor = null
V/NetworkStats(  893): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  893): currentTimeMillis() cache hit
,V/NetworkStats(  893): performPollLocked() took 12ms
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
,D/NtpTrustedTime(  893): currentTimeMillis() cache hit
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
D/SecContentProvider2(  893): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  893): mCursor = null
D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,D/InputMethodManagerService(  893): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  893): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@11d3de53 attribute=null, token = android.os.BinderProxy@3d4a0dd2
,D/ActivityManager(  893): post active user change for 0
D/KnoxTimeoutHandler(  893): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  893): handleActiveUserChange for user 0
,D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/Timeline( 7298): Timeline: Activity_idle id: android.os.BinderProxy@30707550 time:109979
,I/chromium( 7298): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ChimeraCfgMgr( 2549): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2549): Module APK com.google.android.play.games already loaded
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ChimeraCfgMgr( 2549): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 2549): Submit a task: k
,D/ChimeraCfgMgr( 2549): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 2549): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 2549): Processing package: com.test.thalitest
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7684): MountEmulatedStorage()
I/libpersona( 7684): KNOX_SDCARD checking this for 10039
E/Zygote  ( 7684): v2
I/libpersona( 7684): KNOX_SDCARD not a persona
,D/GassUtils( 2549): Found app info for package com.test.thalitest:18. Hash: 8d179c3391de64cb252217b95c8671d16c87cb117668119dbcd10fd1a66cc302
D/k       ( 2549): Found info for package com.test.thalitest in db.
,I/ActivityManager(  893): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7684 uid=10039 gids={50039, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7684): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7684): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7684): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,V/AlarmManager(  893): waitForAlarm result :4
,D/TimaKeyStoreProvider( 7684): TimaSignature is unavailable
,D/ActivityThread( 7684): Added TimaKeyStore provider
,W/BaseAppContext( 2549): Using Auth Proxy for data requests.
W/BaseAppContext( 2549): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 2549): cleanUpNonGplusAccounts done.
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7684): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,D/AcmsKeyStoreHelper( 7533):  getKeyStoreForApplication Enter
,I/chromium( 7298): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/AcmsKeyStoreHelper( 7533): Key Store exist
I/AcmsKeyStoreHelper( 7533): Hence loading the keystore file
,I/art     (  893): Explicit concurrent mark sweep GC freed 35239(1940KB) AllocSpace objects, 1(16KB) LOS objects, 31% free, 35MB/51MB, paused 1.527ms total 84.235ms
,I/chromium( 7298): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7298): 
,W/BaseAppContext( 2549): Using Auth Proxy for data requests.
,I/ActivityManager(  893): Killing 6822:com.sec.android.soagent/u0a36 (adj 15): bgCount ##41
,D/BootupListener( 1489): ACTION_DRIVELINK
D/SettingsProvider(  893): name = drivelink_navigation
D/SettingsProvider(  893): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  893): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  893): selectionArgs: false
D/SettingsProvider(  893): selectionArgs: 1001
D/SecContentProvider(  893): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  893): ret = -1
,D/BootupListener( 1489): NAVI : com.google.android.apps.maps
D/SettingsProvider(  893): name = internet_call_settings_visibility
D/SettingsProvider(  893): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  893): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  893): selectionArgs: false
D/SettingsProvider(  893): selectionArgs: 1001
D/SecContentProvider(  893): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  893): ret = -1
,D/SecurityLogAgent( 6944):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6944):  SeDenialReceiver : File path = null
,I/Hs20UtilService( 1312): Starting #6
,I/Hs20UtilService( 1312): Message received 5007
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
W/BaseAppContext( 2549): Using Auth Proxy for data requests.
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1312): MountReceiver.onReceive - Set preference state off
,W/BaseAppContext( 2549): Using Auth Proxy for data requests.
W/BaseAppContext( 2549): Using Auth Proxy for data requests.
,V/NearbySettings( 1312): MountReceiver.mPrefHandler - 7002
,I/Hs20UtilService( 1312): Starting #7
,I/Hs20UtilService( 1312): Message received 5007
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1312): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1312): MountReceiver.mPrefHandler - 7002
,W/libprocessgroup(  893): failed to open /acct/uid_10036/pid_6822/cgroup.procs: No such file or directory
,D/KeyguardViewMediator( 1181): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/KeyguardViewMediator( 1181): doKeyguard: not showing because lockscreen is off
W/BaseAppContext( 2549): Using Auth Proxy for data requests.
,D/AcmsKeyStoreHelper( 7533):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 7533): getKeyStoreForApplication success 
D/AcmsCore( 7533): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 7533): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7533): Decrementing - Counter value: 1
D/AcmsCore( 7533): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 7533): This is NOT a valid MirrorLink app
D/AcmsCore( 7533): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 7533): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsServiceMonitor( 7533): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 7533): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 7533): getSvcCounter - Counter value: 0
D/AcmsService( 7533): Enter onDestroy
,I/AcmsService( 7533): cleanUp(): inside service clean up
D/AcmsCore( 7533): AcmsCore: inside DeInit
D/AcmsCore( 7533): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 7533): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 7533): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 7533): KeyStoreHelper: inside cleanup
,D/AcmsAppEntryInterface( 7533): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 7533): getSvcCounter - Counter value: 0
D/AcmsService( 7533): killing acms process
,I/Process ( 7533): Sending signal. PID: 7533 SIG: 9
,D/ConnectivityService(  893): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  893): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ApplicationPolicy(  893): updateDataUsageMap
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  893): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  893): getSBEnabled() enabled =false
D/SmartBondingService(  893): getSBEnabled() enabled =false
,D/SmartBondingService(  893): getSBEnabled() enabled =false
,D/Tethering(  893): MasterInitialState.processMessage what=3
,D/SmartBondingService(  893): getNetworkEnabled : wifi : true mobile : true
,D/accuweather( 2243): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  893): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  893): CLoinfo wifi false
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 7134): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7134): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7134): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7134): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7134): noConnectivity : true
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3676): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/SLocation(  893): No Active Data Connection
,I/DBG_DM  ( 3676): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/Zygote  ( 7704): MountEmulatedStorage()
E/Zygote  ( 7704): v2
I/libpersona( 7704): KNOX_SDCARD checking this for 10125
I/libpersona( 7704): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=7704 uid=10125 gids={50125, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7704): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  893): Process ACMS.Process (pid 7533)(adj 0) has died(76,578)
,I/SELinux ( 7704): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7704): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7704): TimaSignature is unavailable
,D/ActivityThread( 7704): Added TimaKeyStore provider
,D/ResourcesManager( 7704): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore( 7704): Database version: 104
,D/ResourcesManager( 7704): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7704): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7704): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7704): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/PowerManagerService(  893): [PWL] Off : 5s ago
I/PowerManagerService(  893): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  893): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  893): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=893, ws=null) (elapsedTime=750)
I/PowerManagerService(  893): [PWL]       PARTIAL_WAKE_LOCK              'Icing' (uid=10011, pid=2549, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=579)
,W/ActivityThread( 7704): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7704): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e306ee3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7704): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7704): GMSCore installation verified
,I/ConfigStore( 7704): Config Database version: 1
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7704): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/art     ( 2549): Verification of void com.google.android.gms.games.broker.PlayerAgent.<init>(com.google.android.gms.games.broker.Lockable, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer) took 131.013ms
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7704): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7704): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/WifiDisplayAdapter(  893): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter(  893): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/AudioPolicyManager(  301): getOutputsForDevice device 0002 -> 0002
,I/AudioService(  893): getStreamVolume 3 index 0
,I/MediaRouter( 7704): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7732): MountEmulatedStorage()
E/Zygote  ( 7732): v2
I/libpersona( 7732): KNOX_SDCARD checking this for 10002
I/libpersona( 7732): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7732 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7732): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7732): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7732): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiDisplayAdapter(  893): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7704): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider( 7732): TimaSignature is unavailable
,D/ActivityThread( 7732): Added TimaKeyStore provider
,I/ActivityManager(  893): Killing 6857:com.samsung.android.scloud.sync/u0a66 (adj 15): bgCount ##41
,D/ResourcesManager( 7732): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/wpa_supplicant( 1278): nl80211: Received scan results (4 BSSes)
,I/wpa_supplicant( 1278): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 1278): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1278): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  893): [1,450,240,746,988 ms] noteScanEnd no scan source
,W/libprocessgroup(  893): failed to open /acct/uid_10066/pid_6857/cgroup.procs: No such file or directory
,E/WifiStateMachine(  893): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@39e1d3c5 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  893): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  893): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  893): setDetailed state send new extra info0x
,D/SecContentProvider2(  893): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  893): mCursor = null
,I/CLocInfoService(  893): External Intent Received android.net.wifi.SCAN_RESULTS
,I/ActivityManager(  893): Killing 6873:com.sec.android.widgetapp.ap.hero.accuweather/u0a70 (adj 15): bgCount ##41
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,D/ChimeraCfgMgr( 2549): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2549): Module APK com.google.android.play.games already loaded
,E/Zygote  ( 7760): MountEmulatedStorage()
,E/Zygote  ( 7760): v2
I/libpersona( 7760): KNOX_SDCARD checking this for 1000
I/libpersona( 7760): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7760 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7760): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7760): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7760): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 1278): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1278): Associated with C0.AA.48
,E/WifiStateMachine(  893): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  893): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  893): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  893): mCursor = null
,W/libprocessgroup(  893): failed to open /acct/uid_10070/pid_6873/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7760): TimaSignature is unavailable
,D/ActivityThread( 7760): Added TimaKeyStore provider
,D/ResourcesManager( 7760): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/wpa_supplicant( 1278): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  893): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  893): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  893): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  893): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  893): mCursor = null
,I/wpa_supplicant( 1278): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1278): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1278): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1278): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1278): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1278): Blacklist: Clear (temp) 
I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  893): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  893): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  893): Network connection established
,D/WifiNative-HAL(  893): callSECApiVoid - ID [50]
E/WifiStateMachine(  893): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  893): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  893): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  893): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  893): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  893): Got NetworkAgent Messenger
E/WifiStateMachine(  893): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  893): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService(  893): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiConfigStore(  893): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  893): NetworkAgent connected
E/ConnectivityService(  893): updateNetworkInfo()
,I/DIAGMON_AGENT( 7760): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,E/WifiStateMachine(  893): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  893): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  893): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  893): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  290): Setting iface cfg
,E/WifiStateMachine(  893): Start Dhcp Watchdog 2
,D/SecContentProvider2(  893): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  893): mCursor = null
,I/DIAGMON_AGENT( 7760): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/Icing   ( 2549): Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,E/WifiStateMachine(  893): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  893): do suspend false
,D/WifiP2pService(  893): InactiveState{ what=143375 }
,D/WifiP2pService(  893): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  893): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  893): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  893): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/SecContentProvider2(  893): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  893): mCursor = null
,I/DIAGMON_AGENT( 7760): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7760): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7760): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7760): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/ResourcesManager( 2549): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7781): MountEmulatedStorage()
E/Zygote  ( 7781): v2
I/libpersona( 7781): KNOX_SDCARD checking this for 10010
I/libpersona( 7781): KNOX_SDCARD not a persona
,I/Icing   ( 2549): Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
I/ActivityManager(  893): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7781 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7781): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7781): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7781): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7781): TimaSignature is unavailable
,D/ActivityThread( 7781): Added TimaKeyStore provider
,D/ResourcesManager( 7781): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager(  893): Killing 6890:com.sec.android.app.clockpackage/u0a90 (adj 15): bgCount ##41
,I/FOTA_Client( 7781): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7781): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,W/libprocessgroup(  893): failed to open /acct/uid_10090/pid_6890/cgroup.procs: No such file or directory
,I/FOTA_Client( 7781): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  893): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7796 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 6905:com.sec.esdk.elm/u0a103 (adj 15): bgCount ##41
,E/Zygote  ( 7796): MountEmulatedStorage()
,E/Zygote  ( 7796): v2
I/libpersona( 7796): KNOX_SDCARD checking this for 10018
I/libpersona( 7796): KNOX_SDCARD not a persona
,E/dhcpcd  ( 7802): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7802): version 5.5.6 starting
,E/dhcpcd  ( 7802): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/SELinux ( 7796): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7796): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7796): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  893): failed to open /acct/uid_10103/pid_6905/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7796): TimaSignature is unavailable
,D/ActivityThread( 7796): Added TimaKeyStore provider
,D/ResourcesManager( 7796): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/dhcpcd  ( 7802): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7802): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7802): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7802): bssid match
,I/KLMS-2.4.503: ( 7796): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/dhcpcd  ( 7802): wlan0: rebinding lease of 192.168.1.136
,I/KLMS-2.4.503: ( 7796): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450240747484
,I/KLMS-2.4.503: ( 7796): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7796): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7796): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  893): Killing 6922:com.sec.android.GeoLookout/u0a112 (adj 15): bgCount ##41
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7818): MountEmulatedStorage()
I/libpersona( 7818): KNOX_SDCARD checking this for 10036
E/Zygote  ( 7818): v2
I/libpersona( 7818): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7818 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7818): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7818): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7818): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  893): failed to open /acct/uid_10112/pid_6922/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7818): TimaSignature is unavailable
,D/ActivityThread( 7818): Added TimaKeyStore provider
,D/ResourcesManager( 7818): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/ActivityManager(  893): Killing 5611:com.sec.android.widgetapp.SPlannerAppWidget/u0a148 (adj 15): bgCount ##41
,I/SO_AGENT( 7818): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7171): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6838): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 6838): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6838): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,E/SPPClientService( 7171): [[SystemStateMonitorService]] No Active Internet
,W/libprocessgroup(  893): failed to open /acct/uid_10148/pid_5611/cgroup.procs: No such file or directory
,I/SA      ( 6838): [SLFUCHKMGR] constructor called
,I/SA      ( 6838): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6838): [OR] == isSIMCardReady false ==
,I/SA      ( 6838): [SCU] == networkStateCheck == false
,I/SA      ( 6838): [OR] onReceive END
,I/ActivityManager(  893): Killing 4681:com.android.calendar/u0a149 (adj 15): bgCount ##41
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7841): MountEmulatedStorage()
E/Zygote  ( 7841): v2
I/libpersona( 7841): KNOX_SDCARD checking this for 10070
I/libpersona( 7841): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7841 uid=10070 gids={50070, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7841): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7841): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7841): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  893): failed to open /acct/uid_10149/pid_4681/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7841): TimaSignature is unavailable
,D/ActivityThread( 7841): Added TimaKeyStore provider
,D/ResourcesManager( 7841): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7841): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7841): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7841): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/comsamsunglog( 7841): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7841): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7841): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7841): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7841): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7841): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7841): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7841): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  893): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  893): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  893): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  893): selectionArgs: false
D/SettingsProvider(  893): selectionArgs: 10070
D/SecContentProvider(  893): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  893): ret = -1
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7841): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7841): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
D/accuweather( 7841): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7841): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
D/accuweather( 7841): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 7841): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7841): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7841): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1341): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7841): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7841): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7858): MountEmulatedStorage()
E/Zygote  ( 7858): v2
I/libpersona( 7858): KNOX_SDCARD checking this for 1000
I/libpersona( 7858): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7858 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 6966:com.sec.android.app.taskmanager/u0a175 (adj 15): bgCount ##41
,I/SELinux ( 7858): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7858): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7858): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7858): TimaSignature is unavailable
,D/ActivityThread( 7858): Added TimaKeyStore provider
,W/libprocessgroup(  893): failed to open /acct/uid_10175/pid_6966/cgroup.procs: No such file or directory
,D/ResourcesManager( 7858): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7858): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7858): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7858): premStatus:2
,I/KnoxUsageLogPro( 7858): isEulaShown : false
I/KnoxUsageLogPro( 7858): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7876): MountEmulatedStorage()
E/Zygote  ( 7876): v2
I/libpersona( 7876): KNOX_SDCARD checking this for 10087
I/libpersona( 7876): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7876 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 6981:com.qualcomm.timeservice/1000 (adj 15): bgCount ##41
,I/art     (  323): Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 272us total 11.694ms
,I/SELinux ( 7876): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7876): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7876): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 11.927ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 261us total 8.159ms
,D/TimaKeyStoreProvider( 7876): TimaSignature is unavailable
,W/libprocessgroup(  893): failed to open /acct/uid_1000/pid_6981/cgroup.procs: No such file or directory
D/ActivityThread( 7876): Added TimaKeyStore provider
,D/ResourcesManager( 7876): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/GAV2    ( 7311): Thread[GAThread,5,main]: No campaign data found.
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ActivityManager(  893): Killing 4746:com.android.providers.calendar/u0a45 (adj 15): bgCount ##41
,D/Headlines( 5386): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5386): getCountryCode(): countryCode = PL
,D/Headlines( 5386): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5386): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5386): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5386): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5386): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5386): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5386): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7897): MountEmulatedStorage()
,E/Zygote  ( 7897): v2
I/libpersona( 7897): KNOX_SDCARD checking this for 10127
I/libpersona( 7897): KNOX_SDCARD not a persona
I/ActivityManager(  893): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7897 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7897): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7897): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7897): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7897): TimaSignature is unavailable
,D/ActivityThread( 7897): Added TimaKeyStore provider
,W/libprocessgroup(  893): failed to open /acct/uid_10045/pid_4746/cgroup.procs: No such file or directory
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/ActivityManager(  893): mDVFSHelper.release()
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7897): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7897): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7897): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7897): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7897): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7897): Loading: webviewchromium
,I/LibraryLoader( 7897): Time to load native libraries: 4 ms (timestamps 2275-2279)
I/LibraryLoader( 7897): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7897): Binding Chromium to main looper Looper (main, tid 1) {21f1163f}
,I/LibraryLoader( 7897): Expected native library version number "",actual native library version number ""
,I/chromium( 7897): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7897): Initializing chromium process, renderers=0
,W/art     ( 7897): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7897): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7897): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7897): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7897): Requires BLUETOOTH permission
,I/Adreno-EGL( 7897): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7897): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7897): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7897): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7897): Remote Branch: 
I/Adreno-EGL( 7897): Local Patches: 
I/Adreno-EGL( 7897): Reconstruct Branch: 
,I/dhcpcd  ( 7802): wlan0: acknowledged 192.168.1.136 from 192.168.1.1
,I/NSApplication( 7897): Starting up...
,I/dhcpcd  ( 7802): wlan0: leased 192.168.1.136 for 86400 seconds
,E/WifiStateMachine(  893): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  893): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  893): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/ActivityManager(  893): Killing 7100:com.google.android.partnersetup/u0a14 (adj 15): bgCount ##41
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7968): MountEmulatedStorage()
I/libpersona( 7968): KNOX_SDCARD checking this for 10137
E/Zygote  ( 7968): v2
I/libpersona( 7968): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7968 uid=10137 gids={50137, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7968): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7968): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,W/libprocessgroup(  893): failed to open /acct/uid_10014/pid_7100/cgroup.procs: No such file or directory
E/SELinux ( 7968): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7968): TimaSignature is unavailable
,D/ActivityThread( 7968): Added TimaKeyStore provider
,D/ResourcesManager( 7968): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7968): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7968): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7968): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SMD     (  295): DCD ON
,D/QuickConnect( 7968): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7968): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7968): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7999): MountEmulatedStorage()
E/Zygote  ( 7999): v2
I/libpersona( 7999): KNOX_SDCARD checking this for 10162
I/libpersona( 7999): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7999 uid=10162 gids={50162, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 7119:com.samsung.groupcast/u0a15 (adj 15): bgCount ##41
,I/SELinux ( 7999): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7999): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7999): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7999): TimaSignature is unavailable
,D/ActivityThread( 7999): Added TimaKeyStore provider
,D/ResourcesManager( 7999): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7999): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7999): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7999): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7999): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  893): failed to open /acct/uid_10015/pid_7119/cgroup.procs: No such file or directory
,D/RCPManagerService(  893): exchangeData() failure , invalid userId
,D/RCPManagerService(  893): exchangeData() failure , invalid userId
,D/RCPManagerService(  893): exchangeData() failure , invalid userId
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,D/RCPManagerService(  893): exchangeData() failure , invalid userId
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,E/Zygote  ( 8023): MountEmulatedStorage()
I/libpersona( 8023): KNOX_SDCARD checking this for 10077
E/Zygote  ( 8023): v2
I/libpersona( 8023): KNOX_SDCARD not a persona
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,I/ActivityManager(  893): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8023 uid=10077 gids={50077, 9997} abi=armeabi-v7a
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,I/SELinux ( 8023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
I/SELinux ( 8023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
E/SELinux ( 8023): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,E/WifiStateMachine(  893): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  893): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  893): do suspend true
,D/RCPManagerService(  893): exchangeData() failure , invalid userId
,D/WifiP2pService(  893): InactiveState{ what=143375 }
,D/WifiP2pService(  893): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  893): WifiStateMachine DHCP successful
,D/TimaKeyStoreProvider( 8023): TimaSignature is unavailable
E/WifiStateMachine(  893): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/RCPManagerService(  893): exchangeData() failure , invalid userId
E/WifiStateMachine(  893): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
D/ConnectivityService(  893): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
D/ActivityThread( 8023): Added TimaKeyStore provider
,E/WifiStateMachine(  893): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  893): Not connected state, yet.
E/WifiStateMachine(  893): VerifyingLinkState enter
,D/WifiStateMachine(  893): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  893): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  893): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/WifiNative-HAL(  893): callSECApiInt - ID [210]
,E/WifiStateMachine(  893): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  893): updateNetworkInfo()
,D/ConnectivityService(  893): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  893): Adding iface wlan0 to network 503
,I/ActivityManager(  893): Killing 6343:com.samsung.android.app.galaxyfinder/u0a33 (adj 15): bgCount ##41
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6944): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6944): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6944): StateMachine : Current State = 1
,D/SecurityLogAgent( 6944): StateMachine : Changed Current State = 1
,I/CLocInfoService(  893): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  893): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  893): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  893): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  893): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  893): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/ActivityManager(  893): Killing 4804:com.sec.android.app.shealth/u0a34 (adj 15): bgCount ##41
,E/WifiStateMachine(  893): VerifyingLinkState what=131212 NOT_HANDLED
,E/WifiStateMachine(  893): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  893): updateLinkProperties nid: 0 state: VERIFYING_POOR_LINK reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
E/WifiStateMachine(  893): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine(  893): Now, connected state.
,E/WifiStateMachine(  893): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  893): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  893): Adding Route [fe80::/64 -> :: wlan0] to network 503
I/WifiTrafficPoller(  893): evaluateTrafficStatsPolling
,D/ConnectivityService(  893): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/ConnectivityService(  893): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  893): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  893): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  893): updateSourceRoutes : add src route for:192.168.1.136
,I/CLocInfoService(  893): External Intent Received android.net.wifi.STATE_CHANGE
,D/ResourcesManager( 8023): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,V/        (  290): QcRouteController
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
I/WifiTrafficPoller(  893): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  893): mBoosterFLAG : 0
E/WifiStateMachine(  893): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  893): current booster mode : FullMode
D/WifiNative-HAL(  893): callSECApiVoid - ID [212]
,I/CLocInfoService(  893): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  893): ConnectedState Enter  mScreenOn=false scanperiod=20000
V/BitmapFactory( 7999): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,I/WifiStateMachine(  893): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
V/        (  290): QcRouteController
,V/        (  290): QcRouteController
,D/BadgeProvider( 8023): onCreate
D/BadgeProvider( 8023): DatabaseHelper
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,V/        (  290): QcRouteController
,E/Zygote  ( 8050): MountEmulatedStorage()
,E/Zygote  ( 8050): v2
I/libpersona( 8050): KNOX_SDCARD checking this for 10177
I/libpersona( 8050): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8050 uid=10177 gids={50177, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/        (  290): QcRouteController
,V/        (  290): QcRouteController
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,V/        (  290): QcRouteController
,I/SELinux ( 8050): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/BadgeProvider( 8023): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/SELinux ( 8050): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8050): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,V/        (  290): QcRouteController
,D/BadgeProvider( 8023): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8023): sendNotify, [notify] : null
D/BadgeProvider( 8023): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8023): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 8023): update, [UpdateCount] : 1
,D/Launcher.Model( 1501): reloadBadges entered.
,W/libprocessgroup(  893): failed to open /acct/uid_10033/pid_6343/cgroup.procs: No such file or directory
,W/libprocessgroup(  893): failed to open /acct/uid_10034/pid_4804/cgroup.procs: No such file or directory
,D/ConnectivityService(  893): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  893): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  893): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  893): calling update connectivity
D/ConnectivityService(  893): ignoring duplicate network state non-change
D/ConnectivityService(  893): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/ConnectivityService(  893): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  893): identical MTU - not setting
D/ConnectivityService(  893): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  893): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe63:1186
,V/        (  290): QcRouteController
,V/        (  290): QcRouteController
,D/TimaKeyStoreProvider( 8050): TimaSignature is unavailable
,D/ActivityThread( 8050): Added TimaKeyStore provider
,W/NetworkManagementService(  893): route cmd failed: 
W/NetworkManagementService(  893): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '69 route replace src v6 wlan0 fe80::ee1f:72ff:fe63:1186 2 ::' failed with '400 69 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  893): '
W/NetworkManagementService(  893): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  893): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  893): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  893): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  893): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  893): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  893): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  893): 	at com.android.server.ConnectivityService.access$1900(ConnectivityService.java:230)
W/NetworkManagementService(  893): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  893): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  893): requiresClat: netType=1, connected=false, hasIPv4Address=true
E/ConnectivityService(  893): updateNetworkInfo()
D/ConnectivityService(  893): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  893): updateNetworkInfo()
D/ConnectivityService(  893): calling update connectivity
D/ConnectivityService(  893): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  893): calling update connectivity
D/ConnectivityService(  893): ignoring duplicate network state non-change
D/ConnectivityService(  893): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  893): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  893): calling update connectivity
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  893): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): Connected
D/ConnectivityService(  893):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  893):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): Validated
D/ConnectivityService(  893):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  893):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  893): currentScore = 0, newScore = 60
D/ConnectivityService(  893):    accepting network in place of null
D/ConnectivityService(  893): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1489): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  893): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  893): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  893): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  893): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  893): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  893): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/ConnectivityService(  893): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/SmartBondingService(  893): getSBEnabled() enabled =false
D/SmartBondingService(  893): getSBEnabled() enabled =false
D/SmartBondingService(  893): getSBEnabled() enabled =false
,V/NetworkStats(  893): updateIfacesLocked()
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
V/NetworkStats(  893): performPollLocked(flags=0x1)
D/ConnectivityService(  893): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  893): calling update connectivity
D/NetworkStatsFactory(  893): UpdateStatsForKnox
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  893): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1181): updateDataNetType()
D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
,D/NtpTrustedTime(  893): currentTimeMillis() cache hit
,D/NtpTrustedTime(  893): currentTimeMillis() cache hit
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
V/NetworkStats(  893): performPollLocked() took 4ms
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
V/NetworkStats(  893): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
,D/ConnectivityService(  893):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  893):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  893): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1181): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/ConnectivityService(  893):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  893): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  893): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  893): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  893):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  893):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  893):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  893): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  893): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  893): calling update connectivity
D/ConnectivityService(  893):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  893):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  893): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  893):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  893): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  893): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
,D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 2549): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 2549): CM callback handler got msg 524290
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1181): updateDataNetType()
,D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1181): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ResourcesManager( 8050): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ActivityManager(  893): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  893): Killing 7188:com.samsung.android.sdk.samsunglink/u0a41 (adj 15): bgCount ##41
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7684): notifyNetworkActivated
,W/ContextImpl( 7684): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  893): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/libprocessgroup(  893): failed to open /acct/uid_10041/pid_7188/cgroup.procs: No such file or directory
,D/hcjo    ( 7684): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7684): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7684): exit::IDLE
D/InitializeManagerStateMachine( 7684): entry::NETWORK_CHECK
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7684): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7684): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7684): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7684): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7684): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7684): entry::SUCCESS
D/hcjo    ( 7684): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 1312): Starting #8
,I/Hs20UtilService( 1312): Message received 5007
D/hcjo    ( 7684): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7684): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7684): exit::SUCCESS
D/InitializeManagerStateMachine( 7684): entry::IDLE
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1312): Starting #9
,I/Hs20UtilService( 1312): Message received 5007
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1312): Starting #10
,I/Hs20UtilService( 1312): Message received 5007
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1312): Starting #11
,I/Hs20UtilService( 1312): Message received 5007
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  893): callSECApi what=220
D/WifiStateMachine(  893): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SurfaceFlinger(  257): id=17 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/PowerManagerService(  893): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=893
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/ConnectivityService(  893): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  893): MasterInitialState.processMessage what=3
,D/SmartBondingService(  893): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  893): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  893): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  893): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  893): getSBEnabled() enabled =false
D/SmartBondingService(  893): getSBEnabled() enabled =false
D/SmartBondingService(  893): getSBEnabled() enabled =false
,I/CLocInfoService(  893): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  893): CLocinfo wifi true 
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  893): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2092): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2092): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2243): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3676): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3676): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7704): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 7134): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7134): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7134): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7134): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7760): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7760): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/art     (  893): Explicit concurrent mark sweep GC freed 51366(2MB) AllocSpace objects, 2(32KB) LOS objects, 31% free, 35MB/51MB, paused 1.244ms total 85.023ms
,D/SecContentProvider2(  893): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  893): mCursor = null
,I/FOTA_Client( 7781): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FOTA_Client( 7781): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7781): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.503: ( 7796): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7796): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450240749727
,I/KLMS-2.4.503: ( 7796): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7796): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7796): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7796): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7796): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7818): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 2121): Vacuum at: now=1450240749802 tag=VacuumService
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7171): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6838): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 6838): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6838): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6838): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6838): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6838): [SCU] == networkStateCheck == true
I/SA      ( 6838): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6838): isChinaCountryCode : false
I/SA      ( 6838): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6838): [OR] == networkStateCheck true ==
,I/GAV2    ( 7550): Thread[GAThread,5,main]: No campaign data found.
,I/SA      ( 6838): [OR] GetMyCountryZoneTask
,I/SA      ( 6838): [OR] onReceive END
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 7841): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7841): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/SA      ( 6838): [SRS] prepareGetMyCountryZone
,I/KnoxUsageLogPro( 7858): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7858): premStatus:2
,I/SA      ( 6838): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/KnoxUsageLogPro( 7858): isEulaShown : false
I/KnoxUsageLogPro( 7858): KnoxUsageReceiver onReceive : not Processible, just return
,I/SA      ( 6838): [SSP] query invoked
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6838): [TPMU] GetMccFromDB : null
,I/SA      ( 6838): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6838): [TPM] isNoProxy(default) : true
,D/Headlines( 5386): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5386): getCountryCode(): countryCode = PL
,D/Headlines( 5386): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5386): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5386): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5386): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5386): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5386): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5386): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/File    ( 6838): fail readDirectory() errno=2
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7968): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7968): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7968): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  893): exchangeData() failure , invalid userId
,D/RCPManagerService(  893): exchangeData() failure , invalid userId
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6944): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6944): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6944): StateMachine : Current State = 1
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6944): StateMachine : Changed Current State = 1
,I/ActivityManager(  893): Killing 5767:com.sec.android.gallery3d/u0a47 (adj 15): bgCount ##41
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7684): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7684): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7684): exit::IDLE
,D/InitializeManagerStateMachine( 7684): entry::NETWORK_CHECK
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7684): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7684): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7684): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7684): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7684): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7684): entry::SUCCESS
D/hcjo    ( 7684): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7684): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7684): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7684): exit::SUCCESS
D/InitializeManagerStateMachine( 7684): entry::IDLE
,W/libprocessgroup(  893): failed to open /acct/uid_10047/pid_5767/cgroup.procs: No such file or directory
,D/ConnectivityService(  893): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/SA      ( 6838): [RC New] Execute method=[GET] start
,I/SA      ( 6838): [RC New] Security=[true]
,I/System.out( 6838): Thread-1060(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6838): Thread-1060(ApacheHTTPLog):isShipBuild true
,I/System.out( 6838): Thread-1060(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/jxcore-log( 7298): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 7298): 
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/SA      ( 6838): [RC New] [v2liruge] api execute + 725
,I/SA      ( 6838): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6838): AsyncTask #1 calls detatch()
,I/SA      ( 6838): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6838): [OCP] update openData : PL
,I/SA      ( 6838): [TPMU] getNetworkMcc : 
,I/SA      ( 6838): [SCU] saveMccToPreferece Start
,I/SA      ( 6838): [SCU] RegionMCC : 260
I/SA      ( 6838): [SSP] query invoked
,I/SA      ( 6838): [TPMU] GetMccFromDB : null
,I/SA      ( 6838): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6838): [SCU] saveMccToPreferece End
,I/SA      ( 6838): [RC New] executeRequest [v2liruge] end. 794
,I/SA      ( 6838): [RC New] Execute end
,I/SA      ( 6838): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6838): [OR] GetMyCountryZoneTask Success
,D/SSRM:m  (  893): SIOP:: AP = 410, PST = 370, CUR = 450
,E/SMD     (  295): DCD ON
,D/PackageManager(  893): [MSG] MCS_UNBIND
,I/dhcpcd  ( 7802): wlan0: sending IPv6 Router Solicitation
,I/ActivityManager(  893): Killing 5699:com.android.mms/u0a49 (adj 15): bgCount ##41
,D/CountryDetector(  893): No listener is left
,W/libprocessgroup(  893): failed to open /acct/uid_10049/pid_5699/cgroup.procs: No such file or directory
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/WearableService( 2121): callingUid 10011, callindPid: 2121
,D/ResourcesManager( 7704): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7704): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7704): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 7704): Using the GMSCore's GoogleHttpClient
,D/WearableClient( 7704): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7704): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7704): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7704): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 7704): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 7704): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/MusicLeanback( 7704): Conditions not met for autocaching.
I/MusicLeanback( 7704): Stop autocaching.
,E/ActivityThread( 7704): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@19d2a615 that was originally bound here
E/ActivityThread( 7704): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@19d2a615 that was originally bound here
E/ActivityThread( 7704): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 7704): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 7704): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 7704): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 7704): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 7704): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 7704): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7704): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7704): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7704): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 7704): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 7704): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 7704): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 7704): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 7704): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 7704): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 7704): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 7704): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 7704): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7704): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 7704): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 7704): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7704): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7704): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 7704): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/WifiStateMachine(  893): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  893): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger(  257): id=17 Removed Toast (8/9)
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/PowerManagerService(  893): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 893) eventTime = 116701
,D/PowerManagerService(  893): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=893 (0x0)
,D/PowerManagerService(  893): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=893, ws=WorkSource{10058}) (elapsedTime=3513)
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 1
,I/GAV4    ( 7897): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager(  893): waitForAlarm result :4
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  893): stay LED for fully charged
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhenotypeConfigurator( 2121): Scheduling Phenotype for one-off execution 9499 seconds from now (1450240754253)
,D/GetConfigurationSnapshotOperation( 2121): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2121): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 2121): Using platform SSLCertificateSocketFactory
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7134): mConnectivityHandler : connected
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7134): [hasSamungAccount] - No Samsung Account
,E/SMD     (  295): DCD ON
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7134): [GetString-S]
,I/ReactiveServiceManager( 7134): Supported : 1
,D/QSEECOMAPI: (  893): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: (  893): App is not loaded in QSEE
,D/QSEECOMAPI: (  893): Loaded image: APP id = 2
,D/QSEECOMAPI: (  893): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  893): QSEECom_shutdown_app, app_id = 2
E/terrier (  893): handleString: Failed to handle string(-4)
,E/terrier (  893): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 7134): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7134): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7134): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7134): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7134): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7134): [ensureRegistration] - No Samsung account
,D/LocationManagerService(  893): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 2121): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 2121): (HTTPLog)-Static: isShipBuild true
,I/System.out( 2121): (HTTPLog)-Thread-289-755026824: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 2121): Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 2121, getuid(): 10011
,I/qtaguid ( 2121): Tagging socket 81 with tag 1000120100000000{268440065,0} uid -1, pid: 2121, getuid(): 10011
,D/LocationManagerService(  893): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2121): Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 2121, getuid(): 10011
,D/LocationManagerService(  893): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2121): Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 2121, getuid(): 10011
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/dhcpcd  ( 7802): wlan0: sending IPv6 Router Solicitation
,I/PowerManagerService(  893): [PWL] Off : 15s ago
,E/SMD     (  295): DCD ON,
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/PreloadUpdateManagerStateMachine( 7684): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7684): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7684): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7684): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7684): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7684): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7684): entry::IDLE
,I/dhcpcd  ( 7802): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 7802): wlan0: no IPv6 Routers available
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/PreloadUpdateManagerStateMachine( 7684): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7684): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7684): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7684): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7684): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7684): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7684): entry::IDLE
,E/SMD     (  295): DCD ON
,V/AlarmManager(  893): waitForAlarm result :4
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/Finsky  ( 7613): [1240] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7613): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/SSRM:m  (  893): SIOP:: AP = 350, PST = 360, CUR = 450
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON,
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,E/Watchdog(  893): !@Sync 4
,V/AlarmManager(  893): waitForAlarm result :4
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  893): stay LED for fully charged
D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
I/MotionRecognitionService(  893): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 330, PST = 352, CUR = 450
,I/PowerManagerService(  893): [PWL] Off : 30s ago
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 310, PST = 347, CUR = 450
,E/SMD     (  295): DCD ON
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  893): [PWL] Off : 50s ago
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/SSRM:m  (  893): SIOP:: AP = 310, PST = 344, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 4
,E/Watchdog(  893): !@Sync 5
,E/SMD     (  295): DCD ON
,V/AlarmManager(  893): waitForAlarm result :8
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/SSRM:m  (  893): SIOP:: AP = 300, PST = 340, CUR = 450
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/SSRM:m  (  893): SIOP:: AP = 300, PST = 336, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  893): [PWL] Off : 75s ago
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/SSRM:m  (  893): SIOP:: AP = 290, PST = 331, CUR = 450
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  893): !@Sync 6
,E/SMD     (  295): DCD ON
,I/ClearcutLoggerApiImpl( 2121): disconnect managed GoogleApiClient
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,D/BatteryService(  893): stay LED for fully charged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/SSRM:m  (  893): SIOP:: AP = 290, PST = 326, CUR = 450
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 290, PST = 318, CUR = 450
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  893): [PWL] Off : 105s ago
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,I/Atfwd_Sendcmd(  347): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  347): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:m  (  893): SIOP:: AP = 290, PST = 306, CUR = 450
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/Watchdog(  893): !@Sync 7
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/SSRM:m  (  893): SIOP:: AP = 290, PST = 300, CUR = 450
,E/SMD     (  295): DCD ON
,V/AlarmManager(  893): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 1
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  295): DCD ON
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON,
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/SSRM:m  (  893): SIOP:: AP = 290, PST = 296, CUR = 450
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  893): [PWL] Off : 140s ago
,D/SSRM:m  (  893): SIOP:: AP = 290, PST = 294, CUR = 450
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 3
,E/Watchdog(  893): !@Sync 8
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 290, PST = 292, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/jxcore-log( 7298): Connected to the server!
I/jxcore-log( 7298): 
,I/chromium( 7298): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 290, PST = 291, CUR = 450
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  893): !@Sync 9
,E/SMD     (  295): DCD ON
,V/AlarmManager(  893): waitForAlarm result :8
,I/PowerManagerService(  893): [PWL] Off : 180s ago
,D/SSRM:m  (  893): SIOP:: AP = 270, PST = 288, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/SSRM:m  (  893): SIOP:: AP = 270, PST = 286, CUR = 450
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 270, PST = 284, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  893): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  893): TimaServiceHandler.handleMessage what =1
,D/TimaService(  893): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  893): initializing...
,I/TLC_TIMA_PKM_initialize(  893): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  893): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  893): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  893): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  893): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  893): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  893): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  893): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  893): App is not loaded in QSEE
,D/QSEECOMAPI: (  893): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  893): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  893): Trustlet response is completed
,E/Watchdog(  893): !@Sync 10
,E/SMD     (  295): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  893): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  893): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  893): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  893): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  295): DCD ON,
,D/SSRM:m  (  893): SIOP:: AP = 290, PST = 284, CUR = 450
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  893): stay LED for fully charged
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,I/Atfwd_Sendcmd(  347): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  347): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 270, PST = 282, CUR = 450
,E/SMD     (  295): DCD ON
,V/AlarmManager(  893): waitForAlarm result :4
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0,
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  893): stay LED for fully charged
,I/ActivityManager(  893): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8253 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,E/Zygote  ( 8253): MountEmulatedStorage()
,E/Zygote  ( 8253): v2
I/libpersona( 8253): KNOX_SDCARD checking this for 10080
,I/libpersona( 8253): KNOX_SDCARD not a persona
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
I/MotionRecognitionService(  893): setPowerConnected  = true
,I/SELinux ( 8253): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8253): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8253): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/TimaKeyStoreProvider( 8253): TimaSignature is unavailable
I/PowerManagerService(  893): [PWL] Off : 225s ago
D/ActivityThread( 8253): Added TimaKeyStore provider
I/PowerManagerService(  893): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  893): [PWL]     mWakeLockSummary : 0x1
,D/ResourcesManager( 8253): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ActivityManager(  893): Killing 7233:com.sec.android.app.myfiles/u0a50 (adj 15): bgCount ##41
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/libprocessgroup(  893): failed to open /acct/uid_10050/pid_7233/cgroup.procs: No such file or directory
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 270, PST = 280, CUR = 450
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  893): !@Sync 11
,E/SMD     (  295): DCD ON
,V/AlarmManager(  893): waitForAlarm result :8
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 270, PST = 278, CUR = 450
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 270, PST = 276, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/SSRM:m  (  893): SIOP:: AP = 270, PST = 274, CUR = 450
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  893): !@Sync 12
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 271, CUR = 450
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  893): [PWL] Off : 275s ago
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 270, CUR = 450
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  295): DCD ON
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 269, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  893): !@Sync 13
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 268, CUR = 450
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  893): stay LED for fully charged
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 265, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,D/BatteryService(  893): stay LED for fully charged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 264, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  893): !@Sync 14
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  893): [PWL] Off : 330s ago
,E/SMD     (  295): DCD ON
,I/Atfwd_Sendcmd(  347): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  347): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 263, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 262, CUR = 450
,E/SMD     (  295): DCD ON
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 261, CUR = 450
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  893): !@Sync 15
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/bootchecker(  326): bootchecker wake up!!
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  893): !@Sync 16
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  893): [PWL] Off : 390s ago
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 4
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  893): !@Sync 17
,E/SMD     (  295): DCD ON
,V/AlarmManager(  893): waitForAlarm result :8
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  295): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  893): !@Sync 18
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/Atfwd_Sendcmd(  347): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  347): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  893): [PWL] Off : 455s ago
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,I/Atfwd_Daemon(  347): Stop the daemon....
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  893): !@Sync 19
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,D/BatteryService(  893): stay LED for fully charged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  893): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  893): TimaServiceHandler.handleMessage what =1
,D/TimaService(  893): TIMA: checkEvent, operation: 50000 subject: 10000
,E/Watchdog(  893): !@Sync 20
,E/SMD     (  295): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  893): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  893): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  893): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  893): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  893): [PWL] Off : 525s ago
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  893): stay LED for fully charged
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  893): !@Sync 21
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  893): !@Sync 22
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,E/Watchdog(  893): !@Sync 23
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3230): Disconnected process message: 10
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  893): [PWL] Off : 600s ago
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  893): !@Sync 24
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  893): !@Sync 25
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  893): [PWL] Off : 680s ago
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  893): !@Sync 26
,E/SMD     (  295): DCD ON
,V/AlarmManager(  893): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/LightsService(  893): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  893): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  893): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2549): Aggregate from 1450239300882 (log), 1450239300882 (data)
,E/LightSensor(  893): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  893): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  893): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  893): unregisterListener ::   
D/LightsService(  893): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,E/SMD     (  295): DCD ON
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  893): !@Sync 27
,E/SMD     (  295): DCD ON
,V/AlarmManager(  893): waitForAlarm result :8
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON,
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,D/BatteryService(  893): stay LED for fully charged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  893): !@Sync 28
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,I/PowerManagerService(  893): [PWL] Off : 765s ago
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  893): !@Sync 29
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/TimaService(  893): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  893): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  893): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  893): !@Sync 30
,E/SMD     (  295): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  893): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  893): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  893): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  893): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  893): !@Sync 31
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,I/PowerManagerService(  893): [PWL] Off : 855s ago
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  893): !@Sync 32
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,D/BatteryService(  893): stay LED for fully charged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  893): !@Sync 33
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,V/AlarmManager(  893): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  893): stay LED for fully charged
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
I/MotionRecognitionService(  893): setPowerConnected  = true
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,D/BatteryService(  893): stay LED for fully charged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  893): !@Sync 34
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  893): [PWL] Off : 950s ago
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  893): !@Sync 35
,E/SMD     (  295): DCD ON
,V/AlarmManager(  893): waitForAlarm result :8
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  893): !@Sync 36
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  893): !@Sync 37
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,E/SMD     (  295): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  893): !@Sync 38
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  893): [PWL] Off : 1050s ago
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  893): !@Sync 39
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/TimaService(  893): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  893): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  893): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  893): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  893): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  893): Updating Usage Statistics in DB @ 1450241847786
,I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
,W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
,W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
,W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
,W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  893): ::getAppControlDB: Exception to create DB
W/System.err(  893): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  893): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  893): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  893): Done Updating Usage Statistics in DB @ 1450241848018
,E/Watchdog(  893): !@Sync 40
,E/SMD     (  295): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  893): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  893): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  893): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  893): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,D/BatteryService(  893): stay LED for fully charged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  893): !@Sync 41
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,I/PowerManagerService(  893): [PWL] Off : 1155s ago
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/Watchdog(  893): !@Sync 42
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,D/BatteryService(  893): stay LED for fully charged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  893): !@Sync 43
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  893): !@Sync 44
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/art     (  893): Background sticky concurrent mark sweep GC freed 93662(9MB) AllocSpace objects, 372(5MB) LOS objects, 18% free, 35MB/43MB, paused 1.757ms total 150.056ms
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  893): !@Sync 45
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  893): [PWL] Off : 1265s ago
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  893): !@Sync 46
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  893): !@Sync 47
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  893): Plugged
I/MotionRecognitionService(  893): setPowerConnected  = true
D/BatteryService(  893): stay LED for fully charged
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  893): !@Sync 48
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  893): !@Sync 49
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  893): [PWL] Off : 1380s ago
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/TimaService(  893): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  893): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  893): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,D/BatteryService(  893): stay LED for fully charged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  893): !@Sync 50
,E/SMD     (  295): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  893): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  893): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  893): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  893): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,V/AlarmManager(  893): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/LightsService(  893): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  893): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  893): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/LightSensor(  893): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  893): [SvcLED]  onSensorChanged::light value = 0
E/LightSensor(  893): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  893): unregisterListener ::   
,D/LightsService(  893): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  893): !@Sync 51
,E/SMD     (  295): DCD ON
,V/AlarmManager(  893): waitForAlarm result :8
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  893): !@Sync 52
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  893): !@Sync 53
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  893): [PWL] Off : 1500s ago
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  893): stay LED for fully charged
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  893): !@Sync 54
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  893): !@Sync 55
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  893): !@Sync 56
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  893): !@Sync 57
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,I/PowerManagerService(  893): [PWL] Off : 1625s ago
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  893): !@Sync 58
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,D/BatteryService(  893): stay LED for fully charged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  893): !@Sync 59
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/NetworkStatsFactory(  893): UpdateStatsForKnox
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/TimaService(  893): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  893): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  893): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  893): !@Sync 60
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  893): stay LED for fully charged
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel(  893): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  893): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  893): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  893): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  893): !@Sync 61
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  893): [PWL] Off : 1755s ago
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  893): !@Sync 62
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/Watchdog(  893): !@Sync 63
,E/SMD     (  295): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,E/SMD     (  295): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  295): DCD ON
,V/AlarmManager(  893): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,I/ActivityManager(  893): Killing 7968:com.samsung.android.sconnect/u0a137 (adj 15): empty for 1804s
,I/ActivityManager(  893): Killing 7550:com.google.android.apps.plus/u0a134 (adj 15): empty for 1804s
,I/ActivityManager(  893): Killing 7897:com.google.android.apps.magazines/u0a127 (adj 15): empty for 1804s
,I/ActivityManager(  893): Killing 7876:com.android.chrome/u0a87 (adj 15): empty for 1804s
,I/ActivityManager(  893): Killing 6419:com.sec.chaton/u0a85 (adj 15): empty for 1804s
,I/ActivityManager(  893): Killing 7858:com.sec.knox.bridge/1000 (adj 15): empty for 1804s
,I/ActivityManager(  893): Killing 7841:com.sec.android.widgetapp.ap.hero.accuweather/u0a70 (adj 15): empty for 1804s
,I/ActivityManager(  893): Killing 6838:com.osp.app.signin/u0a44 (adj 15): empty for 1804s
,I/ActivityManager(  893): Killing 7149:com.policydm/1000 (adj 15): empty for 1804s
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  893): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  893): stay LED for fully charged
,V/AlarmManager(  893): waitForAlarm result :8
,I/ActivityManager(  893): Killing 7818:com.sec.android.soagent/u0a36 (adj 15): empty for 1804s
,I/ActivityManager(  893): Killing 7796:com.samsung.klmsagent/u0a18 (adj 15): empty for 1804s
,I/ActivityManager(  893): Killing 7781:com.sec.android.fotaclient/u0a10 (adj 15): empty for 1804s
,I/ActivityManager(  893): Killing 7760:com.sec.android.diagmonagent/1000 (adj 15): empty for 1804s
,I/ActivityManager(  893): Killing 7732:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1804s
,I/ActivityManager(  893): Killing 7134:com.sec.pcw.device/1000 (adj 15): empty for 1804s
,I/ActivityManager(  893): Killing 8023:com.sec.android.provider.badge/u0a77 (adj 15): empty for 1805s
,I/ActivityManager(  893): Killing 7598:com.samsung.android.provider.shootingmodeprovider/u0a169 (adj 15): empty for 1808s
,I/ActivityManager(  893): Killing 7580:com.sec.kidsplat.installer/u0a165 (adj 15): empty for 1808s
,I/ActivityManager(  893): Killing 7518:com.samsung.helphub/1000 (adj 15): empty for 1809s
,I/ActivityManager(  893): Killing 7499:com.samsung.android.magazine.service/u0a117 (adj 15): empty for 1809s
I/ActivityManager(  893): Killing 7483:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): empty for 1809s
,I/ActivityManager(  893): Killing 7467:com.samsung.android.app.filterinstaller/1000 (adj 15): empty for 1810s
,I/ActivityManager(  893): Killing 7443:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty for 1810s
,I/ActivityManager(  893): Killing 7437:com.sec.android.provider.logsprovider/u0a19 (adj 15): empty for 1810s
,V/AlarmManager(  893): waitForAlarm result :8
,I/ActivityManager(  893): Killing 7374:com.sec.android.automotive.drivelink/u0a98 (adj 15): empty for 1810s
,I/ActivityManager(  893): Killing 7404:com.vlingo.midas/u0a32 (adj 15): empty for 1810s
,I/ActivityManager(  893): Killing 7311:com.google.android.apps.docs/u0a97 (adj 15): empty for 1810s
I/ActivityManager(  893): Killing 7273:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1812s
,I/ActivityManager(  893): Killing 7254:com.sec.android.app.soundalive/u0a57 (adj 15): empty for 1812s
,TIME-OUT KILL (timeout was 1800000ms),I/ProcessStatsService(  893): Prepared write state in 11ms
D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
V/NetworkStats(  893): performPollLocked(flags=0x3)
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
D/NetworkStatsFactory(  893): UpdateStatsForKnox
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/NetworkStats(  893): performPollLocked() took 10ms
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  893): Plugged
I/MotionRecognitionService(  893): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3230): Disconnected process message: 10
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/qtaguid ( 2121): Tagging socket 52 with tag 1000040100000000{268436481,0} uid 10011, pid: 2121, getuid(): 10011
I/qtaguid ( 2121): Tagging socket 67 with tag 1000040100000000{268436481,0} uid 10011, pid: 2121, getuid(): 10011
I/ProcessStatsService(  893): Pruning old procstats: /data/system/procstats/state-2015-12-15-18-47-17.bin
W/libprocessgroup(  893): failed to open /acct/uid_10111/pid_7483/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_10098/pid_7374/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_10117/pid_7499/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_10137/pid_7968/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_10134/pid_7550/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_10127/pid_7897/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_10087/pid_7876/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_10085/pid_6419/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_10070/pid_7841/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_1000/pid_7149/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_10044/pid_6838/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_10036/pid_7818/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_10010/pid_7781/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_10018/pid_7796/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_1000/pid_7760/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_10002/pid_7732/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_1000/pid_7134/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_10077/pid_8023/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_10165/pid_7580/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_1000/pid_7518/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_10019/pid_7437/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_10003/pid_7443/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_10032/pid_7404/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_1000/pid_7858/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_10097/pid_7311/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_10057/pid_7254/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_1000/pid_7273/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_10169/pid_7598/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_1000/pid_7467/cgroup.procs: No such file or directory
I/art     ( 2549): Explicit concurrent mark sweep GC freed 40886(2MB) AllocSpace objects, 9(144KB) LOS objects, 25% free, 21MB/28MB, paused 3.803ms total 116.630ms
W/SQLiteConnectionPool( 2549): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
E/SMD     (  295): DCD ON
E/SMD     (  295): DCD ON
D/AndroidRuntime( 8440): 
D/AndroidRuntime( 8440): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8440): CheckJNI is OFF
D/AndroidRuntime( 8440): setted country_code = Poland
D/AndroidRuntime( 8440): setted countryiso_code = PL
D/AndroidRuntime( 8440): setted sales_code = XEO
D/AndroidRuntime( 8440): readGMSProperty: start
D/AndroidRuntime( 8440): readGMSProperty: already setted!!
D/AndroidRuntime( 8440): readGMSProperty: end
D/AndroidRuntime( 8440): addProductProperty: start
E/AffinityControl( 8440): AffinityControl: registerfunction enter
D/AndroidRuntime( 8440): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  893): START PACKAGE DELETE: observer{275623169}
D/PackageManager(  893): pkg{<packageName>}
D/PackageManager(  893): user{0}
D/PackageManager(  893): caller{2000}
D/PackageManager(  893): flags{3}
D/PersonaManagerService(  893): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  893): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  893): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  893): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  893): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  893): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  893): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  893): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  893): getApplicationUninstallationEnabled
D/ApplicationPolicy(  893): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  893): !@killApplicatoin: 10356, uninstall pkg
I/ActivityManager(  893): Force stopping com.test.thalitest appid=10356 user=-1: uninstall pkg
I/ActivityManager(  893): Killing 7298:com.test.thalitest/u0a356 (adj 0): stop com.test.thalitest
I/ActivityManager(  893):   Force finishing activity ActivityRecord{3c0a8135 u0 com.test.thalitest/.MainActivity t4}
W/ActivityManager(  893): mDVFSHelper.acquire()
W/PackageSettings(  893): Skipping PackageSetting{1b994228 com.example.hello/10357} due to missing metadata
D/WifiService(  893): Client connection lost with reason: 4
I/WindowState(  893): WIN DEATH: Window{2b2a0ea3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  257): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SurfaceFlinger(  257): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
I/SurfaceFlinger(  257): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/art     (  893): Background partial concurrent mark sweep GC freed 52384(5MB) AllocSpace objects, 179(3MB) LOS objects, 30% free, 35MB/51MB, paused 2.840ms total 106.159ms
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/ActivityManager(  893): Force stopping com.test.thalitest appid=10356 user=0: pkg removed
I/ActivityManager(  893):   Force finishing activity ActivityRecord{3c0a8135 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager(  893): Duplicate finish request for ActivityRecord{3c0a8135 u0 com.test.thalitest/.MainActivity t4 f}
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/FocusedStackFrame(  893): Set to : 0
I/DBG_DM  ( 3676): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager(  893): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/DBG_DM  ( 3676): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 17
D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
I/InputReader(  893): Reconfiguring input devices.  changes=0x00000010
I/art     ( 1568): Explicit concurrent mark sweep GC freed 33647(2038KB) AllocSpace objects, 1(39KB) LOS objects, 39% free, 16MB/27MB, paused 436us total 32.610ms
E/SamsungIME( 1853): mOCRHelper is null
I/DBG_DM  ( 3676): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
W/GeofencerStateMachine( 2121): Ignoring removeGeofence because network location is disabled.
E/libprocessgroup(  893): failed to kill 1 processes for processgroup 7298
I/DBG_DM  ( 3676): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3676): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 17
I/ActivityManager(  893): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8465 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3676): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
E/Zygote  ( 8465): MountEmulatedStorage()
E/Zygote  ( 8465): v2
I/libpersona( 8465): KNOX_SDCARD checking this for 10018
I/libpersona( 8465): KNOX_SDCARD not a persona
I/art     ( 6222): Explicit concurrent mark sweep GC freed 32625(1759KB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 14MB/24MB, paused 413us total 86.660ms
I/DBG_DM  ( 3676): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
I/SELinux ( 8465): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8465): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
E/SELinux ( 8465): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
I/DBG_DM  ( 3676): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
D/TimaKeyStoreProvider( 8465): TimaSignature is unavailable
D/ActivityThread( 8465): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/SecContentProvider2(  893): uri = 14 selection = getSealedState
D/SecContentProvider2(  893): mCursor = null
D/SecContentProvider2(  893): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  893): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  893): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
I/DBG_DM  ( 3676): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 17
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/SurfaceWidgetView( 1501): destroyHardwareResources():732853489
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/DBG_DM  ( 3676): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/RegisteredServicesCache( 1483): empty dynamic service
V/WindowOrientationListener(  893): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  893): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  893): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  893): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  893): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/SecContentProvider2(  893): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  893): mCursor = null
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/DBG_DM  ( 3676): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3676): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3676): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 3676): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
D/Launcher( 1501): onRestart, Launcher: 159815579
D/Launcher( 1501): onStart, Launcher: 159815579
D/Launcher.HomeView( 1501): onStart
D/ActivityManager(  893): post active user change for 0
D/KnoxTimeoutHandler(  893): postActiveUserChange for user 0
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager( 8465): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2243): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 2243): [237392/6] SurfaceWidget drawing first frame
I/DBG_DM  ( 3676): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
E/ActivityThread( 3676): Performing stop of activity that is not resumed: {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}
E/ActivityThread( 3676): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}
E/ActivityThread( 3676): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3743)
E/ActivityThread( 3676): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3824)
E/ActivityThread( 3676): 	at android.app.ActivityThread.access$1200(ActivityThread.java:172)
E/ActivityThread( 3676): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1451)
E/ActivityThread( 3676): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3676): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3676): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 3676): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3676): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3676): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 3676): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
I/SurfaceFlinger(  257): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
D/StatusBarManagerService(  893): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
I/Timeline( 3676): Timeline: Activity_idle id: android.os.BinderProxy@2a8d6bad time:1923153
I/ActivityManager(  893): Activity reported stop, but no longer stopping: ActivityRecord{21a488d4 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t3}
D/StatusBarManagerService(  893): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/KLMS-2.4.503: ( 8465): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
I/KLMS-2.4.503: ( 8465): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1450242559233
I/KLMS-2.4.503: ( 8465): MainReciver(): PACKAGE_REMOVED
D/Launcher.HomeView( 1501): onStop
D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
I/KLMS-2.4.503: ( 8465): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/InputMethodManagerService(  893): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
W/InputMethodManagerService(  893): Got RemoteException sending setActive(false) notification to pid 7298 uid 10356
W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Books/Books.apk
D/EnterpriseDeviceManagerService(  893): Package has changed for user 0
D/EnterpriseDeviceManagerService(  893): Admin package name: com.google.android.gms
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
I/art     (  893): Explicit concurrent mark sweep GC freed 17815(988KB) AllocSpace objects, 4(64KB) LOS objects, 31% free, 35MB/51MB, paused 8.683ms total 257.437ms
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
W/ActivityManager(  893): mDVFSHelper.release()
I/Timeline(  893): Timeline: Activity_windows_visible id: ActivityRecord{292f67b5 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:1923269
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8486): MountEmulatedStorage()
E/Zygote  ( 8486): v2
I/libpersona( 8486): KNOX_SDCARD checking this for 10103
I/libpersona( 8486): KNOX_SDCARD not a persona
I/ActivityManager(  893): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8486 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  893): Killing 7999:com.android.email/u0a162 (adj 15): empty for 1809s
D/ResourcesManager(  893): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/SELinux ( 8486): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8486): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8486): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Books/Books.apk
D/RCPManagerService(  893): PackageReceiver onReceive()
I/HarmonyEASService(  893): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/KnoxMUMContainerPolicy(  893): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/PackageManager(  893): delete codoeFile: 
D/BackupManagerService(  893): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/libprocessgroup(  893): failed to open /acct/uid_10162/pid_7999/cgroup.procs: No such file or directory
D/JobSchedulerService(  893): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  893): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  893): uID is 10356
V/EnterpriseBillingPolicy(  893): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  893): getProfileForApplication - enter
D/PackageManager(  893): result of delete: 1{275623169}
V/EnterpriseBillingPolicyStorage(  893): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  893): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  893): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  893): getBillingProfileForVpnEngine - start - com.test.thalitest
D/TimaKeyStoreProvider( 8486): TimaSignature is unavailable
D/ActivityThread( 8486): Added TimaKeyStore provider
V/EnterpriseBillingPolicyStorage(  893): getBillingProfileForVpnEngine - end - null
D/KnoxTimeoutHandler(  893): handleActiveUserChange for user 0
D/AndroidRuntime( 8440): Shutting down VM
D/ResourcesManager( 8486): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk

```
