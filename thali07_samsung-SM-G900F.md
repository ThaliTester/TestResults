#### Test 561510938d3c4f5_thali07_samsung-SM-G900F Logs


```
--------- beginning of system
V/AlarmManager(  853): waitForAlarm result :4
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
--------- beginning of main
E/Zygote  ( 7585): MountEmulatedStorage()
E/Zygote  ( 7585): v2
I/libpersona( 7585): KNOX_SDCARD checking this for 10179
I/libpersona( 7585): KNOX_SDCARD not a persona
I/ActivityManager(  853): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler: pid=7585 uid=10179 gids={50179, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
I/SELinux ( 7585): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7585): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
E/SELinux ( 7585): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  853): Plugged
I/MotionRecognitionService(  853): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3261): Disconnected process message: 10
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaKeyStoreProvider( 7585): TimaSignature is unavailable
D/ActivityThread( 7585): Added TimaKeyStore provider
D/ResourcesManager( 7585): creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
W/ResourcesManager( 7585): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/UMC:Core( 7585): onCreate(): 
D/USER_AGENT( 7585): UMC/1.1.39 (SM-G900F) SAFE-5.3 KNOX-2.3
I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  853): CMD_RSSI_POLL : out!
D/[SAMSUNG SMARCART NATIVE]( 7585): initialize...
D/[SAMSUNG SMARCART NATIVE]( 7585): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
I/CSTORAGE( 7585): ================================================
I/CSTORAGE( 7585):  CSTORAGE_SKM_LIB v1.0.8
I/CSTORAGE( 7585): ================================================
I/TZ_CCM_C_GetFunctionList: ( 7585): TZ_CCM_C_GetFunctionList was called
D/[SAMSUNG SMARCART NATIVE]( 7585): FINISHED: initialize rv:0
V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UMC:SecurityUtils( 7585): Loaded server certificates: 0
D/UMC:SecurityUtils( 7585): Loaded server certificates: 0
I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/UMC:SecurityUtils( 7585): timaVersion on the device: 3.0
D/UMC:CloudMDMSecurity( 7585): New Flow
V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TimaService(  853): TIMA3: in ccmRegisterForDefaultCertificate
D/TimaService(  853): TIMA: in getTimaVersion
I/        (  853): CCM JNI: In ccm_register_for_default_cert
I/        (  853): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: (  853): DEBUG_CONTAINER_PROBLEM Enter TZ_CCM_C_Initialize_TLC!
I/TZ_CCM_C_Initialize: (  853): pInitArgs 0x96dfd814 has not called C_Init before.
I/TZ_CCM_C_Initialize: (  853): &ctx = 0x9fa6ec1c
I/TLC_TZ_CCM: (  853): creating new ccm context...
I/TLC_TZ_CCM: (  853): initializing ccm context...
I/TLC_TZ_CCM: (  853): root = /firmware/image, root_strlen = 15
I/TLC_TZ_CCM: (  853): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  853): input max_sendmsg_size = 19420
I/TZ: client_server_communication(  853): input max_recvmsg_size = 19420
I/TZ: client_server_communication(  853): root = /firmware/image, root_len = 15
I/TZ: client_server_communication(  853): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  853): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication(  853): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication(  853): Client_Server_Open was called
I/TZ: client_server_communication(  853): IClientServer::IClientServer()
I/TZ: client_server_communication(  853): BpClientServer::BpClientServer()
I/TZ: client_server_communication(  853): IClientServer::~IClientServer()
I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 1077): OPENSWCONN
I/TZ_CCM_SERVER( 1077): creating new ccm context...
I/TZ_CCM_SERVER( 1077): initializing ccm context...
I/TZ_CCM_SERVER( 1077): root = /firmware/image, root_strlen = 15
I/TZ_CCM_SERVER( 1077): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1077): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1077): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1077): aligned max_sendmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1077): aligned max_recvmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1077): max_message_size = 38912 = 0x9800
D/QSEECOMAPI: ( 1077): QSEECom_get_handle sb_length = 0x9800
D/QSEECOMAPI: ( 1077): App is not loaded in QSEE
D/Finsky  ( 6629): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6629): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6629): [1] 5.onFinished: Scheduling replication attempt 2.
D/QSEECOMAPI: ( 1077): Loaded image: APP id = 3
I/TZ: qc_tlc_communication( 1077): TIMA: path = /firmware/image, fname = tz_ccm, tzapp is loaded
I/TZ: client_server_communication(  853): OpenSWConn(CCM) is successful
I/TZ: client_server_communication(  853): Client_Server_Open succeeded, serverName = CCM
I/TZ_CCM_C_Initialize: (  853): ctx = 0x9fd21e90, comm = 0x9d0f61a8, sendmsg = 0x911f5000, recvmsg = 0x911f9c00
I/TZ_init: (  853): TZ_init: sending initialization request...
I/TZ: client_server_communication(  853): Cmd id = 2, len = 19456
I/TZ: client_server_communication(  853): Calling Communicate()
I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1077): COMM
I/TZ_init: (  853): TZ_init: successful initialization
I/TLC_TZ_COMMON: key_db_init: (  853): Exercising TZ_DB_INIT in TLC
I/TZ: client_server_communication(  853): Cmd id = 17, len = 19456
I/TZ: client_server_communication(  853): Calling Communicate()
I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1077): COMM
I/TZ_COMMON: tlc_key_db_util: (  853): DB Operation suceeded
I/TLC_TZ_CCM: register for default cert: (  853): Exercising TZ_CCM_register_default_TLC
I/TZ: client_server_communication(  853): Cmd id = 25, len = 19456
I/TZ: client_server_communication(  853): Calling Communicate()
I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1077): COMM
I/TLC_TZ_CCM: register for default cert: (  853): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: (  853): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
I/TZ_CCM_C_Finalize: (  853): DEBUG_CONTAINER_PROBLEM Exercising TZ_CCM_C_Finalize_TLC
I/TZ: client_server_communication(  853): Cmd id = 41, len = 19456
I/TZ: client_server_communication(  853): Calling Communicate()
I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1077): COMM
I/TZ: client_server_communication(  853): Client_Server_Close was called
I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(1) 16
I/TZ_CCM_SERVER( 1077): CLOSESWCONN
D/QSEECOMAPI: ( 1077): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1077): QSEECom_shutdown_app, app_id = 3
I/TZ: client_server_communication(  853): Client_Server_Close succeeded
D/UMC:CloudMDMSecurity( 7585): ccmRegisterForDefaultCertificate: 0
D/UMC:CloudMDMSecurity( 7585): TIMA service call for password change success!!
D/AndroidRuntime( 7605): 
D/AndroidRuntime( 7605): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/UMC:AdminManager( 7585): init - start
D/AndroidRuntime( 7605): CheckJNI is OFF
D/UMC:AdminManager( 7585): loadAdmins
D/AndroidRuntime( 7605): setted country_code = Germany
D/AndroidRuntime( 7605): setted countryiso_code = DE
D/AndroidRuntime( 7605): setted sales_code = DBT
D/AndroidRuntime( 7605): readGMSProperty: start
D/AndroidRuntime( 7605): readGMSProperty: already setted!!
D/AndroidRuntime( 7605): readGMSProperty: end
D/AndroidRuntime( 7605): addProductProperty: start
D/UMC:AdminManager( 7585): startPolicyHandlers
I/UMC:TestPolicyHandler( 7585): Setup is called in testpolicyhandler
D/UMC:AdminManager( 7585): init - end
V/UMC:AlarmHandler( 7585): Enter loadList
E/SMD     (  282): DCD ON
D/GSLBManager( 7585): migrateStoredUrlFromOldPref
D/GSLBManager( 7585): migrateStoredUrlFromOldPref : Migration Not Needed
D/UMC:UMCAdmin( 7585): deactivateUMCAdminIfNotRequired : -1
E/UMC:Utils( 7585): Admin not found in package com.samsung.knoxpb.mdm
D/UMC:UMCAdmin( 7585): deactivateUMCAdmin : -1
D/UMC:UMCAdmin( 7585): isContainer : 0
W/LicenseLogService(  853): log() failed
D/EnterpriseDeviceManagerService(  853): isManagedProfileUser(): userId = 0
E/UMC:UMCAdmin( 7585): No active admin owned by uid 10179
D/UMC:UMCAdmin( 7585): isContainer : 0
D/UMC:UMCAdmin( 7585): deactivateUMCAdmin - UMC App Admin deactivated
V/UMC:AlarmHandler( 7585): onReceive :Intent { flg=0x14 cmp=com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler (has extras) }
I/ActivityManager(  853): Killing 4703:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
D/QuickStartReceiver( 7585): Msg Id : 2
D/QuickStartReceiver( 7585): model : SM-G900F
D/QuickStartReceiver( 7585): id : 100
W/libprocessgroup(  853): failed to open /acct/uid_10035/pid_4703/cgroup.procs: No such file or directory
E/AffinityControl( 7605): AffinityControl: registerfunction enter
D/AndroidRuntime( 7605): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  853): inState():  stateMachine is null !!
V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  853): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  853): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  853): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 853  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  853): mDVFSHelper.acquire()
D/FocusedStackFrame(  853): Set to : 0
D/Launcher.HomeView( 1480): onPause
D/Launcher( 1480): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/AndroidRuntime( 7605): Shutting down VM
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
V/TaskCloserActivity( 7327): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/Zygote  ( 7634): MountEmulatedStorage()
E/Zygote  ( 7634): v2
I/libpersona( 7634): KNOX_SDCARD checking this for 10200
I/libpersona( 7634): KNOX_SDCARD not a persona
I/SurfaceFlinger(  249): id=14 createSurf (1x1),1 flag=404, Starting com.test.thalitest
I/ActivityManager(  853): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7634 uid=10200 gids={50200, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7634): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/SELinux ( 7634): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7634): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/StatusBarManagerService(  853): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/MicrophoneInputStream( 1566): mic_close gfk@26a60814
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
V/AudioPolicyManager(  289): stopInput() input 29
V/AudioPolicyManager(  289): releaseInput() 29
V/AudioPolicyManager(  289): closeInput(29)
I/HotwordRecognitionRnr( 1566): Stopping hotword detection.
I/HotwordRecognitionRnr( 1566): Hotword detection finished
V/audio_hw_primary(  289): in_standby: enter
D/TimaKeyStoreProvider( 7634): TimaSignature is unavailable
D/ActivityThread( 7634): Added TimaKeyStore provider
V/WindowOrientationListener(  853): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  853): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  853): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  853): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  853): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  853): Display changed displayId=0
D/Launcher.HomeView( 1480): onStop
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2111): [237392/6] Surface widget pause on instance = 1
D/accuweather( 2111): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2111): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2111): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2111): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/Launcher( 1480): onTrimMemory. Level: 20
D/SurfaceWidgetView( 1480): destroyHardwareResources():1057401600
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
V/audio_hw_primary(  289): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  289): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  289): disable_audio_route: reset mixer path: audio-record
D/audio_route(  289): ++++ audio_route_update_mixer ==============
D/audio_route(  289): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  289): Setting mixer control: value: 0
D/StatusBarManagerService(  853): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/audio_route(  289): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  289): disable_audio_route: exit
V/audio_hw_primary(  289): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  289): ++++ audio_route_update_mixer ==============
D/audio_route(  289): Setting mixer control: DEC2 Volume
D/audio_route(  289): Setting mixer control: value: 0
D/audio_route(  289): Setting mixer control: SLIM TX7 MUX, value: 0
D/audio_route(  289): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  289): Setting mixer control: value: 0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/audio_route(  289): Setting mixer control: DEC2 MUX, value: 0
D/audio_route(  289): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  289): stop_input_stream: exit: status(0)
V/audio_hw_primary(  289): in_standby: exit:  status(0)
V/audio_hw_primary(  289): adev_close_input_stream
V/audio_hw_primary(  289): in_standby: enter
V/audio_hw_primary(  289): in_standby: exit:  status(0)
E/audio_hw_primary(  289): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  289): releaseInput() exit
D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager( 7634): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/SurfaceWidgetView( 1480): destroyHardwareResources():1057401600
D/accuweather( 2111): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/accuweather( 2111): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/WebViewFactory( 7634): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7634): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/LibraryLoader( 7634): Loading: webviewchromium
,I/LibraryLoader( 7634): Time to load native libraries: 2 ms (timestamps 8268-8270)
,I/LibraryLoader( 7634): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7634): Binding Chromium to main looper Looper (main, tid 1) {6a276b3}
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/LibraryLoader( 7634): Expected native library version number "",actual native library version number ""
I/chromium( 7634): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7634): Initializing chromium process, renderers=0
,W/art     ( 7634): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7634): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7634): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium( 7634): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/Adreno-EGL( 7634): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7634): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7634): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7634): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7634): Remote Branch: 
I/Adreno-EGL( 7634): Local Patches: 
I/Adreno-EGL( 7634): Reconstruct Branch: 
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,W/chromium( 7634): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7634): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7634): Attempt to remove local handle scope entry from IRT, ignoring
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
W/AwContents( 7634): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/SystemWebViewEngine( 7634): CordovaWebView is running on device made by: samsung
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,W/art     ( 7634): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 7634): Attempt to remove local handle scope entry from IRT, ignoring
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/Activity( 7634): performCreate Call secproduct feature valuefalse
D/Activity( 7634): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 7634): Render dirty regions requested: true
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/ActivityManager(  853): post active user change for 0
D/KnoxTimeoutHandler(  853): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  853): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
I/OpenGLRenderer( 7634): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7634): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7634): Enabling debug mode 0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/InputMethodManagerService(  853): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
,I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager(  853): Displayed com.test.thalitest/.MainActivity: +620ms
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/Timeline( 7634): Timeline: Activity_idle id: android.os.BinderProxy@137981d2 time:98608
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/PowerManagerService(  853): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1171 (0x0)
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/JsMessageQueue( 7634): Set native->JS mode to OnlineEventsBridgeMode
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,I/chromium( 7634): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7634): 
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/jxcore_app_log( 7634): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1259380864
,D/JX-Cordova( 7634): jxcore cordova android initializing
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/SurfaceFlinger(  249): id=14 Removed Starting com.test.thalitest (7/8)
,I/SurfaceFlinger(  249): id=14 Removed Starting com.test.thalitest (-2/8)
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/CustomFrequencyManagerService(  853): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 853  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  853): mDVFSHelper.release()
I/Timeline(  853): Timeline: Activity_windows_visible id: ActivityRecord{340a0cdc u0 com.test.thalitest/.MainActivity t17} time:98865
,D/CustomFrequencyManagerService(  853): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 853  pkgName : ACTIVITY_RESUME_BOOSTER@10
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/CustomFrequencyManagerService(  853): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 853  tag : ACTIVITY_RESUME_BOOSTER@10
,D/SSRM:m  (  853): SIOP:: AP = 360, PST = 423, CUR = 300
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  853): CMD_RSSI_POLL : out!
,W/jxcore-log( 7634): Initializing JXcore engine
,W/jxcore-log( 7634): JXcore engine is ready
,W/jxcore-log( 7634): Starting JXcore engine
,E/auditd  ( 2152): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  853): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
D/SecurityLogAgent:SEDenialService(  853): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7693): MountEmulatedStorage()
E/Zygote  ( 7693): v2
I/libpersona( 7693): KNOX_SDCARD checking this for 1000
I/libpersona( 7693): KNOX_SDCARD not a persona
,I/ActivityManager(  853): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7693 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7693): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7693): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7693): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7693): TimaSignature is unavailable
,D/ActivityThread( 7693): Added TimaKeyStore provider
,D/ResourcesManager( 7693): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7693):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7693):  SeDenialReceiver : File path = null
,I/ActivityManager(  853): Killing 6826:com.policydm/1000 (adj 15): bgCount ##41
,W/jxcore-log( 7634): Platform android
W/jxcore-log( 7634): 
W/jxcore-log( 7634): Process ARCH arm
W/jxcore-log( 7634): 
,E/SMD     (  282): DCD ON
,W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_6826/cgroup.procs: No such file or directory
,I/jxcore-log( 7634): JXcore Cordova bridge is ready!
I/jxcore-log( 7634): 
W/jxcore-log( 7634): JXcore engine is started
,E/Adreno-ES20( 7634): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7634): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/jxcore-log( 7634): Toggling radios to true
I/jxcore-log( 7634): 
,D/BluetoothAdapter( 7634): enable()
,D/BluetoothAdapter( 7634): enable(): BT is already enabled..!
,D/WifiService(  853): New client listening to asynchronous messages
,I/WifiManager( 7634): packageName : com.test.thalitest
,D/SecContentProvider(  853): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  853): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  853): mCursor = null
,D/WifiService(  853): setWifiEnabled: true pid=7634, uid=10200
,E/WifiService(  853): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  853): Permission Denial: getCurrentUser() from pid=7634, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  853): Failed getting userId using ActivityManagerNative
W/WifiService(  853): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7634, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  853): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  853): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  853): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  853): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  853): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  853): name = wifi_on
I/WifiService(  853): disconnect: pid=7634, uid=10200
,I/wpa_supplicant( 1304): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7634): Radios toggled
I/jxcore-log( 7634): 
,I/jxcore-log( 7634): My device name is: samsung-SM-G900F
I/jxcore-log( 7634): 
,I/wpa_supplicant( 1304): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1304): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1304): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1304): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine(  853): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1304): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1304): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1304): Disconnected - do not scan
I/wpa_supplicant( 1304): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  853): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
,E/WifiStateMachine(  853): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  853): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  853): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  853): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  853): InactiveState{ what=143375 }
,D/WifiP2pService(  853): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1677): Read error: ssl=0xaed34e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1677): SSL shutdown failed: ssl=0xaed34e00: I/O error during system call, Broken pipe
,E/WifiStateMachine(  853): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  853): updateNetworkInfo()
,D/ConnectivityService(  853): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  853): updateNetworkInfo()
D/ConnectivityService(  853): ignoring duplicate network state non-change
,D/ConnectivityService(  853): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,E/WifiConfigStore(  853): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller(  853): evaluateTrafficStatsPolling
,I/CLocInfoService(  853): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  853): Start Disconnecting Watchdog 1
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  853): ValidatedState{ when=-2ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  853): DefaultState{ when=-4ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  853): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  853): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  853): Validated
,I/wpa_supplicant( 1304): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1304): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1304): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1304): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1304): First Scan Start
,I/wpa_supplicant( 1304): Scan requested (ret=0) - scan timeout 30 seconds
D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Hs20UtilService( 1301): Starting #6
E/WifiStateMachine(  853): ConnectModeState: Network connection lost 
I/Hs20UtilService( 1301): Message received 5007
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  853): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,E/WifiStateMachine(  853): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiP2pService(  853): InactiveState{ what=143375 }
D/WifiP2pService(  853): P2pEnabledState{ what=143375 }
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1301): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1301): MountReceiver.mPrefHandler - 7002
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,D/ConnectivityService(  853): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  853): calling update connectivity
,D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  853): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/EntConnectivity(  853): Not allowed due to - mEnabled false
,D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524292
,E/WifiStateMachine(  853): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/Nat464Xlat(  853): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/WifiStateMachine(  853): updateConfiguredNetworkExpiration - currTime: 1452860411294
D/WifiStateMachine(  853): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  853): ValidatedState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  853): DefaultState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  853): Disconnected - quitting
I/WifiTrafficPoller(  853): evaluateTrafficStatsPolling
,E/WifiStateMachine(  853): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
,E/WifiStateMachine(  853): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  853): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/CLocInfoService(  853): External Intent Received android.net.wifi.STATE_CHANGE
D/ConnectivityService(  853): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  853): NetworkAgent: NetworkAgent channel lost
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CSLegacyTypeTracker(  853): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  853): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/TelephonyNetworkFactory( 1474): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine(  853): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  853): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  853): setDetailed state send new extra info"NG700"
D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SecContentProvider2(  853): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  853): mCursor = null
,D/ConnectivityService(  853): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  853): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,V/NetworkStats(  853): updateIfacesLocked()
,V/NetworkStats(  853): performPollLocked(flags=0x1)
D/NtpTrustedTime(  853): currentTimeMillis() cache hit
,D/NtpTrustedTime(  853): currentTimeMillis() cache hit
,E/ConnectivityService(  853): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/NtpTrustedTime(  853): currentTimeMillis() cache hit
D/SmartBondingService(  853): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/NtpTrustedTime(  853): currentTimeMillis() cache hit
D/NtpTrustedTime(  853): currentTimeMillis() cache hit
V/NetworkStats(  853): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/SmartBondingService(  853): getSBEnabled() enabled =false
D/StatusBar.NetworkController( 1171): getUpdateDataNetType(): 0
D/SmartBondingService(  853): getSBEnabled() enabled =false
D/StatusBar.NetworkController( 1171): updateDataNetType()
D/SmartBondingService(  853): getSBEnabled() enabled =false
D/StatusBar.NetworkController( 1171): NoService, mRoamingIconId = 0
,D/NetworkStatsFactory(  853): UpdateStatsForKnox
D/ConnectivityService(  853): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  853): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  853): mCursor = null
,D/SmartBondingService(  853): getNetworkEnabled : wifi : true mobile : true
,D/StatusBar.NetworkController( 1171): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,V/NetworkStats(  853): performPollLocked() took 10ms
,D/NtpTrustedTime(  853): currentTimeMillis() cache hit
,I/Hs20UtilService( 1301): Starting #7
,I/Hs20UtilService( 1301): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
,D/NtpTrustedTime(  853): currentTimeMillis() cache hit
D/NtpTrustedTime(  853): currentTimeMillis() cache hit
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1301): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1301): MountReceiver.mPrefHandler - 7002
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  853): updateDataUsageMap
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  853): MasterInitialState.processMessage what=3
,D/SmartBondingService(  853): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  853): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  853): getSBEnabled() enabled =false
D/SmartBondingService(  853): getSBEnabled() enabled =false
D/SmartBondingService(  853): getSBEnabled() enabled =false
,I/CLocInfoService(  853): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  853): CLoinfo wifi false
,D/accuweather( 2111): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,W/SLocation(  853): No Active Data Connection
,D/SmartBondingService(  853): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5359): type=WIFI subType= reason=null isConnected=false
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,I/SystemBroadcastReceiver( 7199): [#DCM#] [DCM_Performance] onReceive completed in time  1119 microsec. 
,I/SystemBroadcastReceiver( 7199): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7199): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7199): [#DCM#] setIsConnectedForExtractors 
,I/DBG_DM  ( 3789): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,E/Zygote  ( 7760): MountEmulatedStorage()
E/Zygote  ( 7760): v2
I/libpersona( 7760): KNOX_SDCARD checking this for 1000
I/libpersona( 7760): KNOX_SDCARD not a persona
,I/ActivityManager(  853): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7760 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SELinux ( 7760): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/DBG_DM  ( 3789): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
I/SELinux ( 7760): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7760): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7760): TimaSignature is unavailable
,D/ActivityThread( 7760): Added TimaKeyStore provider
,D/ResourcesManager( 7760): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG( 7760): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7760): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7760): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 7760): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7760): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7760): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7760): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7760): noConnectivity : true
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7782): MountEmulatedStorage()
E/Zygote  ( 7782): v2
I/libpersona( 7782): KNOX_SDCARD checking this for 10002
I/libpersona( 7782): KNOX_SDCARD not a persona
,I/ActivityManager(  853): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7782 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 5244:com.sec.spp.push/u0a38 (adj 15): bgCount ##41
,I/SELinux ( 7782): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7782): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7782): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7782): TimaSignature is unavailable
,D/ActivityThread( 7782): Added TimaKeyStore provider
,D/ResourcesManager( 7782): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,W/libprocessgroup(  853): failed to open /acct/uid_10038/pid_5244/cgroup.procs: No such file or directory
,I/ActivityManager(  853): Killing 6116:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  853): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7799 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 7799): MountEmulatedStorage()
I/libpersona( 7799): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7799): v2
I/libpersona( 7799): KNOX_SDCARD not a persona
,I/SELinux ( 7799): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7799): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7799): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7799): TimaSignature is unavailable
,D/ActivityThread( 7799): Added TimaKeyStore provider
,W/libprocessgroup(  853): failed to open /acct/uid_10042/pid_6116/cgroup.procs: No such file or directory
,D/ResourcesManager( 7799): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7799): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7799): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/wpa_supplicant( 1304): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 1304): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1304): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1304): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1304): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
E/WifiStateMachine(  853): [1,452,860,412,324 ms] noteScanEnd no scan source
,E/WifiStateMachine(  853): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@30c37300 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  853): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  853): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  853): setDetailed state send new extra info0x
,D/SecContentProvider2(  853): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  853): mCursor = null
,I/CLocInfoService(  853): External Intent Received android.net.wifi.SCAN_RESULTS
,D/PowerManagerService(  853): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  853): getFinalBrightness : 15 -> 15
,D/PowerManagerService(  853): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  853): lcd : 37 +
,D/lights  (  853): lcd : 37 -
,D/lights  (  853): lcd : 29 +
,I/DIAGMON_AGENT( 7799): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,D/lights  (  853): lcd : 29 -
,I/DIAGMON_AGENT( 7799): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7799): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7799): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/lights  (  853): lcd : 20 +
,D/lights  (  853): lcd : 20 -
,I/wpa_supplicant( 1304): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1304): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine(  853): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  853): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
I/wpa_supplicant( 1304): Associated with C0.AA.48
,D/SecContentProvider2(  853): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  853): mCursor = null
,D/DisplayPowerController(  853): getFinalBrightness : 15 -> 15
,D/lights  (  853): lcd : 15 +
,D/lights  (  853): lcd : 15 -
,D/DisplayPowerController(  853): getFinalBrightness : 15 -> 15
,I/wpa_supplicant( 1304): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1304): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  853): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  853): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  853): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  853): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  853): mCursor = null
,I/wpa_supplicant( 1304): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1304): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1304): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  853): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  853): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 1304): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1304): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1304): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1304): Blacklist: Clear (temp) 
I/wpa_supplicant( 1304): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  853): Network connection established
,D/WifiNative-HAL(  853): callSECApiVoid - ID [50]
,E/WifiStateMachine(  853): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  853): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService(  853): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  853): Got NetworkAgent Messenger
,D/ConnectivityService(  853): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  853): updateNetworkInfo()
D/ConnectivityService(  853): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  853): NetworkAgent connected
E/WifiStateMachine(  853): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  853): L2ConnectedState "NG700" nid=0
,E/WifiConfigStore(  853): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/CLocInfoService(  853): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  853): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  853): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  853): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  853): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,D/CommandListener(  277): Setting iface cfg
,E/WifiStateMachine(  853): Start Dhcp Watchdog 2
,D/SecContentProvider2(  853): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  853): mCursor = null
,E/Zygote  ( 7824): MountEmulatedStorage()
,E/Zygote  ( 7824): v2
I/libpersona( 7824): KNOX_SDCARD checking this for 10011
I/libpersona( 7824): KNOX_SDCARD not a persona
,I/ActivityManager(  853): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7824 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore in!
E/WifiStateMachine(  853): calculateWifiScore() report new score 60
I/WifiStateMachine(  853): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  853): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  853): CMD_RSSI_POLL : out!
,D/ConnectivityService(  853): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,E/WifiStateMachine(  853): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  853): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  853): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/SELinux ( 7824): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7824): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7824): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7824): TimaSignature is unavailable
,D/ActivityThread( 7824): Added TimaKeyStore provider
,D/ResourcesManager( 7824): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,E/WifiStateMachine(  853): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  853): do suspend false
,D/SecContentProvider2(  853): uri = 20 selection = getPromptCredentialsEnabled
,D/WifiP2pService(  853): InactiveState{ what=143375 }
,D/WifiP2pService(  853): P2pEnabledState{ what=143375 }
D/SecContentProvider2(  853): mCursor = null
,I/ActivityManager(  853): Killing 6846:com.osp.app.signin/u0a45 (adj 15): bgCount ##41
,I/FOTA_Client( 7824): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7824): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7824): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7824): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7824): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7839): MountEmulatedStorage()
E/Zygote  ( 7839): v2
I/libpersona( 7839): KNOX_SDCARD checking this for 10019
I/libpersona( 7839): KNOX_SDCARD not a persona
,I/ActivityManager(  853): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7839 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  853): Killing 6867:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,I/art     (  312): Explicit concurrent mark sweep GC freed 8735(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 270us total 12.974ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 247us total 8.263ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 7.592ms
,I/SELinux ( 7839): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  853): failed to open /acct/uid_10045/pid_6846/cgroup.procs: No such file or directory
,I/SELinux ( 7839): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7839): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7839): TimaSignature is unavailable
,D/ActivityThread( 7839): Added TimaKeyStore provider
,D/ResourcesManager( 7839): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,W/libprocessgroup(  853): failed to open /acct/uid_10051/pid_6867/cgroup.procs: No such file or directory
,I/KLMS-2.4.503: ( 7839): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7839): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452860412719
,I/KLMS-2.4.503: ( 7839): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7839): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7839): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  853): Killing 6886:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7855): MountEmulatedStorage()
E/Zygote  ( 7855): v2
I/libpersona( 7855): KNOX_SDCARD checking this for 10037
I/libpersona( 7855): KNOX_SDCARD not a persona
,I/ActivityManager(  853): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7855 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7855): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7855): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7855): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/dhcpcd  ( 7861): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7861): version 5.5.6 starting
,E/dhcpcd  ( 7861): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,W/libprocessgroup(  853): failed to open /acct/uid_10058/pid_6886/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7855): TimaSignature is unavailable
,D/ActivityThread( 7855): Added TimaKeyStore provider
,D/ResourcesManager( 7855): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/dhcpcd  ( 7861): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7861): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7861): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7861): bssid match
,I/dhcpcd  ( 7861): wlan0: rebinding lease of 192.168.1.135
,I/SO_AGENT( 7855): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7877): MountEmulatedStorage()
E/Zygote  ( 7877): v2
,I/libpersona( 7877): KNOX_SDCARD checking this for 1000
I/libpersona( 7877): KNOX_SDCARD not a persona
,I/ActivityManager(  853): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7877 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 6279:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/SELinux ( 7877): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7877): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7877): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7877): TimaSignature is unavailable
,D/ActivityThread( 7877): Added TimaKeyStore provider
,D/ResourcesManager( 7877): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_6279/cgroup.procs: No such file or directory
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7900): MountEmulatedStorage()
I/libpersona( 7900): KNOX_SDCARD checking this for 10038
E/Zygote  ( 7900): v2
I/libpersona( 7900): KNOX_SDCARD not a persona
,I/ActivityManager(  853): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7900 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 6560:com.sec.chaton/u0a86 (adj 15): bgCount ##41
,I/SELinux ( 7900): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7900): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SELinux ( 7900): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7900): TimaSignature is unavailable
,D/ActivityThread( 7900): Added TimaKeyStore provider
,W/libprocessgroup(  853): failed to open /acct/uid_10086/pid_6560/cgroup.procs: No such file or directory
,D/ResourcesManager( 7900): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService( 7900): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 7900): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7900): PushLog.txt file is not deleted.
D/SPPClientService( 7900): PushLog.txt file is not deleted.
D/SPPClientService( 7900): ============PushLog. stop!
,E/SPPClientService( 7900): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7916): MountEmulatedStorage()
,E/Zygote  ( 7916): v2
I/libpersona( 7916): KNOX_SDCARD checking this for 10045
I/libpersona( 7916): KNOX_SDCARD not a persona
,I/ActivityManager(  853): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7916 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 6905:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,I/SELinux ( 7916): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7916): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7916): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,E/SPPClientService( 7900): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider( 7916): TimaSignature is unavailable
,D/ActivityThread( 7916): Added TimaKeyStore provider
,D/ResourcesManager( 7916): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,W/libprocessgroup(  853): failed to open /acct/uid_10098/pid_6905/cgroup.procs: No such file or directory
,I/SA      ( 7916): [SSP] onCreated
,I/SA      ( 7916): [TPM] There is no property file
,I/SA      ( 7916): [SCU] isHaveSA() - false
,I/SA      ( 7916): [TPM] getModelProperty : null
,I/SA      ( 7916): [TPM] getCSCProperty : null
,I/SA      ( 7916): [DM] init START
,I/SA      ( 7916): [DM] This device is not a Vodafone
,W/ResourceType( 7916): Failure getting entry for 0x7f06000f (t=5 e=15) (error -75)
,W/ResourceType( 7916): Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,W/ResourceType( 7916): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 7916): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 7916): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 7916): Failure getting entry for 0x7f060001 (t=5 e=1) (error -75)
,W/ResourceType( 7916): Failure getting entry for 0x7f060013 (t=5 e=19) (error -75)
,W/ResourceType( 7916): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7916): Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,W/ResourceType( 7916): Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
W/ResourceType( 7916): Failure getting entry for 0x7f060024 (t=5 e=36) (error -75)
,W/ResourceType( 7916): Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
W/ResourceType( 7916): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,W/ResourceType( 7916): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7916): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 7916): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 7916): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 7916): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 7916): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 7916): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,E/SMD     (  282): DCD ON
,I/SA      ( 7916): [SCU] isHaveSA() - false
,I/SA      ( 7916): support phone number id : false
I/SA      ( 7916): [DM] init END
,I/SA      ( 7916): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7916): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 7916): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 7916): [SLFUCHKMGR] constructor called
,I/SA      ( 7916): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7916): [OR] == isSIMCardReady false ==
,I/SA      ( 7916): [SCU] == networkStateCheck == false
I/SA      ( 7916): [OR] onReceive END
,I/ActivityManager(  853): Killing 6955:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,D/accuweather( 7408): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7408): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
D/accuweather( 7408): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
D/accuweather( 7408): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7408): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7408): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7408): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7408): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1328): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7408): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7408): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7937): MountEmulatedStorage()
I/libpersona( 7937): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7937): v2
I/libpersona( 7937): KNOX_SDCARD not a persona
,I/ActivityManager(  853): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7937 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,V/AlarmManager(  853): waitForAlarm result :4
,I/SELinux ( 7937): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  853): failed to open /acct/uid_10033/pid_6955/cgroup.procs: No such file or directory
,I/SELinux ( 7937): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7937): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7937): TimaSignature is unavailable
,D/ActivityThread( 7937): Added TimaKeyStore provider
,E/Watchdog(  853): !@Sync 3
,D/ResourcesManager( 7937): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7937): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7937): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7937): premStatus:2
,I/KnoxUsageLogPro( 7937): isEulaShown : false
,I/KnoxUsageLogPro( 7937): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7953): MountEmulatedStorage()
,E/Zygote  ( 7953): v2
I/libpersona( 7953): KNOX_SDCARD checking this for 10086
I/libpersona( 7953): KNOX_SDCARD not a persona
,I/ActivityManager(  853): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.NetStateReceiver: pid=7953 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 6935:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,I/SELinux ( 7953): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7953): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7953): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7953): TimaSignature is unavailable
,D/ActivityThread( 7953): Added TimaKeyStore provider
,D/ResourcesManager( 7953): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7953): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  853): failed to open /acct/uid_10099/pid_6935/cgroup.procs: No such file or directory
,D/PushModule( 7953): [PushClientApplication] (main) PushClientApplication.onCreate()
,I/PushModule( 7953): [PushClientApplication] (main) PushModule version: 0.9.01.12
,D/PushModule( 7953): [PushClientApplication] (main) Discovered public push client. disable in app push client.
,D/ChatON  ( 7953): [1][isApplicationInstalled] com.android.mms was installed
,W/ContextImpl( 7953): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
,W/ActivityManager(  853): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,D/ChatON  ( 7953): [1][a] ChatONV isn't installed.
D/ChatON  ( 7953): [1][a] ChatONVPlugIn.isAvailable()
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7975): MountEmulatedStorage()
,E/Zygote  ( 7975): v2
I/libpersona( 7975): KNOX_SDCARD checking this for 10088
I/libpersona( 7975): KNOX_SDCARD not a persona
,I/ActivityManager(  853): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7975 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 7005:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,I/SELinux ( 7975): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7975): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7975): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7975): TimaSignature is unavailable
,D/ActivityThread( 7975): Added TimaKeyStore provider
,W/libprocessgroup(  853): failed to open /acct/uid_10020/pid_7005/cgroup.procs: No such file or directory
,D/ResourcesManager( 7975): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/ActivityManager(  853): Killing 6999:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,D/Headlines( 5502): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 5502): getCountryCode(): countryCode = DE
,D/Headlines( 5502): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5502): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5502): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5502): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5502): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5502): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5502): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7991): MountEmulatedStorage()
I/libpersona( 7991): KNOX_SDCARD checking this for 10128
E/Zygote  ( 7991): v2
I/libpersona( 7991): KNOX_SDCARD not a persona
,I/ActivityManager(  853): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7991 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7991): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  853): failed to open /acct/uid_10003/pid_6999/cgroup.procs: No such file or directory
,I/SELinux ( 7991): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7991): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7991): TimaSignature is unavailable
,D/ActivityThread( 7991): Added TimaKeyStore provider
,D/ResourcesManager( 7991): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7991): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7991): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7991): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7991): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/dhcpcd  ( 7861): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,I/dhcpcd  ( 7861): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  853): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  853): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  853): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/WebViewFactory( 7991): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7991): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7991): Loading: webviewchromium
,I/LibraryLoader( 7991): Time to load native libraries: 4 ms (timestamps 4498-4502)
,I/LibraryLoader( 7991): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7991): Binding Chromium to main looper Looper (main, tid 1) {5ecb1a9}
,I/LibraryLoader( 7991): Expected native library version number "",actual native library version number ""
,I/chromium( 7991): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7991): Initializing chromium process, renderers=0
W/art     ( 7991): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7991): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7991): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7991): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7991): Requires BLUETOOTH permission
,I/Choreographer( 7634): Skipped 194 frames!  The application may be doing too much work on its main thread.
,I/Adreno-EGL( 7991): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7991): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7991): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7991): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7991): Remote Branch: 
I/Adreno-EGL( 7991): Local Patches: 
I/Adreno-EGL( 7991): Reconstruct Branch: 
,I/chromium( 7634): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/NSApplication( 7991): Starting up...
,I/chromium( 7634): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/WifiStateMachine(  853): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  853): InactiveState{ what=143375 }
D/WifiP2pService(  853): P2pEnabledState{ what=143375 }
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  853): WifiStateMachine DHCP successful
,E/WifiStateMachine(  853): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  853): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
D/ConnectivityService(  853): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/Zygote  ( 8074): MountEmulatedStorage()
,E/Zygote  ( 8074): v2
I/libpersona( 8074): KNOX_SDCARD checking this for 10138
I/libpersona( 8074): KNOX_SDCARD not a persona
,I/ActivityManager(  853): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=8074 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 7029:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,E/WifiStateMachine(  853): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  853): Not connected state, yet.
E/WifiStateMachine(  853): VerifyingLinkState enter
,I/SELinux ( 8074): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/SELinux ( 8074): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/WifiStateMachine(  853): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  853): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  853): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  853): callSECApiInt - ID [210]
,E/SELinux ( 8074): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/WifiStateMachine(  853): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  853): updateNetworkInfo()
,I/CLocInfoService(  853): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  853): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine(  853): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  853): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  853): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  853): Adding iface wlan0 to network 503
D/WifiWatchdogStateMachine.SingDnsChecker(  853): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  853): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,E/WifiStateMachine(  853): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  853): Now, connected state.
E/WifiStateMachine(  853): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
I/WifiTrafficPoller(  853): evaluateTrafficStatsPolling
E/WifiStateMachine(  853): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
I/CLocInfoService(  853): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/WifiTrafficPoller(  853): evaluateTrafficStatsPolling
D/ConnectivityService(  853): Adding Route [fe80::/64 -> :: wlan0] to network 503
,I/WifiTrafficPoller(  853): mBoosterFLAG : 0
,I/WifiTrafficPoller(  853): current booster mode : FullMode
D/ConnectivityService(  853): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
E/WifiStateMachine(  853): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/WifiNative-HAL(  853): callSECApiVoid - ID [212]
,D/ConnectivityService(  853): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
I/CLocInfoService(  853): External Intent Received android.net.wifi.STATE_CHANGE
,E/ConnectivityService(  853): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  853): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  853): updateSourceRoutes : add src route for:192.168.1.135
,V/        (  277): QcRouteController
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/WifiStateMachine(  853): ConnectedState Enter  mScreenOn=true scanperiod=20000
,I/WifiStateMachine(  853): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,V/        (  277): QcRouteController
,V/        (  277): QcRouteController
,W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_7029/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8074): TimaSignature is unavailable
,D/ActivityThread( 8074): Added TimaKeyStore provider
,V/        (  277): QcRouteController
,D/ResourcesManager( 8074): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,V/        (  277): QcRouteController
,W/ResourcesManager( 8074): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8074): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8074): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,V/        (  277): QcRouteController
,V/        (  277): QcRouteController
,V/        (  277): QcRouteController
,D/QuickConnect( 8074): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  853): Setting Dns servers for network 503 to [/192.168.1.1]
I/QuickConnect( 8074): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,D/Nat464Xlat(  853): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  853): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  853): updateNetworkInfo()
D/ConnectivityService(  853): calling update connectivity
E/ConnectivityService(  853): updateNetworkInfo()
D/ConnectivityService(  853): ignoring duplicate network state non-change
D/ConnectivityService(  853): ignoring duplicate network state non-change
D/ConnectivityService(  853): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  853): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  853): calling update connectivity
D/ConnectivityService(  853): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  853):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  853):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  853):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853): currentScore = 0, newScore = 60
D/ConnectivityService(  853):    accepting network in place of null
D/ConnectivityService(  853): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  853): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  853): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  853): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  853): Validated
,E/CSLegacyTypeTracker(  853): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  853): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 1474): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  853): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/EntConnectivity(  853): Not allowed due to - mEnabled false
D/SmartBondingService(  853): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  853): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  853): calling update connectivity
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/SmartBondingService(  853): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  853): getSBEnabled() enabled =false
D/SmartBondingService(  853): getSBEnabled() enabled =false
D/SmartBondingService(  853): getSBEnabled() enabled =false
D/ConnectivityService(  853): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  853): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  853): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  853):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  853):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  853): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  853): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  853): calling update connectivity
V/NetworkStats(  853): updateIfacesLocked()
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkStats(  853): performPollLocked(flags=0x1)
D/NtpTrustedTime(  853): currentTimeMillis() cache hit
D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  853): getNetworkEnabled : wifi : true mobile : true
D/StatusBar.NetworkController( 1171): getUpdateDataNetType(): 0
D/NtpTrustedTime(  853): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1171): updateDataNetType()
D/StatusBar.NetworkController( 1171): NoService, mRoamingIconId = 0
D/NetworkStatsFactory(  853): UpdateStatsForKnox
D/ConnectivityService(  853): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  853): currentTimeMillis() cache hit
D/NtpTrustedTime(  853): currentTimeMillis() cache hit
V/NetworkStats(  853): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  853): currentTimeMillis() cache hit
D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524290
D/ConnectivityService(  853): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/StatusBar.NetworkController( 1171): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524290
V/NetworkStats(  853): performPollLocked() took 6ms
D/NtpTrustedTime(  853): currentTimeMillis() cache hit
D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1171): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1171): updateDataNetType()
D/StatusBar.NetworkController( 1171): NoService, mRoamingIconId = 0
D/StatusBar.NetworkController( 1171): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/NtpTrustedTime(  853): currentTimeMillis() cache hit
D/NtpTrustedTime(  853): currentTimeMillis() cache hit
I/QuickConnect( 8074): PeriphStartReceiver.onReceive - no need to start
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8106): MountEmulatedStorage()
E/Zygote  ( 8106): v2
I/libpersona( 8106): KNOX_SDCARD checking this for 10163
I/libpersona( 8106): KNOX_SDCARD not a persona
I/ActivityManager(  853): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=8106 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager(  853): Killing 7052:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
I/SELinux ( 8106): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8106): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8106): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8106): TimaSignature is unavailable
W/libprocessgroup(  853): failed to open /acct/uid_10112/pid_7052/cgroup.procs: No such file or directory
,D/ActivityThread( 8106): Added TimaKeyStore provider
,D/ResourcesManager( 8106): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8106): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8106): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8106): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8106): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManagerService(  853): exchangeData() failure , invalid userId
,D/RCPManagerService(  853): exchangeData() failure , invalid userId
,D/RCPManagerService(  853): exchangeData() failure , invalid userId
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  853): exchangeData() failure , invalid userId
,E/Zygote  ( 8129): MountEmulatedStorage()
I/libpersona( 8129): KNOX_SDCARD checking this for 10078
E/Zygote  ( 8129): v2
I/libpersona( 8129): KNOX_SDCARD not a persona
,I/ActivityManager(  853): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8129 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/art     (  312): Explicit concurrent mark sweep GC freed 8743(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 275us total 12.059ms
,I/SELinux ( 8129): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8129): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8129): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 267us total 7.954ms
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
D/RCPManagerService(  853): exchangeData() failure , invalid userId
,D/RCPManagerService(  853): exchangeData() failure , invalid userId
V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 256us total 8.157ms
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,D/TimaKeyStoreProvider( 8129): TimaSignature is unavailable
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
D/ActivityThread( 8129): Added TimaKeyStore provider
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
D/SecurityLogAgent( 7693): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7693): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7693): StateMachine : Current State = 1
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,I/ActivityManager(  853): Killing 7067:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,D/SecurityLogAgent( 7693): StateMachine : Changed Current State = 1
,I/ActivityManager(  853): Killing 7083:com.samsung.helphub/1000 (adj 15): bgCount ##41
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/com.peel.receiver.ConnectivityActionReceiver( 5630): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 5630): 
D/com.peel.receiver.ConnectivityActionReceiver( 5630): 
D/com.peel.receiver.ConnectivityActionReceiver( 5630): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5630): 
D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5630): 
D/com.peel.receiver.ConnectivityActionReceiver( 5630): 
D/com.peel.receiver.ConnectivityActionReceiver( 5630):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5630): 
D/com.peel.receiver.ConnectivityActionReceiver( 5630): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5630): 
D/com.peel.receiver.ConnectivityActionReceiver( 5630): 
D/com.peel.receiver.ConnectivityActionReceiver( 5630): last run: 1452855545076 -- System.currentTimeMillis()-last_run: 4869815
D/com.peel.receiver.ConnectivityActionReceiver( 5630): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5630): ... skip last_72_check
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 8106): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,I/art     (  853): Explicit concurrent mark sweep GC freed 75008(4MB) AllocSpace objects, 14(354KB) LOS objects, 30% free, 36MB/52MB, paused 1.388ms total 105.328ms
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 8129): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,E/Zygote  ( 8145): MountEmulatedStorage()
E/Zygote  ( 8145): v2
,I/libpersona( 8145): KNOX_SDCARD checking this for 10178
I/libpersona( 8145): KNOX_SDCARD not a persona
,I/ActivityManager(  853): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8145 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup(  853): failed to open /acct/uid_10118/pid_7067/cgroup.procs: No such file or directory
,I/SELinux ( 8145): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_7083/cgroup.procs: No such file or directory
,I/SELinux ( 8145): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/BadgeProvider( 8129): onCreate
D/BadgeProvider( 8129): DatabaseHelper
E/SELinux ( 8145): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,W/ActivityManager(  853): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/BadgeProvider( 8129): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 1480): reloadBadges entered.
D/BadgeProvider( 8129): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8129): sendNotify, [notify] : null
D/BadgeProvider( 8129): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8129): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 8129): update, [UpdateCount] : 1
,D/TimaKeyStoreProvider( 8145): TimaSignature is unavailable
,D/ActivityThread( 8145): Added TimaKeyStore provider
,D/ResourcesManager( 8145): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/ActivityManager(  853): Killing 7120:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2437): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2437): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  853): failed to open /acct/uid_10166/pid_7120/cgroup.procs: No such file or directory
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  853): MasterInitialState.processMessage what=3
D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  853): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  853): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  853): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  853): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  853): getSBEnabled() enabled =false
D/SmartBondingService(  853): getSBEnabled() enabled =false
D/SmartBondingService(  853): getSBEnabled() enabled =false
I/CLocInfoService(  853): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  853): CLocinfo wifi true 
D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7159): notifyNetworkActivated
D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2111): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  853): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3789): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3789): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 2204): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
I/NetworkMonitor( 5359): type=WIFI subType= reason=null isConnected=true
,W/ContextImpl( 2204): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SystemBroadcastReceiver( 7199): [#DCM#] [DCM_Performance] onReceive completed in time  1175 microsec. 
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7199): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7199): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7199): [#DCM#] setIsConnectedForExtractors 
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DatabaseRebuilderTask( 7199): [#DCM#] postDBrebuildIntent rebuildLocation =  true
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FrameworkService( 7199): [#DCM#] onCreate FrameworkService 
,I/FrameworkService( 7199): [#DCM#] onCreate FrameworkService end 
I/DCMConfig( 7199): [#DCM#] getSuccessState = true
,I/FrameworkService( 7199): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
I/IntentHandler( 7199): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SecContentProvider2(  853): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  853): mCursor = null
,I/SystemUtils( 7199): [#DCM#] LM: false,AM:660774912
,I/DCMThreadPoolExecutor( 7199): [#DCM#] Task being added DatabaseRebuilderTask
,I/DCMThreadPoolExecutor( 7199): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@32794a93 is submitted
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,I/FrameworkService( 7199): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 23143 mirosec. 
,W/ContextImpl( 7159): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  853): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
I/DatabaseRebuilderTask( 7199): [#DCM#] createLuceneReader done 
I/DatabaseRebuilderTask( 7199): [#DCM#] resyncLocation   
I/DatabaseRebuilderTask( 7199): [#DCM#] resyncLocation: querying only for documents with deleted = 0 
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
D/SecContentProvider2(  853): mCursor = null
,D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
W/Kids    ( 2437): [AccountUtils] Account not ready
W/Kids    ( 2437): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2437): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2437): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2437): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2437): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2437): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2437): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2437): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2437): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2437): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2437): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2437): 	at java.lang.Thread.run(Thread.java:818)
,I/DatabaseRebuilderTask( 7199): [#DCM#] topDocs hits = 0
I/DatabaseRebuilderTask( 7199): [#DCM#] No of Location data to be added:  0
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/DatabaseRebuilderTask( 7199): [#DCM#] releaseLuceneReader done 
,I/DatabaseRebuilderTask( 7199): [#DCM#] Starting media manager do operation 
I/SystemUtils( 7199): [#DCM#] setHeavySharedPref set as  false
,I/IntentHandler( 7199): [#DCM#] Stopping service with ids up to  1
,I/DCMThreadPoolExecutor( 7199): [#DCM#] afterExecute FutureTask
,I/DCMController( 7199): [#DCM#] task finished =  com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@32794a93
,I/Hs20UtilService( 1301): Starting #8
,I/Hs20UtilService( 1301): Message received 5007
D/hcjo    ( 7159): AutoUpdateManager:IDLE:execute
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/InitializeManagerStateMachine( 7159): execute::IDLE:EXECUTE
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,D/InitializeManagerStateMachine( 7159): exit::IDLE
D/InitializeManagerStateMachine( 7159): entry::NETWORK_CHECK
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7159): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7159): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7159): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7159): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7159): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7159): entry::SUCCESS
D/hcjo    ( 7159): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7159): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7159): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7159): exit::SUCCESS
D/InitializeManagerStateMachine( 7159): entry::IDLE
,I/Hs20UtilService( 1301): Starting #9
,I/Hs20UtilService( 1301): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1301): Starting #10
,I/Hs20UtilService( 1301): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  853): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1301): Starting #11
,I/Hs20UtilService( 1301): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  853): callSECApi what=220
,D/WifiStateMachine(  853): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 7760): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7760): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7760): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7760): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/DIAGMON_AGENT( 7799): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7799): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService(  853): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=853
,D/DisplayPowerController(  853): getFinalBrightness : 39 -> 39
,D/PowerManagerService(  853): [s] DisplayPowerCallbacks : onStateChanged()
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/lights  (  853): lcd : 23 +
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/lights  (  853): lcd : 23 -
,D/lights  (  853): lcd : 31 +
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/lights  (  853): lcd : 31 -
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/DisplayPowerController(  853): getFinalBrightness : 39 -> 39
D/lights  (  853): lcd : 39 +
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,I/FOTA_Client( 7824): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7824): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,D/lights  (  853): lcd : 39 -
,D/DisplayPowerController(  853): getFinalBrightness : 39 -> 39
,I/FOTA_Client( 7824): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7824): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/FOTA_Client( 7824): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7839): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7839): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452860415490
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore in!
,I/KLMS-2.4.503: ( 7839): MainReciver(): NETWORK_STATE_CHANGED_ACTION
I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  853): CMD_RSSI_POLL : out!
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7839): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7839): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7839): NetworkChangeOperations(): uploadRequestLog().START 
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7839): StateImplV2(): networkChangeListener().END
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/SO_AGENT( 7855): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7900): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/SA      ( 7916): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7916): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7916): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7916): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7916): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7916): [SCU] == networkStateCheck == true
,I/SA      ( 7916): [DM] getCountryCodeFromCSC : DE
I/SA      ( 7916): isChinaCountryCode : false
,I/SA      ( 7916): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7916): [OR] == networkStateCheck true ==
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/SA      ( 7916): [OR] GetMyCountryZoneTask
,I/SA      ( 7916): [OR] onReceive END
,I/SA      ( 7916): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/accuweather( 7408): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  853): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/accuweather( 7408): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro( 7937): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7937): premStatus:2
,I/SA      ( 7916): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/KnoxUsageLogPro( 7937): isEulaShown : false
D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/KnoxUsageLogPro( 7937): KnoxUsageReceiver onReceive : not Processible, just return
,I/SA      ( 7916): [SSP] query invoked
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/GCM     ( 1677): Connected
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7916): [TPMU] GetMccFromDB : null
,I/SA      ( 7916): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7916): [TPM] isNoProxy(default) : true
,D/Headlines( 5502): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 5502): getCountryCode(): countryCode = DE
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1677): Message class com.google.f.a.a.p
D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Headlines( 5502): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5502): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5502): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5502): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5502): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5502): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5502): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 8074): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8074): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 8074): PeriphStartReceiver.onReceive - no need to start
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  853): exchangeData() failure , invalid userId
,D/RCPManagerService(  853): exchangeData() failure , invalid userId
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7693): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7693): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7693): StateMachine : Current State = 1
D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7693): StateMachine : Changed Current State = 1
,E/File    ( 7916): fail readDirectory() errno=2
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/com.peel.receiver.ConnectivityActionReceiver( 5630): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 5630): 
D/com.peel.receiver.ConnectivityActionReceiver( 5630): 
D/com.peel.receiver.ConnectivityActionReceiver( 5630): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5630): 
D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5630): 
D/com.peel.receiver.ConnectivityActionReceiver( 5630): 
D/com.peel.receiver.ConnectivityActionReceiver( 5630):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5630): 
D/com.peel.receiver.ConnectivityActionReceiver( 5630): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5630): 
D/com.peel.receiver.ConnectivityActionReceiver( 5630): 
D/com.peel.receiver.ConnectivityActionReceiver( 5630): last run: 1452855545076 -- System.currentTimeMillis()-last_run: 4870628
D/com.peel.receiver.ConnectivityActionReceiver( 5630): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5630): ... skip last_72_check
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ChimeraCfgMgr( 2437): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2437): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/hcjo    ( 7159): AutoUpdateManager:IDLE:execute
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7159): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7159): exit::IDLE
D/InitializeManagerStateMachine( 7159): entry::NETWORK_CHECK
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7159): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7159): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7159): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 7159): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7159): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7159): entry::SUCCESS
D/hcjo    ( 7159): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7159): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7159): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7159): exit::SUCCESS
D/InitializeManagerStateMachine( 7159): entry::IDLE
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
D/SecContentProvider2(  853): mCursor = null
,D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
W/Kids    ( 2437): [AccountUtils] Account not ready
W/Kids    ( 2437): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2437): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2437): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2437): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2437): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2437): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2437): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2437): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2437): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2437): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2437): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2437): 	at java.lang.Thread.run(Thread.java:818)
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,E/WifiStateMachine(  853): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  853): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  853): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  853): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/SmartBondingService(  853): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  853): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  853): getSBEnabled() enabled =false
D/SmartBondingService(  853): getSBEnabled() enabled =false
D/SmartBondingService(  853): getSBEnabled() enabled =false
,D/ConnectivityService(  853): identical MTU - not setting
D/ConnectivityService(  853): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  853): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
,V/        (  277): QcRouteController
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,V/        (  277): QcRouteController
,W/NetworkManagementService(  853): route cmd failed: 
W/NetworkManagementService(  853): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  853): '
W/NetworkManagementService(  853): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  853): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  853): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  853): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  853): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  853): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  853): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  853): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  853): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  853): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  853): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  853): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  853): calling update connectivity
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  853): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524295
D/ConnectivityService(  853): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  853): calling update connectivity
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  853): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524295
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/SA      ( 7916): [RC New] Execute method=[GET] start
,I/SA      ( 7916): [RC New] Security=[true]
,I/System.out( 7916): Thread-1295(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7916): Thread-1295(ApacheHTTPLog):isShipBuild true
,I/System.out( 7916): Thread-1295(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  853): Plugged
I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/dhcpcd  ( 7861): wlan0: sending IPv6 Router Solicitation
,I/SA      ( 7916): [RC New] [v2liruge] api execute + 830
,I/SA      ( 7916): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 7916): AsyncTask #1 calls detatch()
,I/SA      ( 7916): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 7916): [OCP] update openData : PL
,I/SA      ( 7916): [TPMU] getNetworkMcc : 
,I/SA      ( 7916): [SCU] saveMccToPreferece Start
,I/SA      ( 7916): [SCU] RegionMCC : 260
I/SA      ( 7916): [SSP] query invoked
,I/SA      ( 7916): [TPMU] GetMccFromDB : null
,I/SA      ( 7916): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7916): [SCU] saveMccToPreferece End
,I/SA      ( 7916): [RC New] executeRequest [v2liruge] end. 908
,I/SA      ( 7916): [RC New] Execute end
I/SA      ( 7916): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7916): [OR] GetMyCountryZoneTask Success
,D/PackageManager(  853): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager(  853): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,I/Atfwd_Sendcmd(  320): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  320): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,E/Zygote  ( 8200): MountEmulatedStorage()
,D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
I/ActivityManager(  853): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8200 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,E/Zygote  ( 8200): v2
I/libpersona( 8200): KNOX_SDCARD checking this for 10034
I/libpersona( 8200): KNOX_SDCARD not a persona
I/InputReader(  853): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  853): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  853): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  853): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/SELinux ( 8200): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8200): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8200): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  853): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 1480): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 1480): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager(  853): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/RegisteredServicesCache( 1468): empty dynamic service
,D/ResourcesManager(  853): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 1480): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1480): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 8200): TimaSignature is unavailable
,D/ResourcesManager( 1480): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
D/ActivityThread( 8200): Added TimaKeyStore provider
,W/ResourcesManager( 1480): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1480): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  853): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 8200): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  853): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/SecContentProvider2(  853): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  853): mCursor = null
,D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  853): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,I/FeatureConfig( 8200): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  853): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  853): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  853): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  853): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  853): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  853): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  853): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager(  853): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  853): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  853): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  853): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/BackupManagerService(  853): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,W/ResourcesManager(  853): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  853): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  853): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  853): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  853): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  853): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,V/AlarmManager(  853): waitForAlarm result :8
,D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 8200): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8200): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8200): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8200): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8200): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8200): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8200): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ResourcesManager( 8200): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 8200): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 8200): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8200): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8200): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8200): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8200): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 8200): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,I/WifiStateMachine(  853): REQUEST_POWER_SAVE_ON
,W/ResourcesManager( 8200): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 8200): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 8200): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8200): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8200): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8200): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8200): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 8200): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 8200): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8200): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8200): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8200): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8200): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8200): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8200): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8200): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 8200): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/WifiStateMachine(  853): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
W/ResourcesManager( 8200): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 8200): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8200): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 8200): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8200): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/ResourcesManager( 8200): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8200): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8200): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8200): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8200): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8200): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 8200): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 8200): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8200): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 1677): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
W/ResourcesManager( 8200): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_google_search.png
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/ResourcesManager( 8200): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/SecContentProvider2(  853): uri = 14 selection = getSealedState
D/SecContentProvider2(  853): mCursor = null
,D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,W/ResourcesManager( 8200): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8200): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8200): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8200): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,W/Search.LoginHelper( 1566): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,D/ResourcesManager( 8200): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 8200): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8200): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 8200): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 8200): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 8200): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8200): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8200): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8200): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8200): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8200): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8200): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 8200): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 8200): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8233): MountEmulatedStorage()
E/Zygote  ( 8233): v2
I/libpersona( 8233): KNOX_SDCARD checking this for 10035
I/libpersona( 8233): KNOX_SDCARD not a persona
,I/ActivityManager(  853): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=8233 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 6673:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,I/SELinux ( 8233): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8233): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8233): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  853): failed to open /acct/uid_10012/pid_6673/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8233): TimaSignature is unavailable
,D/ActivityThread( 8233): Added TimaKeyStore provider
,D/ResourcesManager( 8233): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): checkState() : APP TYPE = Full
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8254): MountEmulatedStorage()
,I/libpersona( 8254): KNOX_SDCARD checking this for 10017
E/Zygote  ( 8254): v2
I/libpersona( 8254): KNOX_SDCARD not a persona
,I/ActivityManager(  853): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=8254 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,I/SELinux ( 8254): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/PowerManagerService(  853): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  853): [PWL] On : 78667 (30000 ms ago)
I/PowerManagerService(  853): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
,I/PowerManagerService(  853): [PWL]  SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=853, ws=WorkSource{10059}) (elapsedTime=2936)
,I/SELinux ( 8254): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8254): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8254): TimaSignature is unavailable
,D/ActivityThread( 8254): Added TimaKeyStore provider
,D/ResourcesManager( 8254): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  853): CMD_RSSI_POLL : out!
,D/BluetoothManager( 8233): getConnectedDevices
,D/-----SIC-----( 8233): ------------------skip uv
,D/-----SIC-----( 8233): ------------------skip SPO2
D/-----SIC-----( 8233): ------------------skip TGH
,I/SecureStorage( 8254): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  330): [INFO]: SPID(0x00000005)Credentials: uid 10017, gid 10017, pid 8254
I/SecureStorage(  330): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8233): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8233): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,V/MediaPlayer( 8233): decode(33, 19359868, 4230)
,V/MediaPlayerService(  289): decode(32, 19359868, 4230)
,V/MediaPlayerService(  289): player type = 3
,V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): constructor
,V/AwesomePlayer(  289): setDefault
,V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
,V/StagefrightPlayer(  289): StagefrightPlayer
V/AwesomePlayer(  289): setListener
,V/StagefrightPlayer(  289): initCheck
,V/AwesomePlayer(  289): setAudioSink
V/StagefrightPlayer(  289): setDataSource(32, 19359868, 4230)
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  289): notify(0xafb090b0, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
,V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
D/Utils   (  289): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  289): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  289): mBitrate = -1 bits/sec
I/OggExtractor(  289): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  289): current audio track index (0) is added to vector
,V/AwesomePlayer(  289): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  289): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  289): prepare
V/AwesomePlayer(  289): prepareAsync
,V/MediaPlayerService(  289): wait for prepare
,V/AwesomePlayer(  289): onPrepareAsyncEvent
I/SecMediaClock(  289): SecMediaClock constructor
I/SecMediaClock(  289): reset
I/SecVideoCapture(  289): SecVideoCapture constructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): initAudioDecoder
V/AwesomePlayer(  289): checkOffloadExceptions is true
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  289): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  289): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthServiceInstalled() : HealthService is Installed.
V/AwesomePlayer(  289): finishAsyncPrepare_l
V/AwesomePlayer(  289): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  289): notify(0xafb090b0, 200, 973, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb090b0, 5, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb090b0, 1, 0, 0)
V/AudioCache(  289): prepared
V/AudioCache(  289): wait - success
V/MediaPlayerService(  289): start
V/StagefrightPlayer(  289): start
V/AwesomePlayer(  289): play
V/AwesomePlayer(  289): AwesomePlayer::play_l():: This is not a DRM content
D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
V/AwesomePlayer(  289): startAudioPlayer_l, sendErrorNotification (0)
D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
D/AudioPlayer(  289): start of Playback, useOffload 0
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  289): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  289): Audio channels(1)
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  289): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  289): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb090b0, 6, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): addBatteryData
,I/AudioPlayer(  289): First fillBuffer call!!
V/MediaPlayerService(  289): wait for playback complete
I/AudioPlayer(  289): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  289): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
,V/AwesomePlayer(  289): postAudioEOS delayUs (0)
V/AwesomePlayer(  289): onCheckAudioStatus
V/AwesomePlayer(  289): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  289): onStreamDone
V/AwesomePlayer(  289): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  289): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb090b0, 2, 0, 0)
V/AudioCache(  289): playback complete - thread will wake up later
V/AwesomePlayer(  289): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb090b0, 7, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  289): addBatteryData
V/AudioCache(  289): wait - success
V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb090b0, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
D/AudioPlayer(  289): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop() sendCommand(0x74, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  289): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  289): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  289): ~OggSource --
I/OggExtractor(  289): ~OggExtractor ++
I/OggExtractor(  289): ~MyVorbisExtractor ++ 
I/OggExtractor(  289): ~MyVorbisExtractor --
I/OggExtractor(  289): ~OggExtractor --
,I/AudioPlayer(  289): reset out
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  289): SecVideoCapture destructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): mSecCapture clear
I/SecMediaClock(  289): SecMediaClock destructor
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): ~StagefrightPlayer
V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/AwesomePlayer(  289): destructor
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
,V/MediaPlayer( 8233): decode(37, 19213040, 15440)
,V/MediaPlayerService(  289): decode(32, 19213040, 15440)
,V/MediaPlayerService(  289): player type = 3
V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): constructor
,V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): StagefrightPlayer
V/AwesomePlayer(  289): setListener
V/StagefrightPlayer(  289): initCheck
V/AwesomePlayer(  289): setAudioSink
V/StagefrightPlayer(  289): setDataSource(32, 19213040, 15440)
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d560, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
D/Utils   (  289): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  289): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  289): mBitrate = -1 bits/sec
I/OggExtractor(  289): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  289): current audio track index (0) is added to vector
V/AwesomePlayer(  289): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  289): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  289): prepare
V/AwesomePlayer(  289): prepareAsync
V/MediaPlayerService(  289): wait for prepare
V/AwesomePlayer(  289): onPrepareAsyncEvent
I/SecMediaClock(  289): SecMediaClock constructor
I/SecMediaClock(  289): reset
I/SecVideoCapture(  289): SecVideoCapture constructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): initAudioDecoder
V/AwesomePlayer(  289): checkOffloadExceptions is true
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  289): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  289): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  289): finishAsyncPrepare_l
V/AwesomePlayer(  289): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  289): notify(0xb061d560, 200, 973, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d560, 5, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d560, 1, 0, 0)
V/AudioCache(  289): prepared
V/AudioCache(  289): wait - success
V/MediaPlayerService(  289): start
V/StagefrightPlayer(  289): start
V/AwesomePlayer(  289): play
V/AwesomePlayer(  289): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  289): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  289): start of Playback, useOffload 0
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  289): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/AdaptiveEventManager( 1171): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1171): M updateContainers()
D/AdaptiveEventContainerSmall( 1171): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1171): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1171): pedoEvent == null
,I/AudioPlayer(  289): Audio channels(2)
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  289): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  289): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d560, 6, 0, 0)
V/AudioCache(  289): ignored
I/AudioPlayer(  289): First fillBuffer call!!
I/AudioPlayer(  289): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  289): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
V/AwesomePlayer(  289): addBatteryData
,V/MediaPlayerService(  289): wait for playback complete
,D/AdaptiveEventManager( 1171): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1171): M updateContainers()
D/AdaptiveEventContainerSmall( 1171): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1171): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1171): pedoEvent == null
,I/ActivityManager(  853): Killing 7135:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): bgCount ##41
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] End Of Stream
,I/UpdateIcingCorporaServi( 1566): Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
,V/AwesomePlayer(  289): postAudioEOS delayUs (0)
V/AwesomePlayer(  289): onCheckAudioStatus
V/AwesomePlayer(  289): onCheckAudioStatus() set AUDIO_AT_EOS flag
,V/AwesomePlayer(  289): onStreamDone
V/AwesomePlayer(  289): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  289): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d560, 2, 0, 0)
V/AudioCache(  289): playback complete - thread will wake up later
V/AwesomePlayer(  289): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d560, 7, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  289): addBatteryData
V/AudioCache(  289): wait - success
V/StagefrightPlayer(  289): reset
,V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d560, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
D/AudioPlayer(  289): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop() sendCommand(0x75, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  289): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  289): OggSource::~OggSource() mExtractor !mStarted ref count = 1
,I/OggExtractor(  289): ~OggSource --
I/OggExtractor(  289): ~OggExtractor ++
,I/OggExtractor(  289): ~MyVorbisExtractor ++ 
I/OggExtractor(  289): ~MyVorbisExtractor --
,I/OggExtractor(  289): ~OggExtractor --
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,I/AudioPlayer(  289): reset out
,V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  289): SecVideoCapture destructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): mSecCapture clear
,I/SecMediaClock(  289): SecMediaClock destructor
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): ~StagefrightPlayer
V/StagefrightPlayer(  289): reset
,V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
,V/AwesomePlayer(  289): destructor
,V/AwesomePlayer(  289): reset_l()
,V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
,V/MediaPlayer( 8233): decode(38, 19257568, 9226)
,V/MediaPlayerService(  289): decode(32, 19257568, 9226)
,V/MediaPlayerService(  289): player type = 3
V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): constructor
,V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): StagefrightPlayer
V/AwesomePlayer(  289): setListener
V/StagefrightPlayer(  289): initCheck
V/AwesomePlayer(  289): setAudioSink
V/StagefrightPlayer(  289): setDataSource(32, 19257568, 9226)
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb09100, 8, 0, 0)
V/AudioCache(  289): ignored
,V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
D/Utils   (  289): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  289): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  289): mBitrate = -1 bits/sec
I/OggExtractor(  289): OggSource::OggSource() mExtractor ref count = 4
I/libpersona( 8311): KNOX_SDCARD checking this for 10075
V/AwesomePlayer(  289): current audio track index (0) is added to vector
I/libpersona( 8311): KNOX_SDCARD not a persona
V/AwesomePlayer(  289): setDataSource_l: Audio(1), Video(0)
E/Zygote  ( 8311): MountEmulatedStorage()
I/AwesomePlayer(  289): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
E/Zygote  ( 8311): v2
V/MediaPlayerService(  289): prepare
V/AwesomePlayer(  289): prepareAsync
V/MediaPlayerService(  289): wait for prepare
,V/AwesomePlayer(  289): onPrepareAsyncEvent
I/SecMediaClock(  289): SecMediaClock constructor
I/SecMediaClock(  289): reset
I/SecVideoCapture(  289): SecVideoCapture constructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): initAudioDecoder
V/AwesomePlayer(  289): checkOffloadExceptions is true
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  289): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  289): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/ActivityManager(  853): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=8311 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8311): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8311): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  289): finishAsyncPrepare_l
,E/SELinux ( 8311): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/AwesomePlayer(  289): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  289): notify(0xafb09100, 200, 973, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb09100, 5, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb09100, 1, 0, 0)
V/AudioCache(  289): prepared
V/AudioCache(  289): wait - success
V/MediaPlayerService(  289): start
V/StagefrightPlayer(  289): start
V/AwesomePlayer(  289): play
V/AwesomePlayer(  289): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  289): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  289): start of Playback, useOffload 0
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  289): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  289): Audio channels(2)
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  289): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  289): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb09100, 6, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): addBatteryData
,V/MediaPlayerService(  289): wait for playback complete
,I/AudioPlayer(  289): First fillBuffer call!!
,I/AudioPlayer(  289): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  289): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
,E/DatabaseUtils(  853): Writing exception to parcel
E/DatabaseUtils(  853): java.lang.NullPointerException: key == null
E/DatabaseUtils(  853): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils(  853): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils(  853): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils(  853): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/DatabaseUtils(  853): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils(  853): 	at android.os.Binder.execTransact(Binder.java:446)
,I/ActivityManager(  853): Killing 7179:com.sec.android.app.videoplayer/u0a54 (adj 15): bgCount ##41
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  289): postAudioEOS delayUs (0)
V/AwesomePlayer(  289): onCheckAudioStatus
V/AwesomePlayer(  289): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  289): onStreamDone
V/AwesomePlayer(  289): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  289): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb09100, 2, 0, 0)
V/AudioCache(  289): playback complete - thread will wake up later
V/AwesomePlayer(  289): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb09100, 7, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  289): addBatteryData
V/AudioCache(  289): wait - success
V/StagefrightPlayer(  289): reset
,V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb09100, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
D/AudioPlayer(  289): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop() sendCommand(0x76, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  289): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  289): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  289): ~OggSource --
I/OggExtractor(  289): ~OggExtractor ++
I/OggExtractor(  289): ~MyVorbisExtractor ++ 
I/OggExtractor(  289): ~MyVorbisExtractor --
I/OggExtractor(  289): ~OggExtractor --
,I/AudioPlayer(  289): reset out
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  289): SecVideoCapture destructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): mSecCapture clear
I/SecMediaClock(  289): SecMediaClock destructor
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): ~StagefrightPlayer
V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/AwesomePlayer(  289): destructor
,V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/MediaPlayer( 8233): decode(39, 19364180, 4890)
,V/MediaPlayerService(  289): decode(32, 19364180, 4890)
,V/MediaPlayerService(  289): player type = 3
,V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): constructor
V/AwesomePlayer(  289): setDefault
,V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): StagefrightPlayer
V/AwesomePlayer(  289): setListener
,V/StagefrightPlayer(  289): initCheck
V/AwesomePlayer(  289): setAudioSink
V/StagefrightPlayer(  289): setDataSource(32, 19364180, 4890)
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 8, 0, 0)
V/AudioCache(  289): ignored
,V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
,D/Utils   (  289): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  289): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  289): mBitrate = -1 bits/sec
I/OggExtractor(  289): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  289): current audio track index (0) is added to vector
V/AwesomePlayer(  289): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  289): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService(  289): prepare
V/AwesomePlayer(  289): prepareAsync
V/MediaPlayerService(  289): wait for prepare
,V/AwesomePlayer(  289): onPrepareAsyncEvent
I/SecMediaClock(  289): SecMediaClock constructor
I/SecMediaClock(  289): reset
I/SecVideoCapture(  289): SecVideoCapture constructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): initAudioDecoder
V/AwesomePlayer(  289): checkOffloadExceptions is true
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  289): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  289): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  289): finishAsyncPrepare_l
V/AwesomePlayer(  289): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 200, 973, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 5, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 1, 0, 0)
V/AudioCache(  289): prepared
V/AudioCache(  289): wait - success
V/MediaPlayerService(  289): start
V/StagefrightPlayer(  289): start
V/AwesomePlayer(  289): play
V/AwesomePlayer(  289): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  289): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  289): start of Playback, useOffload 0
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  289): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  289): Audio channels(1)
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  289): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  289): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 6, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): addBatteryData
I/AudioPlayer(  289): First fillBuffer call!!
,I/AudioPlayer(  289): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  289): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/MediaPlayerService(  289): wait for playback complete
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  289): postAudioEOS delayUs (0)
V/AwesomePlayer(  289): onCheckAudioStatus
V/AwesomePlayer(  289): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  289): onStreamDone
V/AwesomePlayer(  289): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  289): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 2, 0, 0)
V/AudioCache(  289): playback complete - thread will wake up later
V/AwesomePlayer(  289): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 7, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  289): addBatteryData
,V/AudioCache(  289): wait - success
V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
D/AudioPlayer(  289): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop() sendCommand(0x77, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  289): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  289): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  289): ~OggSource --
I/OggExtractor(  289): ~OggExtractor ++
I/OggExtractor(  289): ~MyVorbisExtractor ++ 
I/OggExtractor(  289): ~MyVorbisExtractor --
I/OggExtractor(  289): ~OggExtractor --
,I/AudioPlayer(  289): reset out
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  289): SecVideoCapture destructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): mSecCapture clear
I/SecMediaClock(  289): SecMediaClock destructor
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): ~StagefrightPlayer
V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/AwesomePlayer(  289): destructor
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/MediaPlayer( 8233): decode(40, 19290344, 17329)
V/MediaPlayerService(  289): decode(32, 19290344, 17329)
,V/MediaPlayerService(  289): player type = 3
V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): constructor
,V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): StagefrightPlayer
V/AwesomePlayer(  289): setListener
V/StagefrightPlayer(  289): initCheck
V/AwesomePlayer(  289): setAudioSink
V/StagefrightPlayer(  289): setDataSource(32, 19290344, 17329)
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb091f0, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
D/Utils   (  289): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  289): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  289): mBitrate = -1 bits/sec
I/OggExtractor(  289): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  289): current audio track index (0) is added to vector
V/AwesomePlayer(  289): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  289): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  289): prepare
V/AwesomePlayer(  289): prepareAsync
V/MediaPlayerService(  289): wait for prepare
V/AwesomePlayer(  289): onPrepareAsyncEvent
I/SecMediaClock(  289): SecMediaClock constructor
I/SecMediaClock(  289): reset
I/SecVideoCapture(  289): SecVideoCapture constructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): initAudioDecoder
V/AwesomePlayer(  289): checkOffloadExceptions is true
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/TimaKeyStoreProvider( 8311): TimaSignature is unavailable
,I/OMXCodec(  289): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  289): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
D/ActivityThread( 8311): Added TimaKeyStore provider
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  289): finishAsyncPrepare_l
V/AwesomePlayer(  289): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  289): notify(0xafb091f0, 200, 973, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb091f0, 5, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb091f0, 1, 0, 0)
V/AudioCache(  289): prepared
,V/AudioCache(  289): wait - success
V/MediaPlayerService(  289): start
V/StagefrightPlayer(  289): start
V/AwesomePlayer(  289): play
V/AwesomePlayer(  289): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  289): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  289): start of Playback, useOffload 0
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  289): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  289): Audio channels(2)
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  289): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  289): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb091f0, 6, 0, 0)
I/AudioPlayer(  289): First fillBuffer call!!
I/AudioPlayer(  289): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  289): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): addBatteryData
,V/MediaPlayerService(  289): wait for playback complete
W/libprocessgroup(  853): failed to open /acct/uid_10170/pid_7135/cgroup.procs: No such file or directory
,D/ResourcesManager( 8311): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,I/UpdateIcingCorporaServi( 1566): UpdateCorporaTask done [took 144 ms] updated apps [took 144 ms] 
,D/FileShare-Server( 8311): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  289): postAudioEOS delayUs (0)
V/AwesomePlayer(  289): onCheckAudioStatus
V/AwesomePlayer(  289): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  289): onStreamDone
V/AwesomePlayer(  289): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  289): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb091f0, 2, 0, 0)
V/AudioCache(  289): playback complete - thread will wake up later
V/AwesomePlayer(  289): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb091f0, 7, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  289): addBatteryData
V/AudioCache(  289): wait - success
V/StagefrightPlayer(  289): reset
,V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb091f0, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
D/AudioPlayer(  289): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop() sendCommand(0x78, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  289): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  289): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  289): ~OggSource --
I/OggExtractor(  289): ~OggExtractor ++
I/OggExtractor(  289): ~MyVorbisExtractor ++ 
I/OggExtractor(  289): ~MyVorbisExtractor --
I/OggExtractor(  289): ~OggExtractor --
,I/AudioPlayer(  289): reset out
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  289): SecVideoCapture destructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): mSecCapture clear
I/SecMediaClock(  289): SecMediaClock destructor
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): ~StagefrightPlayer
V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/AwesomePlayer(  289): destructor
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/MediaPlayer( 8233): decode(41, 19190536, 6644)
,V/MediaPlayerService(  289): decode(32, 19190536, 6644)
V/MediaPlayerService(  289): player type = 3
V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): constructor
,V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): StagefrightPlayer
V/AwesomePlayer(  289): setListener
V/StagefrightPlayer(  289): initCheck
V/AwesomePlayer(  289): setAudioSink
V/StagefrightPlayer(  289): setDataSource(32, 19190536, 6644)
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
D/Utils   (  289): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  289): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  289): mBitrate = -1 bits/sec
I/OggExtractor(  289): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  289): current audio track index (0) is added to vector
V/AwesomePlayer(  289): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  289): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  289): prepare
V/AwesomePlayer(  289): prepareAsync
V/MediaPlayerService(  289): wait for prepare
V/AwesomePlayer(  289): onPrepareAsyncEvent
I/SecMediaClock(  289): SecMediaClock constructor
I/SecMediaClock(  289): reset
I/SecVideoCapture(  289): SecVideoCapture constructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): initAudioDecoder
V/AwesomePlayer(  289): checkOffloadExceptions is true
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  289): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  289): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  289): finishAsyncPrepare_l
V/AwesomePlayer(  289): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 200, 973, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 5, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 1, 0, 0)
V/AudioCache(  289): prepared
V/AudioCache(  289): wait - success
V/MediaPlayerService(  289): start
V/StagefrightPlayer(  289): start
V/AwesomePlayer(  289): play
V/AwesomePlayer(  289): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  289): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  289): start of Playback, useOffload 0
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  289): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
I/AudioPlayer(  289): Audio channels(1)
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat:0, 1, 0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
V/AudioCache(  289): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  289): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 6, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): addBatteryData
V/MediaPlayerService(  289): wait for playback complete
,I/AudioPlayer(  289): First fillBuffer call!!
,I/AudioPlayer(  289): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  289): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,W/libprocessgroup(  853): failed to open /acct/uid_10054/pid_7179/cgroup.procs: No such file or directory
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] End Of Stream
I/libpersona( 8342): KNOX_SDCARD checking this for 1000
E/Zygote  ( 8342): MountEmulatedStorage()
I/libpersona( 8342): KNOX_SDCARD not a persona
E/Zygote  ( 8342): v2
V/AwesomePlayer(  289): postAudioEOS delayUs (0)
,I/ActivityManager(  853): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=8342 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,V/AwesomePlayer(  289): onCheckAudioStatus
V/AwesomePlayer(  289): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  289): onStreamDone
V/AwesomePlayer(  289): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  289): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 2, 0, 0)
V/AudioCache(  289): playback complete - thread will wake up later
V/AwesomePlayer(  289): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 7, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  289): addBatteryData
V/AudioCache(  289): wait - success
V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
D/AudioPlayer(  289): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop() sendCommand(0x79, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  289): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  289): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  289): ~OggSource --
I/OggExtractor(  289): ~OggExtractor ++
I/OggExtractor(  289): ~MyVorbisExtractor ++ 
I/OggExtractor(  289): ~MyVorbisExtractor --
I/OggExtractor(  289): ~OggExtractor --
,I/AudioPlayer(  289): reset out
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  289): SecVideoCapture destructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): mSecCapture clear
I/SecMediaClock(  289): SecMediaClock destructor
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): ~StagefrightPlayer
V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/AwesomePlayer(  289): destructor
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/MediaPlayer( 8233): decode(42, 19266876, 23389)
,I/ActivityManager(  853): Killing 6245:com.google.android.gm/u0a114 (adj 15): bgCount ##41
,I/SELinux ( 8342): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
V/MediaPlayerService(  289): decode(32, 19266876, 23389)
,V/MediaPlayerService(  289): player type = 3
V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): constructor
V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): StagefrightPlayer
V/AwesomePlayer(  289): setListener
V/StagefrightPlayer(  289): initCheck
V/AwesomePlayer(  289): setAudioSink
V/StagefrightPlayer(  289): setDataSource(32, 19266876, 23389)
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d560, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
D/Utils   (  289): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
I/SELinux ( 8342): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8342): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/AwesomePlayer(  289): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  289): mBitrate = -1 bits/sec
I/OggExtractor(  289): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  289): current audio track index (0) is added to vector
V/AwesomePlayer(  289): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  289): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  289): prepare
V/AwesomePlayer(  289): prepareAsync
V/MediaPlayerService(  289): wait for prepare
V/AwesomePlayer(  289): onPrepareAsyncEvent
I/SecMediaClock(  289): SecMediaClock constructor
I/SecMediaClock(  289): reset
I/SecVideoCapture(  289): SecVideoCapture constructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): initAudioDecoder
V/AwesomePlayer(  289): checkOffloadExceptions is true
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  289): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  289): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  289): finishAsyncPrepare_l
V/AwesomePlayer(  289): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  289): notify(0xb061d560, 200, 973, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d560, 5, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d560, 1, 0, 0)
V/AudioCache(  289): prepared
V/AudioCache(  289): wait - success
V/MediaPlayerService(  289): start
V/StagefrightPlayer(  289): start
,V/AwesomePlayer(  289): play
V/AwesomePlayer(  289): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  289): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  289): start of Playback, useOffload 0
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/AudioPlayer(  289): Audio channels(2)
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  289): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  289): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  289): notify(0xb061d560, 6, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): addBatteryData
D/PowerManagerService(  853): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 853) eventTime = 109236
V/MediaPlayerService(  289): wait for playback complete
,I/AudioPlayer(  289): First fillBuffer call!!
I/AudioPlayer(  289): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  289): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,D/PowerManagerService(  853): [s] UserActivityState : 4 -> 1
,D/PowerManagerService(  853): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=853 (0x0)
D/PowerManagerService(  853): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=853, ws=WorkSource{10059}) (elapsedTime=3508)
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,W/libprocessgroup(  853): failed to open /acct/uid_10114/pid_6245/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8342): TimaSignature is unavailable
,D/ActivityThread( 8342): Added TimaKeyStore provider
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] End Of Stream
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,V/AwesomePlayer(  289): postAudioEOS delayUs (0)
,V/AwesomePlayer(  289): onCheckAudioStatus
V/AwesomePlayer(  289): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  289): onStreamDone
V/AwesomePlayer(  289): MEDIA_PLAYBACK_COMPLETE
,V/AwesomePlayer(  289): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d560, 2, 0, 0)
V/AudioCache(  289): playback complete - thread will wake up later
V/AwesomePlayer(  289): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d560, 7, 0, 0)
V/AudioCache(  289): ignored
,V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  289): addBatteryData
V/AudioCache(  289): wait - success
V/StagefrightPlayer(  289): reset
,V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d560, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
D/AudioPlayer(  289): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop() sendCommand(0x7a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  289): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  289): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  289): ~OggSource --
I/OggExtractor(  289): ~OggExtractor ++
I/OggExtractor(  289): ~MyVorbisExtractor ++ 
I/OggExtractor(  289): ~MyVorbisExtractor --
I/OggExtractor(  289): ~OggExtractor --
,I/AudioPlayer(  289): reset out
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  289): SecVideoCapture destructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): mSecCapture clear
I/SecMediaClock(  289): SecMediaClock destructor
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): ~StagefrightPlayer
V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/AwesomePlayer(  289): destructor
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/MediaPlayer( 8233): decode(35, 19156232, 8154)
V/MediaPlayerService(  289): decode(32, 19156232, 8154)
,V/MediaPlayerService(  289): player type = 3
V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): constructor
,V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): StagefrightPlayer
V/AwesomePlayer(  289): setListener
V/StagefrightPlayer(  289): initCheck
V/AwesomePlayer(  289): setAudioSink
V/StagefrightPlayer(  289): setDataSource(32, 19156232, 8154)
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb09100, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
D/Utils   (  289): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  289): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  289): mBitrate = -1 bits/sec
I/OggExtractor(  289): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  289): current audio track index (0) is added to vector
V/AwesomePlayer(  289): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  289): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  289): prepare
V/AwesomePlayer(  289): prepareAsync
V/MediaPlayerService(  289): wait for prepare
V/AwesomePlayer(  289): onPrepareAsyncEvent
I/SecMediaClock(  289): SecMediaClock constructor
I/SecMediaClock(  289): reset
I/SecVideoCapture(  289): SecVideoCapture constructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): initAudioDecoder
V/AwesomePlayer(  289): checkOffloadExceptions is true
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  289): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  289): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  289): finishAsyncPrepare_l
V/AwesomePlayer(  289): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  289): notify(0xafb09100, 200, 973, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb09100, 5, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb09100, 1, 0, 0)
V/AudioCache(  289): prepared
V/AudioCache(  289): wait - success
V/MediaPlayerService(  289): start
V/StagefrightPlayer(  289): start
V/AwesomePlayer(  289): play
V/AwesomePlayer(  289): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  289): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  289): start of Playback, useOffload 0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ResourcesManager( 8342): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  289): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  289): Audio channels(1)
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  289): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  289): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb09100, 6, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): addBatteryData
V/MediaPlayerService(  289): wait for playback complete
I/AudioPlayer(  289): First fillBuffer call!!
,I/AudioPlayer(  289): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  289): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  289): postAudioEOS delayUs (0)
,V/AwesomePlayer(  289): onCheckAudioStatus
V/AwesomePlayer(  289): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  289): onStreamDone
V/AwesomePlayer(  289): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  289): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb09100, 2, 0, 0)
V/AudioCache(  289): playback complete - thread will wake up later
V/AwesomePlayer(  289): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb09100, 7, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=1)
,V/AudioCache(  289): wait - success
V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): addBatteryData
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb09100, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
D/AudioPlayer(  289): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop() sendCommand(0x7b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  289): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  289): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  289): ~OggSource --
I/OggExtractor(  289): ~OggExtractor ++
I/OggExtractor(  289): ~MyVorbisExtractor ++ 
I/OggExtractor(  289): ~MyVorbisExtractor --
I/OggExtractor(  289): ~OggExtractor --
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,I/AudioPlayer(  289): reset out
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  289): SecVideoCapture destructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): mSecCapture clear
I/SecMediaClock(  289): SecMediaClock destructor
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): ~StagefrightPlayer
V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/AwesomePlayer(  289): destructor
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
,V/MediaPlayer( 8233): decode(37, 19129712, 4804)
V/MediaPlayerService(  289): decode(32, 19129712, 4804)
,V/MediaPlayerService(  289): player type = 3
,V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): constructor
V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): StagefrightPlayer
V/AwesomePlayer(  289): setListener
V/StagefrightPlayer(  289): initCheck
V/AwesomePlayer(  289): setAudioSink
V/StagefrightPlayer(  289): setDataSource(32, 19129712, 4804)
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb090b0, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
D/Utils   (  289): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  289): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  289): mBitrate = -1 bits/sec
I/OggExtractor(  289): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  289): current audio track index (0) is added to vector
V/AwesomePlayer(  289): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  289): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  289): prepare
V/AwesomePlayer(  289): prepareAsync
V/MediaPlayerService(  289): wait for prepare
V/AwesomePlayer(  289): onPrepareAsyncEvent
,I/SecMediaClock(  289): SecMediaClock constructor
I/SecMediaClock(  289): reset
I/SecVideoCapture(  289): SecVideoCapture constructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): initAudioDecoder
V/AwesomePlayer(  289): checkOffloadExceptions is true
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  289): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  289): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  289): finishAsyncPrepare_l
V/AwesomePlayer(  289): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache(  289): notify(0xafb090b0, 200, 973, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb090b0, 5, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb090b0, 1, 0, 0)
V/AudioCache(  289): prepared
V/AudioCache(  289): wait - success
V/MediaPlayerService(  289): start
,V/StagefrightPlayer(  289): start
V/AwesomePlayer(  289): play
V/AwesomePlayer(  289): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  289): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  289): start of Playback, useOffload 0
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  289): Audio channels(1)
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
,V/AudioCache(  289): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  289): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb090b0, 6, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): addBatteryData
,I/AudioPlayer(  289): First fillBuffer call!!
V/MediaPlayerService(  289): wait for playback complete
I/AudioPlayer(  289): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  289): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] End Of Stream,
,V/AwesomePlayer(  289): postAudioEOS delayUs (0)
V/AwesomePlayer(  289): onCheckAudioStatus
,V/AwesomePlayer(  289): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  289): onStreamDone
V/AwesomePlayer(  289): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  289): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb090b0, 2, 0, 0)
V/AudioCache(  289): playback complete - thread will wake up later
,V/AwesomePlayer(  289): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb090b0, 7, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  289): wait - success,
V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): addBatteryData
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb090b0, 8, 0, 0)
V/AudioCache(  289): ignored
,V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
D/AudioPlayer(  289): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  289): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  289): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  289): ~OggSource --
I/OggExtractor(  289): ~OggExtractor ++
I/OggExtractor(  289): ~MyVorbisExtractor ++ 
,I/OggExtractor(  289): ~MyVorbisExtractor --
I/OggExtractor(  289): ~OggExtractor --
I/AudioPlayer(  289): reset out
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
,I/SecVideoCapture(  289): SecVideoCapture destructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): mSecCapture clear
I/SecMediaClock(  289): SecMediaClock destructor
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): ~StagefrightPlayer
V/StagefrightPlayer(  289): reset,
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear,
V/AwesomePlayer(  289): mSecMediaClock clear
V/AwesomePlayer(  289): destructor
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
,V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/MediaPlayer( 8233): decode(43, 19099164, 9400)
V/MediaPlayerService(  289): decode(32, 19099164, 9400)
V/MediaPlayerService(  289): player type = 3
,V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): constructor
V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): StagefrightPlayer
V/AwesomePlayer(  289): setListener
,V/StagefrightPlayer(  289): initCheck
V/AwesomePlayer(  289): setAudioSink
V/StagefrightPlayer(  289): setDataSource(32, 19099164, 9400)
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  289): notify(0xafb091f0, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
,V/AwesomePlayer(  289): mSecMediaClock clear
D/Utils   (  289): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  289): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  289): mBitrate = -1 bits/sec
I/OggExtractor(  289): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  289): current audio track index (0) is added to vector,
V/AwesomePlayer(  289): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  289): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  289): prepare
V/AwesomePlayer(  289): prepareAsync
V/MediaPlayerService(  289): wait for prepare
V/AwesomePlayer(  289): onPrepareAsyncEvent,
I/SecMediaClock(  289): SecMediaClock constructor
I/SecMediaClock(  289): reset
I/SecVideoCapture(  289): SecVideoCapture constructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): initAudioDecoder
V/AwesomePlayer(  289): checkOffloadExceptions is true,
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  289): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
,I/AwesomePlayer(  289): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  289): finishAsyncPrepare_l
V/AwesomePlayer(  289): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  289): notify(0xafb091f0, 200, 973, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0),
V/AudioCache(  289): notify(0xafb091f0, 5, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb091f0, 1, 0, 0)
V/AudioCache(  289): prepared
V/AudioCache(  289): wait - success,
V/MediaPlayerService(  289): start
V/StagefrightPlayer(  289): start
V/MediaPlayer( 8233): decode(49, 19172584, 4112)
V/MediaPlayerService(  289): decode(37, 19172584, 4112)
V/MediaPlayerService(  289): player type = 3
V/AwesomePlayer(  289): setDefault,
V/AwesomePlayer(  289): constructor
V/AwesomePlayer(  289): play
V/AwesomePlayer(  289): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  289): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  289): start of Playback, useOffload 0
V/AwesomePlayer(  289): setDefault,
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): StagefrightPlayer
,V/AwesomePlayer(  289): setListener
V/StagefrightPlayer(  289): initCheck
V/AwesomePlayer(  289): setAudioSink
V/StagefrightPlayer(  289): setDataSource(37, 19172584, 4112)
V/AwesomePlayer(  289): reset_l()
,V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
,V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
D/Utils   (  289): printFileName fd(38) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
I/OMXCodec(  289): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/AwesomePlayer(  289): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  289): mBitrate = -1 bits/sec
I/OggExtractor(  289): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer(  289): current audio track index (0) is added to vector
V/AwesomePlayer(  289): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  289): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  289): prepare
V/AwesomePlayer(  289): prepareAsync
V/MediaPlayerService(  289): wait for prepare
,V/AwesomePlayer(  289): onPrepareAsyncEvent
I/SecMediaClock(  289): SecMediaClock constructor
I/SecMediaClock(  289): reset
I/SecVideoCapture(  289): SecVideoCapture constructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): initAudioDecoder
V/AwesomePlayer(  289): checkOffloadExceptions is true,
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  289): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  289): Could not offload audio decode, try pcm offload
,V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/AudioPlayer(  289): Audio channels(1)
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  289): open(44100, 1, 0x0, 1, 0),
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  289): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb091f0, 6, 0, 0)
V/AudioCache(  289): ignored
,V/AwesomePlayer(  289): addBatteryData
V/AwesomePlayer(  289): finishAsyncPrepare_l
V/AwesomePlayer(  289): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 200, 973, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 5, 0, 0)
,V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 1, 0, 0)
V/AudioCache(  289): prepared
V/AudioCache(  289): wait - success
V/MediaPlayerService(  289): start
V/StagefrightPlayer(  289): start,
V/AwesomePlayer(  289): play
V/AwesomePlayer(  289): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  289): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  289): start of Playback, useOffload 0
V/MediaPlayerService(  289): wait for playback complete
D/ShortcutReceiver( 8342):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,I/AudioPlayer(  289): First fillBuffer call!!
I/AudioPlayer(  289): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  289): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
I/OMXCodec(  289): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec(  289): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  289): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  289): >>>UHQA initOutputFormat 16,
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  289): Audio channels(1)
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  289): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  289): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0),
V/AudioCache(  289): notify(0xb061d330, 6, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): addBatteryData
I/AudioPlayer(  289): First fillBuffer call!!
I/AudioPlayer(  289): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  289): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  289): postAudioEOS delayUs (0)
V/MediaPlayerService(  289): wait for playback complete
V/AwesomePlayer(  289): onCheckAudioStatus
V/AwesomePlayer(  289): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  289): onStreamDone
V/AwesomePlayer(  289): MEDIA_PLAYBACK_COMPLETE
,V/AwesomePlayer(  289): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 2, 0, 0)
V/AudioCache(  289): playback complete - thread will wake up later
V/AwesomePlayer(  289): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 7, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  289): addBatteryData
V/AudioCache(  289): wait - success
V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 8, 0, 0)
V/AudioCache(  289): ignored
,V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
D/AudioPlayer(  289): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop() sendCommand(0x7e, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event ,
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  289): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  289): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  289): ~OggSource --
I/OggExtractor(  289): ~OggExtractor ++
I/OggExtractor(  289): ~MyVorbisExtractor ++ 
I/OggExtractor(  289): ~MyVorbisExtractor --
,I/OggExtractor(  289): ~OggExtractor --
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  289): reset out
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  289): SecVideoCapture destructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): mSecCapture clear
I/SecMediaClock(  289): SecMediaClock destructor
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): ~StagefrightPlayer
V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
,V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/AwesomePlayer(  289): destructor
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/AwesomePlayer(  289): postAudioEOS delayUs (0)
V/AwesomePlayer(  289): onCheckAudioStatus
V/AwesomePlayer(  289): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  289): onStreamDone
V/AwesomePlayer(  289): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  289): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb091f0, 2, 0, 0)
V/AudioCache(  289): playback complete - thread will wake up later
,V/AwesomePlayer(  289): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb091f0, 7, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  289): addBatteryData
V/AudioCache(  289): wait - success
V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb091f0, 8, 0, 0)
,V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
D/AudioPlayer(  289): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  289): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  289): OggSource::~OggSource() mExtractor !mStarted ref count = 1,
I/OggExtractor(  289): ~OggSource --
I/OggExtractor(  289): ~OggExtractor ++
I/OggExtractor(  289): ~MyVorbisExtractor ++ 
I/OggExtractor(  289): ~MyVorbisExtractor --
I/OggExtractor(  289): ~OggExtractor --
,I/AudioPlayer(  289): reset out
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  289): SecVideoCapture destructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): mSecCapture clear
I/SecMediaClock(  289): SecMediaClock destructor,
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): ~StagefrightPlayer
V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/AwesomePlayer(  289): destructor
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
,V/AwesomePlayer(  289): mSecMediaClock clear
V/MediaPlayer( 8233): decode(44, 19307764, 52024)
V/MediaPlayerService(  289): decode(32, 19307764, 52024)
V/MediaPlayerService(  289): player type = 3
V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): constructor
V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): reset_l()
,V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): StagefrightPlayer
V/AwesomePlayer(  289): setListener
V/StagefrightPlayer(  289): initCheck
V/AwesomePlayer(  289): setAudioSink,
V/StagefrightPlayer(  289): setDataSource(32, 19307764, 52024)
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d560, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
,V/AwesomePlayer(  289): mSecMediaClock clear
D/Utils   (  289): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  289): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  289): mBitrate = -1 bits/sec
I/OggExtractor(  289): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  289): current audio track index (0) is added to vector
V/AwesomePlayer(  289): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  289): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService(  289): prepare
V/AwesomePlayer(  289): prepareAsync
V/MediaPlayerService(  289): wait for prepare
V/AwesomePlayer(  289): onPrepareAsyncEvent
I/SecMediaClock(  289): SecMediaClock constructor
I/SecMediaClock(  289): reset
I/SecVideoCapture(  289): SecVideoCapture constructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): initAudioDecoder
,V/AwesomePlayer(  289): checkOffloadExceptions is true
V/AudioPolicyManager(  289): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  289): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  289): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  289): finishAsyncPrepare_l
V/AwesomePlayer(  289): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  289): notify(0xb061d560, 200, 973, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d560, 5, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d560, 1, 0, 0)
V/AudioCache(  289): prepared
V/AudioCache(  289): wait - success
V/MediaPlayerService(  289): start
V/StagefrightPlayer(  289): start
V/AwesomePlayer(  289): play
V/AwesomePlayer(  289): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  289): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  289): start of Playback, useOffload 0
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  289): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  289): Audio channels(2)
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  289): open(48000, 2, 0x0, 1, 0)
,V/AwesomePlayer(  289): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
I/AudioPlayer(  289): First fillBuffer call!!
V/AudioCache(  289): notify(0xb061d560, 6, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): addBatteryData
,D/PackageBroadcastService( 2437): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,V/MediaPlayerService(  289): wait for playback complete
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/PeopleContactsSync( 2437): CP2 sync disabled
,I/GAV4    ( 7991): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  853): Killing 7236:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##41
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  289): postAudioEOS delayUs (0)
,V/AwesomePlayer(  289): onCheckAudioStatus
,V/AwesomePlayer(  289): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  289): onStreamDone
V/AwesomePlayer(  289): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  289): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d560, 2, 0, 0)
V/AudioCache(  289): playback complete - thread will wake up later
V/AwesomePlayer(  289): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d560, 7, 0, 0)
,V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  289): addBatteryData
V/AudioCache(  289): wait - success
V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  289): notify(0xb061d560, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
D/AudioPlayer(  289): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop() sendCommand(0x7f, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  289): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  289): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  289): ~OggSource --
I/OggExtractor(  289): ~OggExtractor ++
,I/OggExtractor(  289): ~MyVorbisExtractor ++ 
I/OggExtractor(  289): ~MyVorbisExtractor --
I/OggExtractor(  289): ~OggExtractor --
,I/AudioPlayer(  289): reset out
,V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  289): SecVideoCapture destructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): mSecCapture clear
I/SecMediaClock(  289): SecMediaClock destructor
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): ~StagefrightPlayer
V/StagefrightPlayer(  289): reset
,V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/AwesomePlayer(  289): destructor
,V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
,V/MediaPlayer( 8233): decode(45, 19172584, 4112)
V/MediaPlayerService(  289): decode(33, 19172584, 4112)
,V/MediaPlayerService(  289): player type = 3
V/AwesomePlayer(  289): setDefault
,V/AwesomePlayer(  289): constructor
V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
,V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): StagefrightPlayer
V/AwesomePlayer(  289): setListener
V/StagefrightPlayer(  289): initCheck
V/AwesomePlayer(  289): setAudioSink
V/StagefrightPlayer(  289): setDataSource(33, 19172584, 4112)
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb09100, 8, 0, 0)
,V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
D/Utils   (  289): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  289): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  289): mBitrate = -1 bits/sec
I/OggExtractor(  289): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  289): current audio track index (0) is added to vector
V/AwesomePlayer(  289): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  289): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  289): prepare
,V/AwesomePlayer(  289): prepareAsync
V/MediaPlayerService(  289): wait for prepare
V/AwesomePlayer(  289): onPrepareAsyncEvent
I/SecMediaClock(  289): SecMediaClock constructor
I/SecMediaClock(  289): reset
I/SecVideoCapture(  289): SecVideoCapture constructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): initAudioDecoder
V/AwesomePlayer(  289): checkOffloadExceptions is true
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  289): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  289): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  289): finishAsyncPrepare_l
V/AwesomePlayer(  289): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  289): notify(0xafb09100, 200, 973, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb09100, 5, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb09100, 1, 0, 0)
V/AudioCache(  289): prepared
V/AudioCache(  289): wait - success
V/MediaPlayerService(  289): start
V/StagefrightPlayer(  289): start
V/AwesomePlayer(  289): play
V/AwesomePlayer(  289): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  289): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  289): start of Playback, useOffload 0
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  289): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  289): Audio channels(1)
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
,V/AudioCache(  289): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  289): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb09100, 6, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): addBatteryData
,V/MediaPlayerService(  289): wait for playback complete
I/AudioPlayer(  289): First fillBuffer call!!
I/AudioPlayer(  289): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  289): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  289): postAudioEOS delayUs (0)
V/AwesomePlayer(  289): onCheckAudioStatus
V/AwesomePlayer(  289): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  289): onStreamDone
,V/AwesomePlayer(  289): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  289): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb09100, 2, 0, 0)
V/AudioCache(  289): playback complete - thread will wake up later
V/AwesomePlayer(  289): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb09100, 7, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  289): addBatteryData
V/AudioCache(  289): wait - success
V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb09100, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  289): mAudioTrackVector clear
D/AudioPlayer(  289): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor(  289): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  289): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  289): ~OggSource --
I/OggExtractor(  289): ~OggExtractor ++
I/OggExtractor(  289): ~MyVorbisExtractor ++ 
I/OggExtractor(  289): ~MyVorbisExtractor --
I/OggExtractor(  289): ~OggExtractor --
I/AudioPlayer(  289): reset out
,V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  289): SecVideoCapture destructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): mSecCapture clear
I/SecMediaClock(  289): SecMediaClock destructor
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): ~StagefrightPlayer
,V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
,V/AwesomePlayer(  289): destructor
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
,V/AwesomePlayer(  289): mSecMediaClock clear
V/MediaPlayer( 8233): decode(46, 19235660, 21825)
V/MediaPlayerService(  289): decode(32, 19235660, 21825)
V/MediaPlayerService(  289): player type = 3
V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): constructor
V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): reset_l()
,V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): StagefrightPlayer
V/AwesomePlayer(  289): setListener,
V/StagefrightPlayer(  289): initCheck
V/AwesomePlayer(  289): setAudioSink
V/StagefrightPlayer(  289): setDataSource(32, 19235660, 21825)
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb090b0, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
D/Utils   (  289): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  289): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  289): mBitrate = -1 bits/sec
I/OggExtractor(  289): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer(  289): current audio track index (0) is added to vector
V/AwesomePlayer(  289): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  289): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  289): prepare
V/AwesomePlayer(  289): prepareAsync
V/MediaPlayerService(  289): wait for prepare
V/AwesomePlayer(  289): onPrepareAsyncEvent
,I/SecMediaClock(  289): SecMediaClock constructor
I/SecMediaClock(  289): reset
I/SecVideoCapture(  289): SecVideoCapture constructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): initAudioDecoder
V/AwesomePlayer(  289): checkOffloadExceptions is true
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  289): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  289): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  289): finishAsyncPrepare_l
V/AwesomePlayer(  289): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  289): notify(0xafb090b0, 200, 973, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb090b0, 5, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache(  289): notify(0xafb090b0, 1, 0, 0)
V/AudioCache(  289): prepared
V/AudioCache(  289): wait - success
V/MediaPlayerService(  289): start
V/StagefrightPlayer(  289): start
V/AwesomePlayer(  289): play
V/AwesomePlayer(  289): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  289): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  289): start of Playback, useOffload 0
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  289): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  289): Audio channels(2)
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  289): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  289): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb090b0, 6, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): addBatteryData
V/MediaPlayerService(  289): wait for playback complete
I/AudioPlayer(  289): First fillBuffer call!!
I/AudioPlayer(  289): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  289): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  289): postAudioEOS delayUs (0)
,V/AwesomePlayer(  289): onCheckAudioStatus
V/AwesomePlayer(  289): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  289): onStreamDone
V/AwesomePlayer(  289): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  289): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb090b0, 2, 0, 0)
V/AudioCache(  289): playback complete - thread will wake up later
V/AwesomePlayer(  289): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
W/libprocessgroup(  853): failed to open /acct/uid_10044/pid_7236/cgroup.procs: No such file or directory
V/AudioCache(  289): notify(0xafb090b0, 7, 0, 0)
,V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  289): addBatteryData
V/AudioCache(  289): wait - success
V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  289): notify(0xafb090b0, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
D/AudioPlayer(  289): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  289): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  289): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  289): ~OggSource --
,I/OggExtractor(  289): ~OggExtractor ++
I/OggExtractor(  289): ~MyVorbisExtractor ++ 
I/OggExtractor(  289): ~MyVorbisExtractor --
I/OggExtractor(  289): ~OggExtractor --
I/AudioPlayer(  289): reset out
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  289): SecVideoCapture destructor
I/SecVideoCapture(  289): reset
,V/AwesomePlayer(  289): mSecCapture clear
I/SecMediaClock(  289): SecMediaClock destructor
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): ~StagefrightPlayer
V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/AwesomePlayer(  289): destructor
,V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/MediaPlayer( 8233): decode(47, 19134596, 21552)
V/MediaPlayerService(  289): decode(32, 19134596, 21552)
V/MediaPlayerService(  289): player type = 3
V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): constructor
V/AwesomePlayer(  289): setDefault
,V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): StagefrightPlayer
V/AwesomePlayer(  289): setListener
V/StagefrightPlayer(  289): initCheck
V/AwesomePlayer(  289): setAudioSink
V/StagefrightPlayer(  289): setDataSource(32, 19134596, 21552)
V/AwesomePlayer(  289): reset_l()
,V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
D/Utils   (  289): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  289): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  289): mBitrate = -1 bits/sec
I/OggExtractor(  289): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  289): current audio track index (0) is added to vector
,V/AwesomePlayer(  289): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  289): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  289): prepare
V/AwesomePlayer(  289): prepareAsync
V/MediaPlayerService(  289): wait for prepare
V/AwesomePlayer(  289): onPrepareAsyncEvent
I/SecMediaClock(  289): SecMediaClock constructor
I/SecMediaClock(  289): reset
I/SecVideoCapture(  289): SecVideoCapture constructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): initAudioDecoder
V/AwesomePlayer(  289): checkOffloadExceptions is true
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
,V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  289): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  289): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  289): finishAsyncPrepare_l
V/AwesomePlayer(  289): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache(  289): notify(0xb061d330, 200, 973, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 5, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 1, 0, 0)
V/AudioCache(  289): prepared
V/AudioCache(  289): wait - success
V/MediaPlayerService(  289): start
V/StagefrightPlayer(  289): start
V/AwesomePlayer(  289): play
V/AwesomePlayer(  289): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  289): startAudioPlayer_l, sendErrorNotification (0)
,D/AudioPlayer(  289): start of Playback, useOffload 0
I/OMXCodec(  289): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  289): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  289): Audio channels(2)
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache(  289): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  289): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 6, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): addBatteryData
V/MediaPlayerService(  289): wait for playback complete
I/AudioPlayer(  289): First fillBuffer call!!
I/AudioPlayer(  289): >>> setAudioEffect Read mAudioFormat : 1, event : 4292761, value : -2137358184
E/AudioPlayer(  289): >>> setAudioEffect Error mAudioFormat : 1, event : 4292761, value : -2137358184
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  289): postAudioEOS delayUs (0)
V/AwesomePlayer(  289): onCheckAudioStatus
V/AwesomePlayer(  289): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  289): onStreamDone
V/AwesomePlayer(  289): MEDIA_PLAYBACK_COMPLETE
,V/AwesomePlayer(  289): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 2, 0, 0)
V/AudioCache(  289): playback complete - thread will wake up later
V/AwesomePlayer(  289): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 7, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  289): addBatteryData
V/AudioCache(  289): wait - success
,V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xb061d330, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
D/AudioPlayer(  289): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor(  289): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  289): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  289): ~OggSource --
I/OggExtractor(  289): ~OggExtractor ++
I/OggExtractor(  289): ~MyVorbisExtractor ++ 
I/OggExtractor(  289): ~MyVorbisExtractor --
I/OggExtractor(  289): ~OggExtractor --
I/AudioPlayer(  289): reset out
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  289): SecVideoCapture destructor
,I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): mSecCapture clear
I/SecMediaClock(  289): SecMediaClock destructor
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): ~StagefrightPlayer
V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
,V/AwesomePlayer(  289): destructor
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/MediaPlayer( 8233): decode(48, 19228560, 7017)
V/MediaPlayerService(  289): decode(32, 19228560, 7017)
V/MediaPlayerService(  289): player type = 3
V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): constructor
,V/AwesomePlayer(  289): setDefault
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): StagefrightPlayer
V/AwesomePlayer(  289): setListener
V/StagefrightPlayer(  289): initCheck
V/AwesomePlayer(  289): setAudioSink
V/StagefrightPlayer(  289): setDataSource(32, 19228560, 7017)
,V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb091f0, 8, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
D/Utils   (  289): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  289): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  289): mBitrate = -1 bits/sec
I/OggExtractor(  289): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  289): current audio track index (0) is added to vector
V/AwesomePlayer(  289): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  289): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  289): prepare
V/AwesomePlayer(  289): prepareAsync
,V/MediaPlayerService(  289): wait for prepare
V/AwesomePlayer(  289): onPrepareAsyncEvent
I/SecMediaClock(  289): SecMediaClock constructor
I/SecMediaClock(  289): reset
I/SecVideoCapture(  289): SecVideoCapture constructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): initAudioDecoder
,V/AwesomePlayer(  289): checkOffloadExceptions is true
V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  289): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  289): Could not offload audio decode, try pcm offload
,V/AudioPolicyManager(  289): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  289): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  289): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  289): finishAsyncPrepare_l
V/AwesomePlayer(  289): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache(  289): notify(0xafb091f0, 200, 973, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb091f0, 5, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb091f0, 1, 0, 0)
V/AudioCache(  289): prepared
,V/AudioCache(  289): wait - success
V/MediaPlayerService(  289): start
V/StagefrightPlayer(  289): start
V/AwesomePlayer(  289): play
V/AwesomePlayer(  289): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  289): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  289): start of Playback, useOffload 0
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  289): >>>UHQA initOutputFormat 16
I/OMXCodec(  289): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  289): Audio channels(2)
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  289): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  289): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  289): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  289): notify(0xafb091f0, 6, 0, 0)
V/AudioCache(  289): ignored
V/AwesomePlayer(  289): addBatteryData
V/MediaPlayerService(  289): wait for playback complete
I/AudioPlayer(  289): First fillBuffer call!!
I/AudioPlayer(  289): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  289): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  289): postAudioEOS delayUs (0)
,V/AwesomePlayer(  289): onCheckAudioStatus
,V/AwesomePlayer(  289): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  289): onStreamDone
V/AwesomePlayer(  289): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  289): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb091f0, 2, 0, 0)
V/AudioCache(  289): playback complete - thread will wake up later
V/AwesomePlayer(  289): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb091f0, 7, 0, 0)
,V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  289): addBatteryData
V/AudioCache(  289): wait - success
V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  289): notify(0xafb091f0, 8, 0, 0)
,V/AudioCache(  289): ignored
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
D/AudioPlayer(  289): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  289): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  289): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  289): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  289): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  289): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  289): ~OggSource --
I/OggExtractor(  289): ~OggExtractor ++
I/OggExtractor(  289): ~MyVorbisExtractor ++ 
I/OggExtractor(  289): ~MyVorbisExtractor --
I/OggExtractor(  289): ~OggExtractor --
,I/AudioPlayer(  289): reset out
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  289): SecVideoCapture destructor
I/SecVideoCapture(  289): reset
V/AwesomePlayer(  289): mSecCapture clear
I/SecMediaClock(  289): SecMediaClock destructor
V/AwesomePlayer(  289): mSecMediaClock clear
V/StagefrightPlayer(  289): ~StagefrightPlayer
,V/StagefrightPlayer(  289): reset
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
,V/AwesomePlayer(  289): destructor
V/AwesomePlayer(  289): reset_l()
V/AwesomePlayer(  289): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  289): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  289): mAudioTrackVector clear
V/AwesomePlayer(  289): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  289): mSecCapture clear
V/AwesomePlayer(  289): mSecMediaClock clear
,I/SecureStorage(  330): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage(  330): [INFO]: SPID(0x00000005)PID: 8254, TID: 8268
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/SSRM:m  (  853): SIOP:: AP = 410, PST = 422, CUR = 300
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,E/SMD     (  282): DCD ON
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/SurfaceFlinger(  249): id=16 Removed Toast (8/8)
,I/SurfaceFlinger(  249): id=16 Removed Toast (-2/8)
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/SecureStorage( 8254): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 8254): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
,I/SecSQLiteOpenHelper( 8233): getWritableDatabase(pwd)
,I/SecSQLiteOpenHelper( 8233): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper( 8233): Open platform.db in secure mode
,D/SecSQLiteDatabase( 8233): Android Version: 5.0
,D/SecSQLiteDatabase( 8233): Load library secsqlite.so for Android 5.0
,I/SecSQLiteDatabase( 8233): openSecureDatabase...
,I/SecSQLiteDatabase( 8233): private openSecureDatabase...
,I/SecSQLiteConnectionPool( 8233): OpenSecure
I/SecSQLiteConnectionPool( 8233): OpenSecure with password
I/SecSQLiteConnectionPool( 8233): openSecureConnectionLocked
,I/SecSQLiteDatabase( 8233): ...private openSecureDatabase
I/SecSQLiteDatabase( 8233): ...openSecureDatabase
,I/SecSQLiteOpenHelper( 8233): ...getDatabaseLocked(b,b,pwd)
,D/SecSQLiteOpenHelper( 8233): ...getDatabaseLocked(b,b,pwd)
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8233): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,W/System.err( 8233): java.lang.NumberFormatException: Invalid int: "null"
,W/System.err( 8233): 	at java.lang.Integer.invalidInt(Integer.java:138)
,W/System.err( 8233): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err( 8233): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err( 8233): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:449)
,W/System.err( 8233): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1173)
W/System.err( 8233): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8233): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 8233): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7760): mConnectivityHandler : connected
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7760): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 7760): ================================================
,I/CSTORAGE( 7760):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 7760): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7760): [GetString-S]
,E/art     ( 7760): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI( 7760): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7760): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7760): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7760): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7760): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7760): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 7861): wlan0: sending IPv6 Router Solicitation
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  853): CMD_RSSI_POLL : out!
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,I/ServiceManager(  320): Waiting for service AtCmdFwd...,
,I/GAV3    ( 8233): Thread[GAThread,5,main]: No campaign data found.
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  853): CMD_RSSI_POLL : out!
,I/dhcpcd  ( 7861): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7861): wlan0: no IPv6 Routers available
,E/SMD     (  282): DCD ON
,D/PreloadUpdateManagerStateMachine( 7159): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7159): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7159): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7159): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7159): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7159): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7159): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7159): entry::IDLE
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/PreloadUpdateManagerStateMachine( 7159): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7159): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7159): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7159): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7159): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7159): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7159): entry::IDLE
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/FactoryTest( 6732): Not factory mode
D/FactoryTest( 6732): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6732): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6732): still no open session command from host, so toast
,W/ContextImpl( 6732): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6732): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
I/Timeline( 6732): Timeline: Activity_launch_request id:com.android.settings time:117441
,E/PersonaManagerService(  853): inState():  stateMachine is null !!,
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  853): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  853): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 853  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  853): mDVFSHelper.acquire()
,V/AlarmManager(  853): waitForAlarm result :4
,I/SQLiteSecureOpenHelper( 3587): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3587): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,E/MTPRx   ( 6732): started activity for popup
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ResourcesManager( 6732): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6732): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6732): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6732): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6732): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6732): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6732): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6732): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,V/AlarmManager(  853): waitForAlarm result :4
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SettingsReceiverActivity( 6732): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/InputMethodManagerService(  853): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,E/ActivityManager(  853): Invalid thumbnail dimensions: 576x576
,W/InputMethodManagerService(  853): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1c848ca4 attribute=null, token = android.os.BinderProxy@29c5293c
,I/SQLiteSecureOpenHelper( 3587): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3587): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6732): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6732): dev.kiessupport is : TRUE
,D/Activity( 6732): performCreate Call secproduct feature valuefalse
,D/Activity( 6732): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ActivityManager(  853): post active user change for 0
W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 1
D/KnoxTimeoutHandler(  853): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  853): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/Timeline( 7634): Timeline: Activity_idle id: android.os.BinderProxy@137981d2 time:117744
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6629): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6629): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6629): [1] 5.onFinished: Scheduling replication attempt 3.
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  853): CMD_RSSI_POLL : out!
,I/art     (  853): Explicit concurrent mark sweep GC freed 65554(3MB) AllocSpace objects, 9(2MB) LOS objects, 30% free, 36MB/52MB, paused 1.369ms total 97.110ms
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 370, PST = 413, CUR = 300
,D/CustomFrequencyManagerService(  853): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 853  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  853): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  853): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 853  pkgName : ACTIVITY_RESUME_BOOSTER@10
,D/CustomFrequencyManagerService(  853): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 853  tag : ACTIVITY_RESUME_BOOSTER@10
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  853): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,E/SMD     (  282): DCD ON
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  853): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  853): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 2
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/SSRM:m  (  853): SIOP:: AP = 340, PST = 400, CUR = 300
D/X       (  853): broadcastSiopLevelIntent:: currentSiopLevel = -1
,D/ContentApp( 1221):  LEVEL : -1,
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,I/SystemBroadcastReceiver( 7199): [#DCM#] [DCM_Performance] onReceive completed in time  2084 microsec. 
,I/SystemBroadcastReceiver( 7199): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7199): [#DCM#] onReceive action = EVENT_SIOP
,I/ActivityManager(  853): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=8440 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,E/Zygote  ( 8440): MountEmulatedStorage()
,E/Zygote  ( 8440): v2
,I/libpersona( 8440): KNOX_SDCARD checking this for 10054
,I/libpersona( 8440): KNOX_SDCARD not a persona
,I/SELinux ( 8440): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8440): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8440): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8440): TimaSignature is unavailable
,D/ActivityThread( 8440): Added TimaKeyStore provider
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8440): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8440): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8440): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8440): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8440): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/TranscodeReceiver( 8440): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 8440): core_num = 4
,W/linker  ( 8440): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 8440): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 8440): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
D/videowall-Global( 8440): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 8440):  SIOP_LEVEL: -1
,I/ActivityManager(  853): Killing 5064:com.android.defcontainer/u0a5 (adj 15): bgCount ##41
,W/libprocessgroup(  853): failed to open /acct/uid_10005/pid_5064/cgroup.procs: No such file or directory
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  853): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/SMD     (  282): DCD ON
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  853): CMD_RSSI_POLL : out!
,D/PowerManagerService(  853): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  853): getFinalBrightness : 15 -> 15
,D/PowerManagerService(  853): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  853): lcd : 31 +
,D/lights  (  853): lcd : 31 -
,D/lights  (  853): lcd : 22 +
,D/lights  (  853): lcd : 22 -
,D/lights  (  853): lcd : 15 +
D/DisplayPowerController(  853): getFinalBrightness : 15 -> 15
,D/lights  (  853): lcd : 15 -
,D/DisplayPowerController(  853): getFinalBrightness : 15 -> 15
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 4
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  853): CMD_RSSI_POLL : out!
,E/SMD     (  282): DCD ON
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/AlarmManager(  853): waitForAlarm result :4,
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  853): Plugged
I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6629): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6629): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6629): [1] 5.onFinished: Scheduling replication attempt 4.
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  853): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  853): CMD_RSSI_POLL : out!
,D/PowerManagerService(  853): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  853): Nap time (uid 1000)...
,I/PowerManagerService(  853): !@[ps] Screen__Off(2) : 
,I/PowerManagerService(  853): Going to sleep due to screen timeout (uid 1000)...
,D/PowerManagerService(  853): [PWL] sb acquire: PowerManagerService.Broadcasts
D/InputManager-JNI(  853): setDeviceInteractive: 0
,D/PowerManagerService(  853): SecHardwareInterface.setBatteryADC : false
,D/InputManager-JNI(  853): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  853): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  853): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/PowerManagerService(  853): handleSandman : startDream()
,D/InputManager-JNI(  853): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/SContextService(  853): 	.unregisterCallback : 1, client=
D/SContextService(  853): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@73dbe1, Service = Auto Rotation, used = 1
,E/PowerManagerService(  853): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  853): Sleeping (uid 1000)...
D/PowerManagerService(  853): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  853): [input device light] setInputDeviceLightOn is called : 0
,W/CAE     (  853): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
D/PowerManagerService(  853): [input device light] handleInputDeviceLightOff
,I/SurfaceFlinger(  249): id=17 createSurf (1080x1920),2 flag=404, ColorFade
,V/CAE     (  853): stop(ContextProvider.java:149)
,V/CAE     (  853): clear(AutoRotationRunner.java:182)
,V/CAE     (  853): disable(AutoRotationRunner.java:171)
,I/CAE     (  853): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  853): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  295): sendContextData: -78, 7, 0, 0
,D/CAE     (  853): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  853): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  853): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  853): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  853): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  853): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  853): removeSContextService() : service = Auto Rotation
,D/SContextService(  853): ===== SContext Service List =====
D/SContextManager(  853):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@147826ba, service=Auto Rotation
,D/KeyguardViewMediator( 1171): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1171): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1171): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1171): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/KeyguardViewMediator( 1171): timeout : 5000
,I/SQLiteSecureOpenHelper( 3587): getWritableDatabase(pwd)
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/DisplayPowerController(  853): ColorFade: onAnimationStart
,D/DisplayPowerController(  853): getFinalBrightness : 39 -> 0
,D/lights  (  853): lcd : 8 +
,I/SQLiteSecureOpenHelper( 3587): getDatabaseLocked(b,b,pwd)...
,D/lights  (  853): lcd : 8 -
,D/lights  (  853): lcd : 0 +
,D/DisplayPowerController(  853): getFinalBrightness : 39 -> 0
,D/lights  (  853): lcd : 0 -
,D/KeyguardViewMediator( 1171): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1171): handleNotifyScreenOff
D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/LightsService(  853): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 853) 
,D/LightsService(  853): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  853): [SvcLED]  onSensorChanged::light value = 22
,D/SensorManager(  853): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  853): unregisterListener ::   
D/lights  (  853): led_pattern : 5 +
,D/BatteryService(  853): turn on LED for fully charged
,D/lights  (  853): led_pattern : 5 -
,D/LightsService(  853): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=4) OUT; SvcLED(id=3) IN
,I/CAE     (  853): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  853): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  853): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  853): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  295): sendContextData: -76, 13, -46, 0
,I/CAE     (  853): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 12, 20, 49,
D/SensorHubManager(  853): SendSensorHubData: send data = -63, 14, 12, 20, 49
D/Sensorhubs(  295): sendContextData: -63, 14, 12, 20, 49
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  853):  handler : SCREEN_OFF end 
,D/WifiStateMachine(  853): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  853): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  853): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  853): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  853): do suspend true
,D/NotificationService(  853): ACTION_SCREEN_OFF
,D/LightsService(  853): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 853) 
,D/LightsService(  853): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
D/LightsService(  853): [SvcLED]  onSensorChanged::light value = 22
,D/SensorManager(  853): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  853): unregisterListener ::   
D/lights  (  853): led_pattern : 3 +
,D/lights  (  853): led_pattern : 3 -
D/LightsService(  853): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  289): adev_set_parameters: enter: screen_state=off
,V/voice   (  289): voice_set_parameters: enter: screen_state=off
V/voice   (  289): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  289): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  289): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  289): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  289): adev_set_parameters: exit
,E/SMD     (  282): DCD ON
,I/SecExternalDisplayIntents_Java(  853): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  853): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController(  853): Bridge Server is not available
,D/DisplayPowerState(  853): !@ ColorFade entry
,D/DisplayPowerController(  853): ColorFade: onAnimationEnd
,D/VolumePanel( 1171): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1171): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1171): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1171): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/AutomaticBrightnessController(  853): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  853): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
D/AutomaticBrightnessController(  853): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,E/LightSensor(  853): Light old sensor_state 8705, new sensor_state : 8193 en : 0
I/AutomaticBrightnessController(  853): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/SensorManager(  853): unregisterListener ::   
,E/Sensors (  853): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/PersonaManagerService(  853): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  853): MSG_ACTION_SCREEN_OFF called
,D/SensorManager(  853): unregisterListener ::   
,D/NfcService( 1468): call the applyRotuiing
,D/DisplayPowerController(  853): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  853): getFinalBrightness : 0 -> 0
I/DisplayManagerService(  853): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  853): Display changed displayId=0
D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6962000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/SSRM:m  (  853): SIOP:: AP = 330, PST = 385, CUR = 300
,D/StatusBar.NetworkController( 1171): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/STATUSBAR-PhoneStatusBar( 1171):      ACTION_SCREEN_OFF is finished!!!! 
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
E/StatusBar( 1171): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1171): dismissHelpPopup 
,D/accuweather( 2111): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 2111): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
,D/accuweather( 2111): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,I/SystemBroadcastReceiver( 7199): [#DCM#] [DCM_Performance] onReceive completed in time  179 microsec. 
,I/SystemBroadcastReceiver( 7199): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7199): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 7199): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,W/ActivityManager(  853): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/SSRM:m  (  853): SIOP:: AP = 330, PST = 373, CUR = 300
,W/ActivityManager(  853): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/PowerManagerService(  853): [PWL] sb release: PowerManagerService.Broadcasts
,I/rmt_storage(  273): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6c01090
,I/rmt_storage(  273): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  273): wakelock acquired: 1, error no: 42
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1228406656)
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1228406656) wakelock released: 1, error no: 22
I/rmt_storage(  273): 
,I/rmt_storage(  273): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6c01090
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  853): Excessive delay in setPowerMode(): 255ms
D/PowerManagerService(  853): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  853): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  853): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  853): Got set_interactive hint
,I/PowerManagerService(  853): [PWL] Off : 0s ago
I/PowerManagerService(  853): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  853): [PWL]     mDisplayReady : false
,D/DisplayPowerController(  853): getFinalBrightness : 0 -> 0
D/PowerManagerService(  853): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  853): [PWL] sb release: PowerManagerService.Display
,I/ServiceManager(  320): Waiting for service AtCmdFwd...,
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager(  853): waitForAlarm result :4
,D/KeyguardViewMediator( 1171): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1171): isKioskContainerExistOnDevice,
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/KeyguardViewMediator( 1171): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService(  853): [PWL] Off : 5s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 320, PST = 364, CUR = 300
,V/AlarmManager(  853): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  853): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): stay LED for fully charged
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
I/MotionRecognitionService(  853): setPowerConnected  = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  282): DCD ON
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
D/SecContentProvider2(  853): mCursor = null
,D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6595): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6595): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6595): 	at kfv.a(PG:65)
E/HttpOperation( 6595): 	at kff.u(PG:385)
E/HttpOperation( 6595): 	at kfb.a(PG:29)
E/HttpOperation( 6595): 	at kff.l(PG:132)
E/HttpOperation( 6595): 	at dsf.a(PG:807)
E/HttpOperation( 6595): 	at fhk.a(PG:1126)
E/HttpOperation( 6595): 	at fhk.a(PG:908)
E/HttpOperation( 6595): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6595): 	at ihi.a(PG:22)
E/HttpOperation( 6595): 	at kft.a(PG:91)
E/HttpOperation( 6595): 	at kfv.a(PG:62)
E/HttpOperation( 6595): 	... 8 more
E/HttpOperation( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6595): 	at gde.c(Unknown Source)
E/HttpOperation( 6595): 	at gde.b(Unknown Source)
E/HttpOperation( 6595): 	at ihi.a(PG:19)
E/HttpOperation( 6595): 	... 10 more
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
,D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,I/PowerManagerService(  853): [PWL] Off : 15s ago
,I/PowerManagerService(  853): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  853): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  853): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.plus.content.EsProvider/com.google/eM_ADDR' (uid=1000, pid=853, ws=WorkSource{10135}) (elapsedTime=508)
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6595): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6595): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6595): 	at kfv.a(PG:65)
E/HttpOperation( 6595): 	at kff.u(PG:385)
E/HttpOperation( 6595): 	at kfb.a(PG:29)
E/HttpOperation( 6595): 	at kff.l(PG:132)
E/HttpOperation( 6595): 	at ieo.a(PG:43)
E/HttpOperation( 6595): 	at iep.a(PG:93)
E/HttpOperation( 6595): 	at fhn.a(PG:59)
E/HttpOperation( 6595): 	at lex.a(PG:85)
E/HttpOperation( 6595): 	at lex.b(PG:132)
E/HttpOperation( 6595): 	at fhk.a(PG:1146)
E/HttpOperation( 6595): 	at fhk.a(PG:908)
E/HttpOperation( 6595): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6595): 	at ihi.a(PG:22)
E/HttpOperation( 6595): 	at kft.a(PG:91)
E/HttpOperation( 6595): 	at kfv.a(PG:62)
E/HttpOperation( 6595): 	... 12 more
E/HttpOperation( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6595): 	at gde.c(Unknown Source)
E/HttpOperation( 6595): 	at gde.b(Unknown Source)
E/HttpOperation( 6595): 	at ihi.a(PG:19)
E/HttpOperation( 6595): 	... 14 more
,E/ExperimentLoader( 6595): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6595): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6595): 	at kfv.a(PG:65)
E/ExperimentLoader( 6595): 	at kff.u(PG:385)
E/ExperimentLoader( 6595): 	at kfb.a(PG:29)
E/ExperimentLoader( 6595): 	at kff.l(PG:132)
E/ExperimentLoader( 6595): 	at ieo.a(PG:43)
E/ExperimentLoader( 6595): 	at iep.a(PG:93)
E/ExperimentLoader( 6595): 	at fhn.a(PG:59)
E/ExperimentLoader( 6595): 	at lex.a(PG:85)
E/ExperimentLoader( 6595): 	at lex.b(PG:132)
E/ExperimentLoader( 6595): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6595): 	at fhk.a(PG:908)
E/ExperimentLoader( 6595): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6595): 	at ihi.a(PG:22)
E/ExperimentLoader( 6595): 	at kft.a(PG:91)
E/ExperimentLoader( 6595): 	at kfv.a(PG:62)
E/ExperimentLoader( 6595): 	... 12 more
E/ExperimentLoader( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6595): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6595): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6595): 	at ihi.a(PG:19)
E/ExperimentLoader( 6595): 	... 14 more
I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
,D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 6595): [getaccountstatus] Unexpected exception
E/HttpOperation( 6595): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6595): 	at kfv.a(PG:65)
E/HttpOperation( 6595): 	at kff.u(PG:385)
E/HttpOperation( 6595): 	at kfb.a(PG:29)
E/HttpOperation( 6595): 	at ixd.a(PG:248)
E/HttpOperation( 6595): 	at ixd.b(PG:206)
E/HttpOperation( 6595): 	at ixd.a(PG:175)
E/HttpOperation( 6595): 	at fig.a(PG:78)
E/HttpOperation( 6595): 	at lex.a(PG:85)
E/HttpOperation( 6595): 	at lex.b(PG:132)
E/HttpOperation( 6595): 	at fhk.a(PG:1146)
E/HttpOperation( 6595): 	at fhk.a(PG:908)
E/HttpOperation( 6595): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6595): 	at ihi.a(PG:22)
E/HttpOperation( 6595): 	at kft.a(PG:91)
E/HttpOperation( 6595): 	at kfv.a(PG:62)
E/HttpOperation( 6595): 	... 12 more
E/HttpOperation( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6595): 	at gde.c(Unknown Source)
E/HttpOperation( 6595): 	at gde.b(Unknown Source)
E/HttpOperation( 6595): 	at ihi.a(PG:19)
E/HttpOperation( 6595): 	... 14 more
,E/EsSyncAdapterService( 6595): Sync failure
E/EsSyncAdapterService( 6595): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6595): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6595): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6595): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6595): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6595): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6595): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6595): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6595): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6595): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6595): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6595): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6595): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6595): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6595): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6595): 	... 10 more
E/EsSyncAdapterService( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6595): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6595): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6595): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6595): 	... 12 more
E/EsSyncAdapterService( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6595): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6595): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6595): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6595): 	... 14 more
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  853): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 154200, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  853): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  853): mCursor = null
,E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/SSRM:m  (  853): SIOP:: AP = 310, PST = 354, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 5
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 310, PST = 345, CUR = 300
,I/PowerManagerService(  853): [PWL] Off : 30s ago
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  853): waitForAlarm result :4
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1677): Explicit concurrent mark sweep GC freed 40444(2MB) AllocSpace objects, 26(2MB) LOS objects, 39% free, 17MB/29MB, paused 676us total 54.851ms
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/VacuumService( 1677): Vacuum at: now=1452860482415 tag=VacuumService
,I/GoogleURLConnFactory( 1677): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
,D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/Uploader( 1677): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1677): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1677): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1677): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1677): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1677): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1677): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1677): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1677): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1677): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,I/System.out( 1677): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1677): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1677): (HTTPLog)-Thread-205-827485926: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1677): Tagging socket 55 with tag 120100000000{4609,0} uid -1, pid: 1677, getuid(): 10012
,I/qtaguid ( 1677): Tagging socket 61 with tag 120100000000{4609,0} uid -1, pid: 1677, getuid(): 10012
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1677): No account for auth token provided
,I/qtaguid ( 1677): Tagging socket 55 with tag 120100000000{4609,0} uid -1, pid: 1677, getuid(): 10012
,D/Finsky  ( 6629): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6629): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6629): [1] 5.onFinished: Scheduling replication attempt 5.
,W/Uploader( 1677): No account for auth token provided
,I/qtaguid ( 1677): Tagging socket 55 with tag 120100000000{4609,0} uid -1, pid: 1677, getuid(): 10012
,W/Uploader( 1677): No account for auth token provided
,I/qtaguid ( 1677): Tagging socket 55 with tag 120100000000{4609,0} uid -1, pid: 1677, getuid(): 10012
,W/Uploader( 1677): No account for auth token provided
,I/qtaguid ( 1677): Tagging socket 55 with tag 120100000000{4609,0} uid -1, pid: 1677, getuid(): 10012
,W/Uploader( 1677): No account for auth token provided
,I/qtaguid ( 1677): Tagging socket 55 with tag 120100000000{4609,0} uid -1, pid: 1677, getuid(): 10012
,W/Uploader( 1677):  no longer exists, so no auth token.
,I/qtaguid ( 1677): Tagging socket 55 with tag 120100000000{4609,0} uid -1, pid: 1677, getuid(): 10012
,E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON,
,V/AlarmManager(  853): waitForAlarm result :4
,D/SSRM:m  (  853): SIOP:: AP = 310, PST = 339, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/AlarmManager(  853): waitForAlarm result :4
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7500): Starting books sync, d
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  282): DCD ON
,D/ResourcesManager( 1677): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7500): Authentication error
E/BooksAccountManager( 7500): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7500): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7500): null auth token
,I/qtaguid ( 7500): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7500, getuid(): 10082
,I/qtaguid ( 7500): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7500, getuid(): 10082
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/qtaguid ( 7500): Untagging socket 34
,W/ApiaryClient( 7500): Error response from books API: {
W/ApiaryClient( 7500):  "error": {
W/ApiaryClient( 7500):   "errors": [
W/ApiaryClient( 7500):    {
W/ApiaryClient( 7500):     "domain": "global",
W/ApiaryClient( 7500):     "reason": "required",
W/ApiaryClient( 7500):     "message": "Login Required",
W/ApiaryClient( 7500):     "locationType": "header",
W/ApiaryClient( 7500):     "location": "Authorization"
W/ApiaryClient( 7500):    }
W/ApiaryClient( 7500):   ],
W/ApiaryClient( 7500):   "code": 401,
W/ApiaryClient( 7500):   "message": "Login Required"
W/ApiaryClient( 7500):  }
W/ApiaryClient( 7500): }
,W/ApiaryClient( 7500): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=637353671776632542&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7500): Headers suppressed
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
,D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7500): Authentication error
E/BooksAccountManager( 7500): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7500): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7500): null auth token
,I/qtaguid ( 7500): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7500, getuid(): 10082
,I/qtaguid ( 7500): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7500, getuid(): 10082
,I/qtaguid ( 7500): Untagging socket 34
,W/ApiaryClient( 7500): Error response from books API: {
W/ApiaryClient( 7500):  "error": {
W/ApiaryClient( 7500):   "errors": [
W/ApiaryClient( 7500):    {
W/ApiaryClient( 7500):     "domain": "global",
W/ApiaryClient( 7500):     "reason": "required",
W/ApiaryClient( 7500):     "message": "Login Required",
W/ApiaryClient( 7500):     "locationType": "header",
W/ApiaryClient( 7500):     "location": "Authorization"
W/ApiaryClient( 7500):    }
W/ApiaryClient( 7500):   ],
W/ApiaryClient( 7500):   "code": 401,
W/ApiaryClient( 7500):   "message": "Login Required"
W/ApiaryClient( 7500):  }
W/ApiaryClient( 7500): }
,W/ApiaryClient( 7500): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=637353671776632542&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7500): Headers suppressed
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7500): Authentication error
E/BooksAccountManager( 7500): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7500): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7500): null auth token
,I/qtaguid ( 7500): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7500, getuid(): 10082
,I/qtaguid ( 7500): Untagging socket 34
,W/ApiaryClient( 7500): Error response from books API: {
W/ApiaryClient( 7500):  "error": {
W/ApiaryClient( 7500):   "errors": [
W/ApiaryClient( 7500):    {
W/ApiaryClient( 7500):     "domain": "global",
W/ApiaryClient( 7500):     "reason": "required",
W/ApiaryClient( 7500):     "message": "Login Required",
W/ApiaryClient( 7500):     "locationType": "header",
W/ApiaryClient( 7500):     "location": "Authorization"
W/ApiaryClient( 7500):    }
W/ApiaryClient( 7500):   ],
W/ApiaryClient( 7500):   "code": 401,
W/ApiaryClient( 7500):   "message": "Login Required"
W/ApiaryClient( 7500):  }
W/ApiaryClient( 7500): }
,W/ApiaryClient( 7500): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=637353671776632542&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7500): Headers suppressed
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 5
,E/BooksSync( 7500): Soft error
E/BooksSync( 7500): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=637353671776632542&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7500): Headers suppressed
E/BooksSync( 7500): 
E/BooksSync( 7500): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7500): Sync error
E/BooksSync( 7500): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=637353671776632542&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7500): Headers suppressed
E/BooksSync( 7500): 
E/BooksSync( 7500): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7500): Finished books sync
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  853): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 157846, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  853): Explicit concurrent mark sweep GC freed 61671(3MB) AllocSpace objects, 33(983KB) LOS objects, 30% free, 36MB/52MB, paused 1.759ms total 131.054ms
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  853): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  853): mCursor = null
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1677): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
D/SecContentProvider2(  853): mCursor = null
,D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6595): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6595): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6595): 	at kfv.a(PG:65)
E/HttpOperation( 6595): 	at kff.u(PG:385)
E/HttpOperation( 6595): 	at kfb.a(PG:29)
E/HttpOperation( 6595): 	at kff.l(PG:132)
E/HttpOperation( 6595): 	at dsf.a(PG:807)
E/HttpOperation( 6595): 	at fhk.a(PG:1126)
E/HttpOperation( 6595): 	at fhk.a(PG:908)
E/HttpOperation( 6595): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6595): 	at ihi.a(PG:22)
E/HttpOperation( 6595): 	at kft.a(PG:91)
E/HttpOperation( 6595): 	at kfv.a(PG:62)
E/HttpOperation( 6595): 	... 8 more
E/HttpOperation( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6595): 	at gde.c(Unknown Source)
E/HttpOperation( 6595): 	at gde.b(Unknown Source)
E/HttpOperation( 6595): 	at ihi.a(PG:19)
E/HttpOperation( 6595): 	... 10 more
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
D/SecContentProvider2(  853): mCursor = null
,D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 6595): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6595): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6595): 	at kfv.a(PG:65)
E/HttpOperation( 6595): 	at kff.u(PG:385)
E/HttpOperation( 6595): 	at kfb.a(PG:29)
E/HttpOperation( 6595): 	at kff.l(PG:132)
E/HttpOperation( 6595): 	at ieo.a(PG:43)
E/HttpOperation( 6595): 	at iep.a(PG:93)
E/HttpOperation( 6595): 	at fhn.a(PG:59)
E/HttpOperation( 6595): 	at lex.a(PG:85)
E/HttpOperation( 6595): 	at lex.b(PG:132)
E/HttpOperation( 6595): 	at fhk.a(PG:1146)
E/HttpOperation( 6595): 	at fhk.a(PG:908)
E/HttpOperation( 6595): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6595): 	at ihi.a(PG:22)
E/HttpOperation( 6595): 	at kft.a(PG:91)
E/HttpOperation( 6595): 	at kfv.a(PG:62)
E/HttpOperation( 6595): 	... 12 more
E/HttpOperation( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6595): 	at gde.c(Unknown Source)
E/HttpOperation( 6595): 	at gde.b(Unknown Source)
E/HttpOperation( 6595): 	at ihi.a(PG:19)
E/HttpOperation( 6595): 	... 14 more
,E/ExperimentLoader( 6595): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6595): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6595): 	at kfv.a(PG:65)
E/ExperimentLoader( 6595): 	at kff.u(PG:385)
E/ExperimentLoader( 6595): 	at kfb.a(PG:29)
E/ExperimentLoader( 6595): 	at kff.l(PG:132)
E/ExperimentLoader( 6595): 	at ieo.a(PG:43)
E/ExperimentLoader( 6595): 	at iep.a(PG:93)
E/ExperimentLoader( 6595): 	at fhn.a(PG:59)
E/ExperimentLoader( 6595): 	at lex.a(PG:85)
E/ExperimentLoader( 6595): 	at lex.b(PG:132)
E/ExperimentLoader( 6595): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6595): 	at fhk.a(PG:908)
E/ExperimentLoader( 6595): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6595): 	at ihi.a(PG:22)
E/ExperimentLoader( 6595): 	at kft.a(PG:91)
E/ExperimentLoader( 6595): 	at kfv.a(PG:62)
E/ExperimentLoader( 6595): 	... 12 more
E/ExperimentLoader( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6595): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6595): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6595): 	at ihi.a(PG:19)
E/ExperimentLoader( 6595): 	... 14 more
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
,D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 6595): [getaccountstatus] Unexpected exception
E/HttpOperation( 6595): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6595): 	at kfv.a(PG:65)
E/HttpOperation( 6595): 	at kff.u(PG:385)
E/HttpOperation( 6595): 	at kfb.a(PG:29)
E/HttpOperation( 6595): 	at ixd.a(PG:248)
E/HttpOperation( 6595): 	at ixd.b(PG:206)
E/HttpOperation( 6595): 	at ixd.a(PG:175)
E/HttpOperation( 6595): 	at fig.a(PG:78)
E/HttpOperation( 6595): 	at lex.a(PG:85)
E/HttpOperation( 6595): 	at lex.b(PG:132)
E/HttpOperation( 6595): 	at fhk.a(PG:1146)
E/HttpOperation( 6595): 	at fhk.a(PG:908)
E/HttpOperation( 6595): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6595): 	at ihi.a(PG:22)
E/HttpOperation( 6595): 	at kft.a(PG:91)
E/HttpOperation( 6595): 	at kfv.a(PG:62)
E/HttpOperation( 6595): 	... 12 more
E/HttpOperation( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6595): 	at gde.c(Unknown Source)
E/HttpOperation( 6595): 	at gde.b(Unknown Source)
E/HttpOperation( 6595): 	at ihi.a(PG:19)
E/HttpOperation( 6595): 	... 14 more
,E/EsSyncAdapterService( 6595): Sync failure
E/EsSyncAdapterService( 6595): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6595): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6595): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6595): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6595): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6595): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6595): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6595): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6595): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6595): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6595): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6595): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6595): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6595): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6595): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6595): 	... 10 more
E/EsSyncAdapterService( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6595): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6595): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6595): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6595): 	... 12 more
E/EsSyncAdapterService( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6595): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6595): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6595): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6595): 	... 14 more
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  853): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 187676, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  853): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  853): mCursor = null
,W/ProcessCpuTracker(  853): Skipping unknown process pid 8565
,W/ProcessCpuTracker(  853): Skipping unknown process pid 8568
,E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,I/PowerManagerService(  853): [PWL] Off : 50s ago
,D/SSRM:m  (  853): SIOP:: AP = 300, PST = 333, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  853): waitForAlarm result :4
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 6
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6629): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6629): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6629): [1] 5.onFinished: Giving up after 6 failures.
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 300, PST = 322, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 300, PST = 315, CUR = 300
,V/AlarmManager(  853): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  320): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  320): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/AlarmManager(  853): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  853): stay LED for fully charged
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  853): [PWL] Off : 75s ago
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 300, PST = 311, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/Watchdog(  853): !@Sync 7
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 307, CUR = 300
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 303, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :4
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  853): [PWL] Off : 105s ago
,I/PowerManagerService(  853): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  853): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  853): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=853, ws=WorkSource{10082}) (elapsedTime=55)
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7500): Starting books sync, d
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,I/PhoneStatusBar( 1171): Icon Only
,E/BooksAccountManager( 7500): Authentication error
E/BooksAccountManager( 7500): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7500): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/HttpHelper( 7500): null auth token
,I/qtaguid ( 7500): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7500, getuid(): 10082
,I/qtaguid ( 7500): Untagging socket 34
,W/ApiaryClient( 7500): Error response from books API: {
W/ApiaryClient( 7500):  "error": {
W/ApiaryClient( 7500):   "errors": [
W/ApiaryClient( 7500):    {
W/ApiaryClient( 7500):     "domain": "global",
W/ApiaryClient( 7500):     "reason": "required",
W/ApiaryClient( 7500):     "message": "Login Required",
W/ApiaryClient( 7500):     "locationType": "header",
W/ApiaryClient( 7500):     "location": "Authorization"
W/ApiaryClient( 7500):    }
W/ApiaryClient( 7500):   ],
W/ApiaryClient( 7500):   "code": 401,
W/ApiaryClient( 7500):   "message": "Login Required"
W/ApiaryClient( 7500):  }
W/ApiaryClient( 7500): }
,W/ApiaryClient( 7500): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2201576253335759042&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7500): Headers suppressed
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7500): Authentication error
E/BooksAccountManager( 7500): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7500): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7500): null auth token
,I/qtaguid ( 7500): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7500, getuid(): 10082
,I/qtaguid ( 7500): Untagging socket 34
,W/ApiaryClient( 7500): Error response from books API: {
W/ApiaryClient( 7500):  "error": {
W/ApiaryClient( 7500):   "errors": [
W/ApiaryClient( 7500):    {
W/ApiaryClient( 7500):     "domain": "global",
W/ApiaryClient( 7500):     "reason": "required",
W/ApiaryClient( 7500):     "message": "Login Required",
W/ApiaryClient( 7500):     "locationType": "header",
W/ApiaryClient( 7500):     "location": "Authorization"
W/ApiaryClient( 7500):    }
W/ApiaryClient( 7500):   ],
W/ApiaryClient( 7500):   "code": 401,
W/ApiaryClient( 7500):   "message": "Login Required"
W/ApiaryClient( 7500):  }
W/ApiaryClient( 7500): }
,W/ApiaryClient( 7500): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2201576253335759042&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7500): Headers suppressed
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7500): Authentication error
E/BooksAccountManager( 7500): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7500): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7500): null auth token
,I/qtaguid ( 7500): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7500, getuid(): 10082
,E/SMD     (  282): DCD ON
,I/qtaguid ( 7500): Untagging socket 34
,W/ApiaryClient( 7500): Error response from books API: {
W/ApiaryClient( 7500):  "error": {
W/ApiaryClient( 7500):   "errors": [
W/ApiaryClient( 7500):    {
W/ApiaryClient( 7500):     "domain": "global",
W/ApiaryClient( 7500):     "reason": "required",
W/ApiaryClient( 7500):     "message": "Login Required",
W/ApiaryClient( 7500):     "locationType": "header",
W/ApiaryClient( 7500):     "location": "Authorization"
W/ApiaryClient( 7500):    }
W/ApiaryClient( 7500):   ],
W/ApiaryClient( 7500):   "code": 401,
W/ApiaryClient( 7500):   "message": "Login Required"
W/ApiaryClient( 7500):  }
W/ApiaryClient( 7500): }
,W/ApiaryClient( 7500): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2201576253335759042&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7500): Headers suppressed
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/BooksSync( 7500): Soft error
E/BooksSync( 7500): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2201576253335759042&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7500): Headers suppressed
E/BooksSync( 7500): 
E/BooksSync( 7500): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7500): Sync error
E/BooksSync( 7500): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2201576253335759042&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7500): Headers suppressed
E/BooksSync( 7500): 
E/BooksSync( 7500): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7500): Finished books sync
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/SyncManager(  853): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 221348, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  853): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  853): mCursor = null
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 300, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 8
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 298, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/AlarmManager(  853): waitForAlarm result :8
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 296, CUR = 300
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  853): stay LED for fully charged
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
D/SecContentProvider2(  853): mCursor = null
,D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6595): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6595): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6595): 	at kfv.a(PG:65)
E/HttpOperation( 6595): 	at kff.u(PG:385)
E/HttpOperation( 6595): 	at kfb.a(PG:29)
E/HttpOperation( 6595): 	at kff.l(PG:132)
E/HttpOperation( 6595): 	at dsf.a(PG:807)
E/HttpOperation( 6595): 	at fhk.a(PG:1126)
E/HttpOperation( 6595): 	at fhk.a(PG:908)
E/HttpOperation( 6595): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6595): 	at ihi.a(PG:22)
E/HttpOperation( 6595): 	at kft.a(PG:91)
E/HttpOperation( 6595): 	at kfv.a(PG:62)
E/HttpOperation( 6595): 	... 8 more
E/HttpOperation( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6595): 	at gde.c(Unknown Source)
E/HttpOperation( 6595): 	at gde.b(Unknown Source)
E/HttpOperation( 6595): 	at ihi.a(PG:19)
E/HttpOperation( 6595): 	... 10 more
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1677): Explicit concurrent mark sweep GC freed 61294(3MB) AllocSpace objects, 76(5MB) LOS objects, 40% free, 18MB/30MB, paused 751us total 62.604ms
,E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,D/ResourcesManager( 1677): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 6595): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6595): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6595): 	at kfv.a(PG:65)
E/HttpOperation( 6595): 	at kff.u(PG:385)
E/HttpOperation( 6595): 	at kfb.a(PG:29)
E/HttpOperation( 6595): 	at kff.l(PG:132)
E/HttpOperation( 6595): 	at ieo.a(PG:43)
E/HttpOperation( 6595): 	at iep.a(PG:93)
E/HttpOperation( 6595): 	at fhn.a(PG:59)
E/HttpOperation( 6595): 	at lex.a(PG:85)
E/HttpOperation( 6595): 	at lex.b(PG:132)
E/HttpOperation( 6595): 	at fhk.a(PG:1146)
E/HttpOperation( 6595): 	at fhk.a(PG:908)
E/HttpOperation( 6595): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6595): 	at ihi.a(PG:22)
E/HttpOperation( 6595): 	at kft.a(PG:91)
E/HttpOperation( 6595): 	at kfv.a(PG:62)
E/HttpOperation( 6595): 	... 12 more
E/HttpOperation( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6595): 	at gde.c(Unknown Source)
E/HttpOperation( 6595): 	at gde.b(Unknown Source)
E/HttpOperation( 6595): 	at ihi.a(PG:19)
E/HttpOperation( 6595): 	... 14 more
,E/ExperimentLoader( 6595): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6595): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6595): 	at kfv.a(PG:65)
E/ExperimentLoader( 6595): 	at kff.u(PG:385)
E/ExperimentLoader( 6595): 	at kfb.a(PG:29)
E/ExperimentLoader( 6595): 	at kff.l(PG:132)
E/ExperimentLoader( 6595): 	at ieo.a(PG:43)
E/ExperimentLoader( 6595): 	at iep.a(PG:93)
E/ExperimentLoader( 6595): 	at fhn.a(PG:59)
E/ExperimentLoader( 6595): 	at lex.a(PG:85)
E/ExperimentLoader( 6595): 	at lex.b(PG:132)
E/ExperimentLoader( 6595): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6595): 	at fhk.a(PG:908)
E/ExperimentLoader( 6595): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6595): 	at ihi.a(PG:22)
E/ExperimentLoader( 6595): 	at kft.a(PG:91)
E/ExperimentLoader( 6595): 	at kfv.a(PG:62)
E/ExperimentLoader( 6595): 	... 12 more
E/ExperimentLoader( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6595): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6595): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6595): 	at ihi.a(PG:19)
E/ExperimentLoader( 6595): 	... 14 more
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  853): uri = 14 selection = getSealedState
D/SecContentProvider2(  853): mCursor = null
D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
E/HttpOperation( 6595): [getaccountstatus] Unexpected exception
E/HttpOperation( 6595): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6595): 	at kfv.a(PG:65)
E/HttpOperation( 6595): 	at kff.u(PG:385)
E/HttpOperation( 6595): 	at kfb.a(PG:29)
E/HttpOperation( 6595): 	at ixd.a(PG:248)
E/HttpOperation( 6595): 	at ixd.b(PG:206)
E/HttpOperation( 6595): 	at ixd.a(PG:175)
E/HttpOperation( 6595): 	at fig.a(PG:78)
E/HttpOperation( 6595): 	at lex.a(PG:85)
E/HttpOperation( 6595): 	at lex.b(PG:132)
E/HttpOperation( 6595): 	at fhk.a(PG:1146)
E/HttpOperation( 6595): 	at fhk.a(PG:908)
E/HttpOperation( 6595): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6595): 	at ihi.a(PG:22)
E/HttpOperation( 6595): 	at kft.a(PG:91)
E/HttpOperation( 6595): 	at kfv.a(PG:62)
E/HttpOperation( 6595): 	... 12 more
E/HttpOperation( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6595): 	at gde.c(Unknown Source)
E/HttpOperation( 6595): 	at gde.b(Unknown Source)
E/HttpOperation( 6595): 	at ihi.a(PG:19)
E/HttpOperation( 6595): 	... 14 more
E/EsSyncAdapterService( 6595): Sync failure
E/EsSyncAdapterService( 6595): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6595): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6595): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6595): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6595): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6595): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6595): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6595): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6595): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6595): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6595): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6595): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6595): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6595): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6595): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6595): 	... 10 more
E/EsSyncAdapterService( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6595): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6595): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6595): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6595): 	... 12 more
E/EsSyncAdapterService( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6595): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6595): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6595): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6595): 	... 14 more
D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  853): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 253920, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  853): Explicit concurrent mark sweep GC freed 44265(2MB) AllocSpace objects, 40(1225KB) LOS objects, 30% free, 36MB/52MB, paused 1.301ms total 86.120ms
,D/SecContentProvider2(  853): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  853): mCursor = null
,E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  853): [PWL] Off : 140s ago
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 294, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 9
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,D/BatteryService(  853): stay LED for fully charged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 293, CUR = 300
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 292, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :4
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  282): DCD ON
,D/TimaService(  853): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  853): TimaServiceHandler.handleMessage what =1
,D/TimaService(  853): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  853): initializing...
,I/TLC_TIMA_PKM_initialize(  853): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  853): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  853): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  853): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  853): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  853): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  853): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  853): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  853): App is not loaded in QSEE
,D/QSEECOMAPI: (  853): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  853): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  853): Trustlet response is completed
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  853): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  853): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  853): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  853): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  853): [PWL] Off : 180s ago
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,I/Atfwd_Sendcmd(  320): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  320): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :8
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  853): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): stay LED for fully charged
,E/Zygote  ( 8634): MountEmulatedStorage()
,I/ActivityManager(  853): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8634 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 8634): v2
,I/libpersona( 8634): KNOX_SDCARD checking this for 10081
I/libpersona( 8634): KNOX_SDCARD not a persona
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
I/MotionRecognitionService(  853): setPowerConnected  = true
,I/SELinux ( 8634): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8634): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8634): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaKeyStoreProvider( 8634): TimaSignature is unavailable
,D/ActivityThread( 8634): Added TimaKeyStore provider
,D/ResourcesManager( 8634): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ActivityManager(  853): Killing 5724:com.android.mms/u0a50 (adj 15): bgCount ##41
,D/CountryDetector(  853): No listener is left
,W/libprocessgroup(  853): failed to open /acct/uid_10050/pid_5724/cgroup.procs: No such file or directory
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :4
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7500): Starting books sync, d
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1677): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
,D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7500): Authentication error
E/BooksAccountManager( 7500): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7500): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7500): null auth token
,I/qtaguid ( 7500): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7500, getuid(): 10082
,I/qtaguid ( 7500): Untagging socket 34
,W/ApiaryClient( 7500): Error response from books API: {
W/ApiaryClient( 7500):  "error": {
W/ApiaryClient( 7500):   "errors": [
W/ApiaryClient( 7500):    {
W/ApiaryClient( 7500):     "domain": "global",
W/ApiaryClient( 7500):     "reason": "required",
W/ApiaryClient( 7500):     "message": "Login Required",
W/ApiaryClient( 7500):     "locationType": "header",
W/ApiaryClient( 7500):     "location": "Authorization"
W/ApiaryClient( 7500):    }
W/ApiaryClient( 7500):   ],
W/ApiaryClient( 7500):   "code": 401,
W/ApiaryClient( 7500):   "message": "Login Required"
W/ApiaryClient( 7500):  }
W/ApiaryClient( 7500): }
,W/ApiaryClient( 7500): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2146017221932764683&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7500): Headers suppressed
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7500): Authentication error
E/BooksAccountManager( 7500): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7500): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7500): null auth token
,I/qtaguid ( 7500): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7500, getuid(): 10082
,I/qtaguid ( 7500): Untagging socket 34
,W/ApiaryClient( 7500): Error response from books API: {
W/ApiaryClient( 7500):  "error": {
W/ApiaryClient( 7500):   "errors": [
W/ApiaryClient( 7500):    {
W/ApiaryClient( 7500):     "domain": "global",
W/ApiaryClient( 7500):     "reason": "required",
W/ApiaryClient( 7500):     "message": "Login Required",
W/ApiaryClient( 7500):     "locationType": "header",
W/ApiaryClient( 7500):     "location": "Authorization"
W/ApiaryClient( 7500):    }
W/ApiaryClient( 7500):   ],
W/ApiaryClient( 7500):   "code": 401,
W/ApiaryClient( 7500):   "message": "Login Required"
W/ApiaryClient( 7500):  }
W/ApiaryClient( 7500): }
,W/ApiaryClient( 7500): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2146017221932764683&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7500): Headers suppressed
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7500): Authentication error
E/BooksAccountManager( 7500): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7500): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7500): null auth token
,I/qtaguid ( 7500): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7500, getuid(): 10082
,I/qtaguid ( 7500): Untagging socket 34
,W/ApiaryClient( 7500): Error response from books API: {
W/ApiaryClient( 7500):  "error": {
W/ApiaryClient( 7500):   "errors": [
W/ApiaryClient( 7500):    {
W/ApiaryClient( 7500):     "domain": "global",
W/ApiaryClient( 7500):     "reason": "required",
W/ApiaryClient( 7500):     "message": "Login Required",
W/ApiaryClient( 7500):     "locationType": "header",
W/ApiaryClient( 7500):     "location": "Authorization"
W/ApiaryClient( 7500):    }
W/ApiaryClient( 7500):   ],
W/ApiaryClient( 7500):   "code": 401,
W/ApiaryClient( 7500):   "message": "Login Required"
W/ApiaryClient( 7500):  }
W/ApiaryClient( 7500): }
,W/ApiaryClient( 7500): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2146017221932764683&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7500): Headers suppressed
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/BooksSync( 7500): Soft error
E/BooksSync( 7500): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2146017221932764683&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7500): Headers suppressed
E/BooksSync( 7500): 
E/BooksSync( 7500): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7500): Sync error
E/BooksSync( 7500): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2146017221932764683&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7500): Headers suppressed
E/BooksSync( 7500): 
E/BooksSync( 7500): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7500): Finished books sync
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  853): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 314455, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2865): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 2865): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  853): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  853): mCursor = null
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 1
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,D/BatteryService(  853): stay LED for fully charged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 11
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1677): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_store.png
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6629): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6629): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6629): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6629): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6629): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6629): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6629): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 6629): Ignoring header User-Agent because its value was null.
,I/System.out( 6629): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6629): (HTTPLog)-Static: isShipBuild true
,I/System.out( 6629): (HTTPLog)-Thread-1078-725457095: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/PowerManagerService(  853): [PWL] Off : 225s ago
,V/AlarmManager(  853): waitForAlarm result :4
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 12
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,D/BatteryService(  853): stay LED for fully charged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :8
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 13
,V/AlarmManager(  853): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  853): stay LED for fully charged
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
I/MotionRecognitionService(  853): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
D/SecContentProvider2(  853): mCursor = null
,D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0,
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6595): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6595): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6595): 	at kfv.a(PG:65)
E/HttpOperation( 6595): 	at kff.u(PG:385)
E/HttpOperation( 6595): 	at kfb.a(PG:29)
E/HttpOperation( 6595): 	at kff.l(PG:132)
E/HttpOperation( 6595): 	at dsf.a(PG:807)
E/HttpOperation( 6595): 	at fhk.a(PG:1126)
E/HttpOperation( 6595): 	at fhk.a(PG:908)
E/HttpOperation( 6595): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6595): 	at ihi.a(PG:22)
E/HttpOperation( 6595): 	at kft.a(PG:91)
E/HttpOperation( 6595): 	at kfv.a(PG:62)
E/HttpOperation( 6595): 	... 8 more
E/HttpOperation( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6595): 	at gde.c(Unknown Source)
E/HttpOperation( 6595): 	at gde.b(Unknown Source)
E/HttpOperation( 6595): 	at ihi.a(PG:19)
E/HttpOperation( 6595): 	... 10 more
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
D/SecContentProvider2(  853): mCursor = null
,D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0,
V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6595): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6595): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6595): 	at kfv.a(PG:65)
E/HttpOperation( 6595): 	at kff.u(PG:385)
E/HttpOperation( 6595): 	at kfb.a(PG:29)
E/HttpOperation( 6595): 	at kff.l(PG:132)
E/HttpOperation( 6595): 	at ieo.a(PG:43)
E/HttpOperation( 6595): 	at iep.a(PG:93)
E/HttpOperation( 6595): 	at fhn.a(PG:59)
E/HttpOperation( 6595): 	at lex.a(PG:85)
E/HttpOperation( 6595): 	at lex.b(PG:132)
E/HttpOperation( 6595): 	at fhk.a(PG:1146)
E/HttpOperation( 6595): 	at fhk.a(PG:908)
E/HttpOperation( 6595): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6595): 	at ihi.a(PG:22)
E/HttpOperation( 6595): 	at kft.a(PG:91)
E/HttpOperation( 6595): 	at kfv.a(PG:62)
E/HttpOperation( 6595): 	... 12 more
E/HttpOperation( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6595): 	at gde.c(Unknown Source)
E/HttpOperation( 6595): 	at gde.b(Unknown Source)
E/HttpOperation( 6595): 	at ihi.a(PG:19)
E/HttpOperation( 6595): 	... 14 more
E/ExperimentLoader( 6595): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6595): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6595): 	at kfv.a(PG:65)
E/ExperimentLoader( 6595): 	at kff.u(PG:385)
E/ExperimentLoader( 6595): 	at kfb.a(PG:29)
E/ExperimentLoader( 6595): 	at kff.l(PG:132)
E/ExperimentLoader( 6595): 	at ieo.a(PG:43)
E/ExperimentLoader( 6595): 	at iep.a(PG:93)
E/ExperimentLoader( 6595): 	at fhn.a(PG:59)
E/ExperimentLoader( 6595): 	at lex.a(PG:85)
E/ExperimentLoader( 6595): 	at lex.b(PG:132)
E/ExperimentLoader( 6595): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6595): 	at fhk.a(PG:908)
E/ExperimentLoader( 6595): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6595): 	at ihi.a(PG:22)
E/ExperimentLoader( 6595): 	at kft.a(PG:91)
E/ExperimentLoader( 6595): 	at kfv.a(PG:62)
E/ExperimentLoader( 6595): 	... 12 more
E/ExperimentLoader( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6595): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6595): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6595): 	at ihi.a(PG:19)
E/ExperimentLoader( 6595): 	... 14 more
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
D/SecContentProvider2(  853): mCursor = null
,D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6595): [getaccountstatus] Unexpected exception
E/HttpOperation( 6595): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6595): 	at kfv.a(PG:65)
E/HttpOperation( 6595): 	at kff.u(PG:385)
E/HttpOperation( 6595): 	at kfb.a(PG:29)
E/HttpOperation( 6595): 	at ixd.a(PG:248)
E/HttpOperation( 6595): 	at ixd.b(PG:206)
E/HttpOperation( 6595): 	at ixd.a(PG:175)
E/HttpOperation( 6595): 	at fig.a(PG:78)
E/HttpOperation( 6595): 	at lex.a(PG:85)
E/HttpOperation( 6595): 	at lex.b(PG:132)
E/HttpOperation( 6595): 	at fhk.a(PG:1146)
E/HttpOperation( 6595): 	at fhk.a(PG:908)
E/HttpOperation( 6595): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6595): 	at ihi.a(PG:22)
E/HttpOperation( 6595): 	at kft.a(PG:91)
E/HttpOperation( 6595): 	at kfv.a(PG:62)
E/HttpOperation( 6595): 	... 12 more
E/HttpOperation( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6595): 	at gde.c(Unknown Source)
E/HttpOperation( 6595): 	at gde.b(Unknown Source)
E/HttpOperation( 6595): 	at ihi.a(PG:19)
E/HttpOperation( 6595): 	... 14 more
,E/EsSyncAdapterService( 6595): Sync failure
E/EsSyncAdapterService( 6595): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6595): 	at ixd.a(PG:348),
E/EsSyncAdapterService( 6595): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6595): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6595): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6595): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6595): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6595): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6595): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6595): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6595): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6595): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6595): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6595): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6595): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6595): 	... 10 more
E/EsSyncAdapterService( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6595): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6595): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6595): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6595): 	... 12 more
E/EsSyncAdapterService( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6595): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6595): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6595): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6595): 	... 14 more
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,D/SyncManager(  853): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 405320, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  853): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  853): mCursor = null
,E/SMD     (  282): DCD ON
,E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 5
,I/PowerManagerService(  853): [PWL] Off : 275s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,D/BatteryService(  853): stay LED for fully charged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 14
,V/AlarmManager(  853): waitForAlarm result :4
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/Atfwd_Sendcmd(  320): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  320): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :8
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 15
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/PowerManagerService(  853): [PWL] Off : 330s ago
,V/AlarmManager(  853): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  853): stay LED for fully charged
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7500): Starting books sync, d
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
D/SecContentProvider2(  853): mCursor = null
D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7500): Authentication error
E/BooksAccountManager( 7500): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7500): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7500): null auth token
,I/qtaguid ( 7500): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7500, getuid(): 10082
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/qtaguid ( 7500): Untagging socket 34
,W/ApiaryClient( 7500): Error response from books API: {
W/ApiaryClient( 7500):  "error": {
W/ApiaryClient( 7500):   "errors": [
W/ApiaryClient( 7500):    {
W/ApiaryClient( 7500):     "domain": "global",
W/ApiaryClient( 7500):     "reason": "required",
W/ApiaryClient( 7500):     "message": "Login Required",
W/ApiaryClient( 7500):     "locationType": "header",
W/ApiaryClient( 7500):     "location": "Authorization"
W/ApiaryClient( 7500):    }
W/ApiaryClient( 7500):   ],
W/ApiaryClient( 7500):   "code": 401,
W/ApiaryClient( 7500):   "message": "Login Required"
W/ApiaryClient( 7500):  }
W/ApiaryClient( 7500): }
,W/ApiaryClient( 7500): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2521089476403542390&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7500): Headers suppressed
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
,D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7500): Authentication error
E/BooksAccountManager( 7500): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7500): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7500): null auth token
,I/qtaguid ( 7500): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7500, getuid(): 10082
,I/qtaguid ( 7500): Untagging socket 34
,W/ApiaryClient( 7500): Error response from books API: {
W/ApiaryClient( 7500):  "error": {
W/ApiaryClient( 7500):   "errors": [
W/ApiaryClient( 7500):    {
W/ApiaryClient( 7500):     "domain": "global",
W/ApiaryClient( 7500):     "reason": "required",
W/ApiaryClient( 7500):     "message": "Login Required",
W/ApiaryClient( 7500):     "locationType": "header",
W/ApiaryClient( 7500):     "location": "Authorization"
W/ApiaryClient( 7500):    }
W/ApiaryClient( 7500):   ],
W/ApiaryClient( 7500):   "code": 401,
W/ApiaryClient( 7500):   "message": "Login Required"
W/ApiaryClient( 7500):  }
W/ApiaryClient( 7500): }
,W/ApiaryClient( 7500): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2521089476403542390&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7500): Headers suppressed
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7500): Authentication error
E/BooksAccountManager( 7500): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7500): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7500): null auth token
,I/qtaguid ( 7500): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7500, getuid(): 10082
,I/qtaguid ( 7500): Untagging socket 34
,W/ApiaryClient( 7500): Error response from books API: {
W/ApiaryClient( 7500):  "error": {
W/ApiaryClient( 7500):   "errors": [
W/ApiaryClient( 7500):    {
W/ApiaryClient( 7500):     "domain": "global",
W/ApiaryClient( 7500):     "reason": "required",
W/ApiaryClient( 7500):     "message": "Login Required",
W/ApiaryClient( 7500):     "locationType": "header",
W/ApiaryClient( 7500):     "location": "Authorization"
W/ApiaryClient( 7500):    }
W/ApiaryClient( 7500):   ],
W/ApiaryClient( 7500):   "code": 401,
W/ApiaryClient( 7500):   "message": "Login Required"
W/ApiaryClient( 7500):  }
W/ApiaryClient( 7500): }
,W/ApiaryClient( 7500): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2521089476403542390&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7500): Headers suppressed
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7500): Soft error
E/BooksSync( 7500): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2521089476403542390&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7500): Headers suppressed
E/BooksSync( 7500): 
E/BooksSync( 7500): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7500): Sync error
E/BooksSync( 7500): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2521089476403542390&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7500): Headers suppressed
E/BooksSync( 7500): 
E/BooksSync( 7500): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7500): Finished books sync
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  853): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 470463, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  853): Explicit concurrent mark sweep GC freed 55415(3MB) AllocSpace objects, 73(1818KB) LOS objects, 30% free, 36MB/52MB, paused 1.623ms total 123.852ms
,D/SecContentProvider2(  853): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  853): mCursor = null
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/bootchecker(  315): bootchecker wake up!!
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 16
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :4
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :8
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 17
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/PowerManagerService(  853): [PWL] Off : 390s ago
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 280, PST = 289, CUR = 300
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 18
,E/SMD     (  282): DCD ON
,I/Atfwd_Sendcmd(  320): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  320): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 280, PST = 288, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/SSRM:m  (  853): SIOP:: AP = 280, PST = 287, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 285, CUR = 300
,I/Atfwd_Daemon(  320): Stop the daemon....
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 19
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 283, CUR = 300
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  853): [PWL] Off : 455s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 281, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/TimaService(  853): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  853): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  853): TimaServiceHandler.handleMessage what =1
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 279, CUR = 300
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  853): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  853): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  853): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  853): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  853): stay LED for fully charged
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  853): SIOP:: AP = 290, PST = 279, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  853): SIOP:: AP = 280, PST = 278, CUR = 300
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,I/ActivityManager(  853): Killing 7417:com.sec.android.widgetapp.digitalclock/u0a94 (adj 15): bgCount ##41
,W/libprocessgroup(  853): failed to open /acct/uid_10094/pid_7417/cgroup.procs: No such file or directory
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 276, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 21
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 275, CUR = 300
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 274, CUR = 300
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  853): [PWL] Off : 525s ago
,V/AlarmManager(  853): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  853): stay LED for fully charged
D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6595): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6595): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6595): 	at kfv.a(PG:65)
E/HttpOperation( 6595): 	at kff.u(PG:385)
E/HttpOperation( 6595): 	at kfb.a(PG:29)
E/HttpOperation( 6595): 	at kff.l(PG:132)
E/HttpOperation( 6595): 	at dsf.a(PG:807)
E/HttpOperation( 6595): 	at fhk.a(PG:1126)
E/HttpOperation( 6595): 	at fhk.a(PG:908)
E/HttpOperation( 6595): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6595): 	at ihi.a(PG:22)
E/HttpOperation( 6595): 	at kft.a(PG:91)
E/HttpOperation( 6595): 	at kfv.a(PG:62)
E/HttpOperation( 6595): 	... 8 more
E/HttpOperation( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6595): 	at gde.c(Unknown Source)
E/HttpOperation( 6595): 	at gde.b(Unknown Source)
E/HttpOperation( 6595): 	at ihi.a(PG:19)
E/HttpOperation( 6595): 	... 10 more
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
D/SecContentProvider2(  853): mCursor = null
,D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6595): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6595): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6595): 	at kfv.a(PG:65)
E/HttpOperation( 6595): 	at kff.u(PG:385)
E/HttpOperation( 6595): 	at kfb.a(PG:29)
E/HttpOperation( 6595): 	at kff.l(PG:132)
E/HttpOperation( 6595): 	at ieo.a(PG:43)
E/HttpOperation( 6595): 	at iep.a(PG:93)
E/HttpOperation( 6595): 	at fhn.a(PG:59)
E/HttpOperation( 6595): 	at lex.a(PG:85)
E/HttpOperation( 6595): 	at lex.b(PG:132)
E/HttpOperation( 6595): 	at fhk.a(PG:1146)
E/HttpOperation( 6595): 	at fhk.a(PG:908)
E/HttpOperation( 6595): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6595): 	at ihi.a(PG:22)
E/HttpOperation( 6595): 	at kft.a(PG:91)
E/HttpOperation( 6595): 	at kfv.a(PG:62)
E/HttpOperation( 6595): 	... 12 more
E/HttpOperation( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6595): 	at gde.c(Unknown Source)
E/HttpOperation( 6595): 	at gde.b(Unknown Source)
E/HttpOperation( 6595): 	at ihi.a(PG:19)
E/HttpOperation( 6595): 	... 14 more
,E/ExperimentLoader( 6595): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6595): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6595): 	at kfv.a(PG:65)
E/ExperimentLoader( 6595): 	at kff.u(PG:385)
E/ExperimentLoader( 6595): 	at kfb.a(PG:29)
E/ExperimentLoader( 6595): 	at kff.l(PG:132)
E/ExperimentLoader( 6595): 	at ieo.a(PG:43)
E/ExperimentLoader( 6595): 	at iep.a(PG:93)
E/ExperimentLoader( 6595): 	at fhn.a(PG:59)
E/ExperimentLoader( 6595): 	at lex.a(PG:85)
E/ExperimentLoader( 6595): 	at lex.b(PG:132)
E/ExperimentLoader( 6595): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6595): 	at fhk.a(PG:908)
E/ExperimentLoader( 6595): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6595): 	at ihi.a(PG:22)
E/ExperimentLoader( 6595): 	at kft.a(PG:91)
E/ExperimentLoader( 6595): 	at kfv.a(PG:62)
E/ExperimentLoader( 6595): 	... 12 more
E/ExperimentLoader( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6595): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6595): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6595): 	at ihi.a(PG:19)
E/ExperimentLoader( 6595): 	... 14 more
I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/art     ( 1677): Explicit concurrent mark sweep GC freed 39336(2MB) AllocSpace objects, 31(2MB) LOS objects, 39% free, 18MB/30MB, paused 1.194ms total 70.122ms
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,D/ResourcesManager( 1677): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
E/HttpOperation( 6595): [getaccountstatus] Unexpected exception
E/HttpOperation( 6595): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6595): 	at kfv.a(PG:65)
E/HttpOperation( 6595): 	at kff.u(PG:385)
E/HttpOperation( 6595): 	at kfb.a(PG:29)
E/HttpOperation( 6595): 	at ixd.a(PG:248)
E/HttpOperation( 6595): 	at ixd.b(PG:206)
E/HttpOperation( 6595): 	at ixd.a(PG:175)
E/HttpOperation( 6595): 	at fig.a(PG:78)
E/HttpOperation( 6595): 	at lex.a(PG:85)
E/HttpOperation( 6595): 	at lex.b(PG:132)
E/HttpOperation( 6595): 	at fhk.a(PG:1146)
E/HttpOperation( 6595): 	at fhk.a(PG:908)
E/HttpOperation( 6595): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6595): 	at ihi.a(PG:22)
E/HttpOperation( 6595): 	at kft.a(PG:91)
E/HttpOperation( 6595): 	at kfv.a(PG:62)
E/HttpOperation( 6595): 	... 12 more
E/HttpOperation( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6595): 	at gde.c(Unknown Source)
E/HttpOperation( 6595): 	at gde.b(Unknown Source)
E/HttpOperation( 6595): 	at ihi.a(PG:19)
E/HttpOperation( 6595): 	... 14 more
,E/EsSyncAdapterService( 6595): Sync failure
E/EsSyncAdapterService( 6595): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6595): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6595): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6595): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6595): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6595): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6595): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6595): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6595): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6595): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6595): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6595): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6595): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6595): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6595): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6595): 	... 10 more
E/EsSyncAdapterService( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6595): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6595): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6595): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6595): 	... 12 more
E/EsSyncAdapterService( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6595): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6595): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6595): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6595): 	... 14 more
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  853): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 665071, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  853): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  853): mCursor = null
,E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 273, CUR = 300
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 22
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  853): stay LED for fully charged
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 23
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): stay LED for fully charged
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 24
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :4
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7500): Starting books sync, d
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1677): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7500): Authentication error
E/BooksAccountManager( 7500): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7500): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7500): null auth token
,I/qtaguid ( 7500): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7500, getuid(): 10082
,I/qtaguid ( 7500): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7500, getuid(): 10082
,I/qtaguid ( 7500): Untagging socket 34
,W/ApiaryClient( 7500): Error response from books API: {
W/ApiaryClient( 7500):  "error": {
W/ApiaryClient( 7500):   "errors": [
W/ApiaryClient( 7500):    {
W/ApiaryClient( 7500):     "domain": "global",
W/ApiaryClient( 7500):     "reason": "required",
W/ApiaryClient( 7500):     "message": "Login Required",
W/ApiaryClient( 7500):     "locationType": "header",
W/ApiaryClient( 7500):     "location": "Authorization"
W/ApiaryClient( 7500):    }
W/ApiaryClient( 7500):   ],
W/ApiaryClient( 7500):   "code": 401,
W/ApiaryClient( 7500):   "message": "Login Required"
W/ApiaryClient( 7500):  }
W/ApiaryClient( 7500): }
,W/ApiaryClient( 7500): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=205339608863069476&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7500): Headers suppressed
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7500): Authentication error
E/BooksAccountManager( 7500): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7500): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7500): null auth token
,I/qtaguid ( 7500): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7500, getuid(): 10082
,I/qtaguid ( 7500): Tagging socket 40 with tag 10000000000{256,0} uid -1, pid: 7500, getuid(): 10082
,I/qtaguid ( 7500): Untagging socket 34
,W/ApiaryClient( 7500): Error response from books API: {
W/ApiaryClient( 7500):  "error": {
W/ApiaryClient( 7500):   "errors": [
W/ApiaryClient( 7500):    {
W/ApiaryClient( 7500):     "domain": "global",
W/ApiaryClient( 7500):     "reason": "required",
W/ApiaryClient( 7500):     "message": "Login Required",
W/ApiaryClient( 7500):     "locationType": "header",
W/ApiaryClient( 7500):     "location": "Authorization"
W/ApiaryClient( 7500):    }
W/ApiaryClient( 7500):   ],
W/ApiaryClient( 7500):   "code": 401,
W/ApiaryClient( 7500):   "message": "Login Required"
W/ApiaryClient( 7500):  }
W/ApiaryClient( 7500): }
,W/ApiaryClient( 7500): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=205339608863069476&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7500): Headers suppressed
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,I/PowerManagerService(  853): [PWL] Off : 600s ago
,I/PowerManagerService(  853): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  853): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  853): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=853, ws=WorkSource{10082}) (elapsedTime=2771)
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7500): Authentication error
E/BooksAccountManager( 7500): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7500): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7500): null auth token
,I/qtaguid ( 7500): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7500, getuid(): 10082
,I/qtaguid ( 7500): Untagging socket 34
,W/ApiaryClient( 7500): Error response from books API: {
W/ApiaryClient( 7500):  "error": {
W/ApiaryClient( 7500):   "errors": [
W/ApiaryClient( 7500):    {
W/ApiaryClient( 7500):     "domain": "global",
W/ApiaryClient( 7500):     "reason": "required",
W/ApiaryClient( 7500):     "message": "Login Required",
W/ApiaryClient( 7500):     "locationType": "header",
W/ApiaryClient( 7500):     "location": "Authorization"
W/ApiaryClient( 7500):    }
W/ApiaryClient( 7500):   ],
W/ApiaryClient( 7500):   "code": 401,
W/ApiaryClient( 7500):   "message": "Login Required"
W/ApiaryClient( 7500):  }
W/ApiaryClient( 7500): }
,W/ApiaryClient( 7500): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=205339608863069476&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7500): Headers suppressed
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7500): Soft error
E/BooksSync( 7500): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=205339608863069476&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7500): Headers suppressed
E/BooksSync( 7500): 
E/BooksSync( 7500): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7500): Sync error
E/BooksSync( 7500): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=205339608863069476&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7500): Headers suppressed
E/BooksSync( 7500): 
E/BooksSync( 7500): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7500): Finished books sync
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  853): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 737147, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  853): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  853): mCursor = null
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 25
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  853): stay LED for fully charged
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 26
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,D/BatteryService(  853): stay LED for fully charged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,E/SMD     (  282): DCD ON
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  853): [PWL] Off : 680s ago
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 27
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,D/BatteryService(  853): stay LED for fully charged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 269, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 28
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 268, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 267, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  853): stay LED for fully charged
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON,
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 266, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 29
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 265, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 264, CUR = 300
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  853): [PWL] Off : 765s ago
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/TimaService(  853): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  853): TimaServiceHandler.handleMessage what =1
,D/TimaService(  853): TIMA: checkEvent, operation: 50000 subject: 10000
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 264, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel(  853): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  853): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  853): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  853): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 264, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 264, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 263, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 31
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 263, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 263, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 263, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 32
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,D/BatteryService(  853): stay LED for fully charged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 263, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 263, CUR = 300
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  853): [PWL] Off : 855s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 33
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 263, CUR = 300
,V/AlarmManager(  853): waitForAlarm result :4
,D/LightsService(  853): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  853): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  853): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  853): stay LED for fully charged
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/GCM     ( 1677): Message class com.google.f.a.a.i
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/EventLogService( 2437): Aggregate from 1452859283128 (log), 1452859283128 (data)
,D/LightsService(  853): [SvcLED]  onSensorChanged::light value = 19
,E/LightSensor(  853): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  853): unregisterListener ::   
,D/LightsService(  853): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,E/SMD     (  282): DCD ON,
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 262, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 34
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 35
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  853): [PWL] Off : 950s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 36
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,D/BatteryService(  853): stay LED for fully charged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true,
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 37
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 38
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  853): !@Sync 39
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
D/SecContentProvider2(  853): mCursor = null
D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/HttpOperation( 6595): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6595): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6595): 	at kfv.a(PG:65)
E/HttpOperation( 6595): 	at kff.u(PG:385)
E/HttpOperation( 6595): 	at kfb.a(PG:29)
E/HttpOperation( 6595): 	at kff.l(PG:132)
E/HttpOperation( 6595): 	at dsf.a(PG:807)
E/HttpOperation( 6595): 	at fhk.a(PG:1126)
E/HttpOperation( 6595): 	at fhk.a(PG:908)
E/HttpOperation( 6595): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6595): 	at ihi.a(PG:22)
E/HttpOperation( 6595): 	at kft.a(PG:91)
E/HttpOperation( 6595): 	at kfv.a(PG:62)
E/HttpOperation( 6595): 	... 8 more
E/HttpOperation( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6595): 	at gde.c(Unknown Source)
E/HttpOperation( 6595): 	at gde.b(Unknown Source)
E/HttpOperation( 6595): 	at ihi.a(PG:19)
E/HttpOperation( 6595): 	... 10 more
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
D/SecContentProvider2(  853): mCursor = null
D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 6595): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 6595): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6595): 	at kfv.a(PG:65)
E/HttpOperation( 6595): 	at kff.u(PG:385)
E/HttpOperation( 6595): 	at kfb.a(PG:29)
E/HttpOperation( 6595): 	at kff.l(PG:132)
E/HttpOperation( 6595): 	at ieo.a(PG:43)
E/HttpOperation( 6595): 	at iep.a(PG:93)
E/HttpOperation( 6595): 	at fhn.a(PG:59)
E/HttpOperation( 6595): 	at lex.a(PG:85)
E/HttpOperation( 6595): 	at lex.b(PG:132)
E/HttpOperation( 6595): 	at fhk.a(PG:1146)
E/HttpOperation( 6595): 	at fhk.a(PG:908)
E/HttpOperation( 6595): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6595): 	at ihi.a(PG:22)
E/HttpOperation( 6595): 	at kft.a(PG:91)
E/HttpOperation( 6595): 	at kfv.a(PG:62)
E/HttpOperation( 6595): 	... 12 more
E/HttpOperation( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6595): 	at gde.c(Unknown Source)
E/HttpOperation( 6595): 	at gde.b(Unknown Source)
E/HttpOperation( 6595): 	at ihi.a(PG:19)
E/HttpOperation( 6595): 	... 14 more
E/ExperimentLoader( 6595): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6595): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6595): 	at kfv.a(PG:65)
E/ExperimentLoader( 6595): 	at kff.u(PG:385)
E/ExperimentLoader( 6595): 	at kfb.a(PG:29)
E/ExperimentLoader( 6595): 	at kff.l(PG:132)
E/ExperimentLoader( 6595): 	at ieo.a(PG:43)
E/ExperimentLoader( 6595): 	at iep.a(PG:93)
E/ExperimentLoader( 6595): 	at fhn.a(PG:59)
E/ExperimentLoader( 6595): 	at lex.a(PG:85)
E/ExperimentLoader( 6595): 	at lex.b(PG:132)
E/ExperimentLoader( 6595): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6595): 	at fhk.a(PG:908)
E/ExperimentLoader( 6595): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6595): 	at ihi.a(PG:22)
E/ExperimentLoader( 6595): 	at kft.a(PG:91)
E/ExperimentLoader( 6595): 	at kfv.a(PG:62)
E/ExperimentLoader( 6595): 	... 12 more
E/ExperimentLoader( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6595): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6595): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6595): 	at ihi.a(PG:19)
E/ExperimentLoader( 6595): 	... 14 more
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
,D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6595): [getaccountstatus] Unexpected exception
E/HttpOperation( 6595): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6595): 	at kfv.a(PG:65)
E/HttpOperation( 6595): 	at kff.u(PG:385)
E/HttpOperation( 6595): 	at kfb.a(PG:29)
E/HttpOperation( 6595): 	at ixd.a(PG:248)
E/HttpOperation( 6595): 	at ixd.b(PG:206)
E/HttpOperation( 6595): 	at ixd.a(PG:175)
E/HttpOperation( 6595): 	at fig.a(PG:78)
E/HttpOperation( 6595): 	at lex.a(PG:85)
E/HttpOperation( 6595): 	at lex.b(PG:132)
E/HttpOperation( 6595): 	at fhk.a(PG:1146)
E/HttpOperation( 6595): 	at fhk.a(PG:908)
E/HttpOperation( 6595): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6595): 	at ihi.a(PG:22)
E/HttpOperation( 6595): 	at kft.a(PG:91)
E/HttpOperation( 6595): 	at kfv.a(PG:62)
E/HttpOperation( 6595): 	... 12 more
E/HttpOperation( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6595): 	at gde.c(Unknown Source)
E/HttpOperation( 6595): 	at gde.b(Unknown Source)
E/HttpOperation( 6595): 	at ihi.a(PG:19)
E/HttpOperation( 6595): 	... 14 more
E/EsSyncAdapterService( 6595): Sync failure
E/EsSyncAdapterService( 6595): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6595): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6595): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6595): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6595): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6595): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6595): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6595): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6595): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6595): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6595): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6595): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6595): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6595): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6595): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6595): 	... 10 more
E/EsSyncAdapterService( 6595): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6595): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6595): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6595): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6595): 	... 12 more
E/EsSyncAdapterService( 6595): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6595): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6595): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6595): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6595): 	... 14 more
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
D/SyncManager(  853): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1183216, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,I/art     (  853): Explicit concurrent mark sweep GC freed 78617(6MB) AllocSpace objects, 230(4MB) LOS objects, 30% free, 36MB/52MB, paused 6.122ms total 293.306ms
D/SecContentProvider2(  853): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  853): mCursor = null
,E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  853): [PWL] Off : 1050s ago
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/TimaService(  853): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  853): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  853): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  853): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  853): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  853): Updating Usage Statistics in DB @ 1452861521610
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
,W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
,W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
,W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
,W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
,W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
,W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
,W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
,W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
,W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
,W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
,W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
,W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
,W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
,W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
,W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
,W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
,W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
,W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
,W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
,W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
,W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
,W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
,W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  853): ::getAppControlDB: Exception to create DB
,W/System.err(  853): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  853): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  853): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  853): Done Updating Usage Statistics in DB @ 1452861521840
,E/Watchdog(  853): !@Sync 40
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :4
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  853): stay LED for fully charged
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel(  853): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  853): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  853): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  853): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  853): SIOP:: AP = 270, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 41
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,D/BatteryService(  853): stay LED for fully charged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 261, CUR = 300
,V/AlarmManager(  853): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7500): Starting books sync, d
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
D/SecContentProvider2(  853): mCursor = null
,D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7500): Authentication error
E/BooksAccountManager( 7500): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7500): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,E/HttpHelper( 7500): null auth token
,I/qtaguid ( 7500): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7500, getuid(): 10082
,I/qtaguid ( 7500): Untagging socket 34
,W/ApiaryClient( 7500): Error response from books API: {
W/ApiaryClient( 7500):  "error": {
W/ApiaryClient( 7500):   "errors": [
W/ApiaryClient( 7500):    {
W/ApiaryClient( 7500):     "domain": "global",
W/ApiaryClient( 7500):     "reason": "required",
W/ApiaryClient( 7500):     "message": "Login Required",
W/ApiaryClient( 7500):     "locationType": "header",
W/ApiaryClient( 7500):     "location": "Authorization"
W/ApiaryClient( 7500):    }
W/ApiaryClient( 7500):   ],
W/ApiaryClient( 7500):   "code": 401,
W/ApiaryClient( 7500):   "message": "Login Required"
W/ApiaryClient( 7500):  }
W/ApiaryClient( 7500): }
,W/ApiaryClient( 7500): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8221359462084447612&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7500): Headers suppressed
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7500): Authentication error
E/BooksAccountManager( 7500): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7500): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7500): null auth token
,I/qtaguid ( 7500): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7500, getuid(): 10082
,I/qtaguid ( 7500): Tagging socket 41 with tag 10000000000{256,0} uid -1, pid: 7500, getuid(): 10082
,I/qtaguid ( 7500): Untagging socket 34
,W/ApiaryClient( 7500): Error response from books API: {
W/ApiaryClient( 7500):  "error": {
W/ApiaryClient( 7500):   "errors": [
W/ApiaryClient( 7500):    {
W/ApiaryClient( 7500):     "domain": "global",
W/ApiaryClient( 7500):     "reason": "required",
W/ApiaryClient( 7500):     "message": "Login Required",
W/ApiaryClient( 7500):     "locationType": "header",
W/ApiaryClient( 7500):     "location": "Authorization"
W/ApiaryClient( 7500):    }
W/ApiaryClient( 7500):   ],
W/ApiaryClient( 7500):   "code": 401,
W/ApiaryClient( 7500):   "message": "Login Required"
W/ApiaryClient( 7500):  }
W/ApiaryClient( 7500): }
,W/ApiaryClient( 7500): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8221359462084447612&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7500): Headers suppressed
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1677): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png,
,D/SecContentProvider2(  853): uri = 14 selection = getSealedState
,D/SecContentProvider2(  853): mCursor = null
D/SecContentProvider2(  853): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  853): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  853): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1677): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1677): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1677): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1677): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1677): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7500): Authentication error
E/BooksAccountManager( 7500): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7500): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7500): null auth token
,I/qtaguid ( 7500): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7500, getuid(): 10082
,I/qtaguid ( 7500): Untagging socket 34
,W/ApiaryClient( 7500): Error response from books API: {
W/ApiaryClient( 7500):  "error": {
W/ApiaryClient( 7500):   "errors": [
W/ApiaryClient( 7500):    {
W/ApiaryClient( 7500):     "domain": "global",
W/ApiaryClient( 7500):     "reason": "required",
W/ApiaryClient( 7500):     "message": "Login Required",
W/ApiaryClient( 7500):     "locationType": "header",
W/ApiaryClient( 7500):     "location": "Authorization"
W/ApiaryClient( 7500):    }
W/ApiaryClient( 7500):   ],
W/ApiaryClient( 7500):   "code": 401,
W/ApiaryClient( 7500):   "message": "Login Required"
W/ApiaryClient( 7500):  }
W/ApiaryClient( 7500): }
,W/ApiaryClient( 7500): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8221359462084447612&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7500): Headers suppressed
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,E/BooksSync( 7500): Soft error
E/BooksSync( 7500): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8221359462084447612&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7500): Headers suppressed
E/BooksSync( 7500): 
E/BooksSync( 7500): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7500): Sync error
E/BooksSync( 7500): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7500): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8221359462084447612&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7500): Headers suppressed
E/BooksSync( 7500): 
E/BooksSync( 7500): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7500): Finished books sync
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  853): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1266487, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  853): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  853): mCursor = null
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  853): !@Sync 42
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  853): stay LED for fully charged
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  853): [PWL] Off : 1155s ago
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 261, CUR = 300
,V/AlarmManager(  853): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  853): stay LED for fully charged
D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
I/MotionRecognitionService(  853): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 43
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 44
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 45
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 46
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  853): [PWL] Off : 1265s ago
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 47
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 48
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 49
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/TimaService(  853): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  853): TimaServiceHandler.handleMessage what =1
,D/TimaService(  853): TIMA: checkEvent, operation: 50000 subject: 10000
,E/Watchdog(  853): !@Sync 50
,E/SMD     (  282): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  853): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  853): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  853): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  853): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  853): [PWL] Off : 1380s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 51
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  853): stay LED for fully charged
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  853): !@Sync 52
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 53
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  853): stay LED for fully charged
D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SettingsProvider(  853): name = SPD_REGISTERD
,W/ContextImpl( 7877): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 android.content.ContextWrapper.sendBroadcast:391 com.policydm.XDMBroadcastReceiver.sendRegisterIntent:458 com.policydm.XDMBroadcastReceiver.processEULAAgreement:447 com.policydm.XDMBroadcastReceiver.xdmExecResumeCase:367 
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ActivityThread( 7877): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/System.out( 7877): Thread-1287(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7877): Thread-1287(ApacheHTTPLog):isShipBuild true
,I/System.out( 7877): Thread-1287(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 7877): Thread-1287 calls detatch()
,V/AlarmManager(  853): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 54
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  853): [PWL] Off : 1500s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :8
,D/LightsService(  853): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  853): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  853): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/LightsService(  853): [SvcLED]  onSensorChanged::light value = 18
,E/LightSensor(  853): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  853): unregisterListener ::   
,D/LightsService(  853): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 55
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,D/BatteryService(  853): stay LED for fully charged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  853): !@Sync 56
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 57
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,E/Watchdog(  853): !@Sync 58
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  853): [PWL] Off : 1625s ago
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 59
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED,
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/NetworkStatsFactory(  853): UpdateStatsForKnox
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/TimaService(  853): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  853): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  853): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  853): !@Sync 60
,E/SMD     (  282): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  853): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  853): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  853): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  853): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 61
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  853): !@Sync 62
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,D/BatteryService(  853): stay LED for fully charged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
,I/MotionRecognitionService(  853): setPowerConnected  = true
,D/BatteryService(  853): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  853): [PWL] Off : 1755s ago
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  853): !@Sync 63
,E/SMD     (  282): DCD ON
,V/AlarmManager(  853): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,I/ActivityManager(  853): Killing 8145:com.samsung.android.service.travel/u0a178 (adj 15): empty for 1800s
,I/ActivityManager(  853): Killing 7693:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1800s
,I/ActivityManager(  853): Killing 8106:com.android.email/u0a163 (adj 15): empty for 1800s
,I/ActivityManager(  853): Killing 8074:com.samsung.android.sconnect/u0a138 (adj 15): empty for 1800s,
,I/ActivityManager(  853): Killing 7991:com.google.android.apps.magazines/u0a128 (adj 15): empty for 1800s
,I/ActivityManager(  853): Killing 7975:com.android.chrome/u0a88 (adj 15): empty for 1800s
,I/ActivityManager(  853): Killing 7408:com.sec.android.widgetapp.ap.hero.accuweather/u0a71 (adj 15): empty for 1800s
,I/ActivityManager(  853): Killing 7916:com.osp.app.signin/u0a45 (adj 15): empty for 1800s
,I/ActivityManager(  853): Killing 7855:com.sec.android.soagent/u0a37 (adj 15): empty for 1800s
,I/ActivityManager(  853): Killing 7839:com.samsung.klmsagent/u0a19 (adj 15): empty for 1800s
,I/ActivityManager(  853): Killing 7824:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1800s
,I/ActivityManager(  853): Killing 7799:com.sec.android.diagmonagent/1000 (adj 15): empty for 1800s
,I/ActivityManager(  853): Killing 7782:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1800s
,I/ActivityManager(  853): Killing 5359:com.google.android.music:main/u0a126 (adj 15): empty for 1800s
,D/BatteryService(  853): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  853): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  853): stay LED for fully charged
,I/ActivityManager(  853): Killing 7760:com.sec.pcw.device/1000 (adj 15): empty for 1800s
,I/ActivityManager(  853): Killing 7199:com.samsung.dcm:DCMService/u0a4 (adj 15): empty for 1800s
,I/ActivityManager(  853): Killing 8129:com.sec.android.provider.badge/u0a78 (adj 15): empty for 1801s
,I/ActivityManager(  853): Killing 7327:com.sec.android.widgetapp.activeapplicationwidget/u0a158 (adj 15): empty for 1808s
,I/ActivityManager(  853): Killing 7585:com.sec.enterprise.knox.cloudmdm.smdms/u0a179 (adj 15): empty for 1809s
I/ActivityManager(  853): Killing 7478:com.sec.android.app.camera/u0a154 (adj 15): empty for 1826s
,I/ActivityManager(  853): Killing 7460:com.sec.android.GeoLookout/u0a113 (adj 15): empty for 1826s
,I/ActivityManager(  853): Killing 7443:com.sec.android.widgetapp.dualclockdigital/u0a103 (adj 15): empty for 1827s
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,V/NetworkStats(  853): performPollLocked(flags=0x3)
,D/NtpTrustedTime(  853): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  853): UpdateStatsForKnox
,D/ConnectivityService(  853): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  853): performPollLocked() took 19ms
,I/ProcessStatsService(  853): Prepared write state in 15ms
,D/NtpTrustedTime(  853): currentTimeMillis() cache hit
,D/BatteryService(  853): Sending ACTION_BATTERY_CHANGED.
,D/NtpTrustedTime(  853): currentTimeMillis() cache hit
,D/NtpTrustedTime(  853): currentTimeMillis() cache hit
,I/ProcessStatsService(  853): Prepared write state in 9ms
,D/MotionRecognitionService(  853):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  853): Plugged
I/MotionRecognitionService(  853): setPowerConnected  = true
,V/HeadsetService( 3261): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3261): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/Procstats( 2437): User is not opted-in to Usage & Diagnostics.
,D/Batterystats( 2437): User is not opted-in to Usage & Diagnostics.
,D/GCM     ( 1677): Message class com.google.f.a.a.i
D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  853): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1677): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1677): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1677): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1677): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1677): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1677): Explicit concurrent mark sweep GC freed 37131(2MB) AllocSpace objects, 22(1782KB) LOS objects, 40% free, 18MB/30MB, paused 809us total 47.680ms
,I/ProcessStatsService(  853): Pruning old procstats: /data/system/procstats/state-2016-01-14-13-21-32.bin
,W/libprocessgroup(  853): failed to open /acct/uid_10113/pid_7460/cgroup.procs: No such file or directory
,W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_7693/cgroup.procs: No such file or directory
W/libprocessgroup(  853): failed to open /acct/uid_10103/pid_7443/cgroup.procs: No such file or directory
,W/libprocessgroup(  853): failed to open /acct/uid_10163/pid_8106/cgroup.procs: No such file or directory
W/libprocessgroup(  853): failed to open /acct/uid_10138/pid_8074/cgroup.procs: No such file or directory
,W/libprocessgroup(  853): failed to open /acct/uid_10128/pid_7991/cgroup.procs: No such file or directory
W/libprocessgroup(  853): failed to open /acct/uid_10088/pid_7975/cgroup.procs: No such file or directory
,W/libprocessgroup(  853): failed to open /acct/uid_10154/pid_7478/cgroup.procs: No such file or directory
W/libprocessgroup(  853): failed to open /acct/uid_10178/pid_8145/cgroup.procs: No such file or directory
,W/libprocessgroup(  853): failed to open /acct/uid_10179/pid_7585/cgroup.procs: No such file or directory
W/libprocessgroup(  853): failed to open /acct/uid_10158/pid_7327/cgroup.procs: No such file or directory
W/libprocessgroup(  853): failed to open /acct/uid_10078/pid_8129/cgroup.procs: No such file or directory
,W/libprocessgroup(  853): failed to open /acct/uid_10004/pid_7199/cgroup.procs: No such file or directory
W/libprocessgroup(  853): failed to open /acct/uid_10002/pid_7782/cgroup.procs: No such file or directory
,W/libprocessgroup(  853): failed to open /acct/uid_10011/pid_7824/cgroup.procs: No such file or directory
W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_7799/cgroup.procs: No such file or directory
,W/libprocessgroup(  853): failed to open /acct/uid_10037/pid_7855/cgroup.procs: No such file or directory
W/libprocessgroup(  853): failed to open /acct/uid_10126/pid_5359/cgroup.procs: No such file or directory
W/libprocessgroup(  853): failed to open /acct/uid_10019/pid_7839/cgroup.procs: No such file or directory
,W/libprocessgroup(  853): failed to open /acct/uid_10071/pid_7408/cgroup.procs: No such file or directory
W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_7760/cgroup.procs: No such file or directory
,W/libprocessgroup(  853): failed to open /acct/uid_10045/pid_7916/cgroup.procs: No such file or directory
,E/SMD     (  282): DCD ON
,E/SQLiteLog( 1677): (10) POSIX Error : 11 SQLite Error : 3850
,TIME-OUT KILL (timeout was 1800000ms),D/SSRM:m  (  853): SIOP:: AP = 260, PST = 260, CUR = 300
D/AndroidRuntime( 8993): 
D/AndroidRuntime( 8993): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8993): CheckJNI is OFF
D/AndroidRuntime( 8993): setted country_code = Germany
D/AndroidRuntime( 8993): setted countryiso_code = DE
D/AndroidRuntime( 8993): setted sales_code = DBT
D/AndroidRuntime( 8993): readGMSProperty: start
D/AndroidRuntime( 8993): readGMSProperty: already setted!!
D/AndroidRuntime( 8993): readGMSProperty: end
D/AndroidRuntime( 8993): addProductProperty: start
E/AffinityControl( 8993): AffinityControl: registerfunction enter
D/AndroidRuntime( 8993): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  853): START PACKAGE DELETE: observer{393199987}
D/PackageManager(  853): pkg{<packageName>}
D/PackageManager(  853): user{0}
D/PackageManager(  853): caller{2000}
D/PackageManager(  853): flags{3}
D/PersonaManagerService(  853): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  853): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  853): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  853): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  853): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  853): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  853): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  853): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  853): getApplicationUninstallationEnabled
D/ApplicationPolicy(  853): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  853): !@killApplicatoin: 10200, uninstall pkg
I/ActivityManager(  853): Force stopping com.test.thalitest appid=10200 user=-1: uninstall pkg
I/ActivityManager(  853): Killing 7634:com.test.thalitest/u0a200 (adj 0): stop com.test.thalitest
I/ActivityManager(  853): Killing 7900:com.sec.spp.push/u0a38 (adj 15): empty for 1800s
I/ActivityManager(  853): Killing 8200:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty for 1801s
I/ActivityManager(  853):   Force finishing activity ActivityRecord{340a0cdc u0 com.test.thalitest/.MainActivity t17}
D/FocusedStackFrame(  853): Set to : 0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/ActivityManager(  853): Killing 6073:com.sec.android.gallery3d/u0a48 (adj 15): empty for 1800s
D/WifiService(  853): Client connection lost with reason: 4
I/ActivityManager(  853): Force stopping com.test.thalitest appid=10200 user=0: pkg removed
D/ConnectivityService(  853): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/art     ( 4587): Explicit concurrent mark sweep GC freed 5023(278KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 402us total 26.591ms
I/ActivityManager(  853): Killing 8311:com.samsung.android.app.FileShareServer/u0a75 (adj 15): empty for 1800s
D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader(  853): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
W/GeofencerStateMachine( 2223): Ignoring removeGeofence because network location is disabled.
E/Zygote  ( 9022): MountEmulatedStorage()
I/libpersona( 9022): KNOX_SDCARD checking this for 10019
E/Zygote  ( 9022): v2
I/libpersona( 9022): KNOX_SDCARD not a persona
I/ActivityManager(  853): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=9022 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/art     ( 1566): Explicit concurrent mark sweep GC freed 16878(1133KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/27MB, paused 515us total 67.866ms
I/SELinux ( 9022): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 9022): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 9022): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/SamsungIME( 1864): mOCRHelper is null
I/ActivityManager(  853): Killing 7953:com.sec.chaton/u0a86 (adj 15): empty for 1800s
I/ActivityManager(  853): Killing 7937:com.sec.knox.bridge/1000 (adj 15): empty for 1800s
D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/TimaKeyStoreProvider( 9022): TimaSignature is unavailable
D/ActivityThread( 9022): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/ActivityManager(  853): Killing 8342:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty for 1800s
D/SurfaceWidgetView( 1480): destroyHardwareResources():1057401600
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
V/WindowOrientationListener(  853): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  853): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  853): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  853): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  853): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager( 9022): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/Launcher( 1480): onRestart, Launcher: 927950245
I/art     (  853): Explicit concurrent mark sweep GC freed 85026(7MB) AllocSpace objects, 233(3MB) LOS objects, 30% free, 36MB/52MB, paused 1.849ms total 185.369ms
D/ResourcesManager(  853): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     (  853): WaitForGcToComplete blocked for 129.481ms for cause Explicit
D/EnterpriseDeviceManagerService(  853): Package has changed for user 0
D/EnterpriseDeviceManagerService(  853): Admin package name: com.google.android.gms
D/Launcher( 1480): onStart, Launcher: 927950245
D/Launcher.HomeView( 1480): onStart
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2111): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 2111): [237392/6] SurfaceWidget drawing first frame
D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/Books/Books.apk
I/SurfaceFlinger(  249): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
D/StatusBarManagerService(  853): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/StatusBarManagerService(  853): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
I/KLMS-2.4.503: ( 9022): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
I/KLMS-2.4.503: ( 9022): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1452862219031
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/KLMS-2.4.503: ( 9022): MainReciver(): PACKAGE_REMOVED
D/InputMethodManagerService(  853): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/SecContentProvider2(  853): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  853): mCursor = null
I/KLMS-2.4.503: ( 9022): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
W/libprocessgroup(  853): failed to open /acct/uid_10038/pid_7900/cgroup.procs: No such file or directory
W/libprocessgroup(  853): failed to open /acct/uid_10034/pid_8200/cgroup.procs: No such file or directory
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/libprocessgroup(  853): failed to open /acct/uid_10048/pid_6073/cgroup.procs: No such file or directory
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/InputMethodManagerService(  853): Got RemoteException sending setActive(false) notification to pid 7634 uid 10200
W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
W/libprocessgroup(  853): failed to open /acct/uid_10075/pid_8311/cgroup.procs: No such file or directory
D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/RegisteredServicesCache( 1468): empty dynamic service
D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/Timeline(  853): Timeline: Activity_windows_visible id: ActivityRecord{88cb798 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t15} time:1909468
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/Videos/Videos.apk
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
E/Zygote  ( 9043): MountEmulatedStorage()
E/Zygote  ( 9043): v2
I/libpersona( 9043): KNOX_SDCARD checking this for 10104
I/libpersona( 9043): KNOX_SDCARD not a persona
I/ActivityManager(  853): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=9043 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  853): Killing 4880:com.google.android.gms.wearable/u0a12 (adj 15): empty for 1800s
D/RCPManagerService(  853): PackageReceiver onReceive()
I/HarmonyEASService(  853): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  853): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
I/SELinux ( 9043): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 9043): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
W/libprocessgroup(  853): failed to open /acct/uid_10086/pid_7953/cgroup.procs: No such file or directory
W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_7937/cgroup.procs: No such file or directory
E/SELinux ( 9043): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_8342/cgroup.procs: No such file or directory
D/BackupManagerService(  853): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  853): Receieved: android.intent.action.PACKAGE_REMOVED
D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
V/EnterpriseBillingPolicy(  853): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  853): uID is 10200
V/EnterpriseBillingPolicy(  853): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  853): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  853): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  853): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  853): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  853): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  853): getBillingProfileForVpnEngine - end - null
D/TaskPersister(  853): removeObsoleteFile: deleting file=17_task.xml
D/TaskPersister(  853): removeObsoleteFile: deleting file=17_task_thumbnail.png
D/TimaKeyStoreProvider( 9043): TimaSignature is unavailable
D/ActivityThread( 9043): Added TimaKeyStore provider
W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/libprocessgroup(  853): failed to open /acct/uid_10012/pid_4880/cgroup.procs: No such file or directory
I/art     (  853): Explicit concurrent mark sweep GC freed 15909(744KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 6.504ms total 257.462ms
D/ResourcesManager( 9043): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/elm:14451( 9043): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14451( 9043): ELMEngine.ELMEngine( context ).
D/elm:14451( 9043): MDMBridge.setEnterpriseBridge()
D/elm:14451( 9043): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8254): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8254): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8254): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
D/elm:14451( 9043): ElmAgentService : onCreate()
D/elm:14451( 9043): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 9043): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 9043): MDMBridge.getInstance()
D/elm:14451( 9043): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14451( 9043): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 9059): MountEmulatedStorage()
E/Zygote  ( 9059): v2
I/libpersona( 9059): KNOX_SDCARD checking this for 1000
I/libpersona( 9059): KNOX_SDCARD not a persona
I/ActivityManager(  853): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=9059 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/art     (  312): Explicit concurrent mark sweep GC freed 8720(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 274us total 14.653ms
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 8.293ms
W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 14MB/23MB, paused 288us total 7.942ms
W/ResourcesManager(  853): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  853): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  853): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/SELinux ( 9059): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 9059): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 9059): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/elm:14451( 9043): ElmAgentService : onDestroy().
D/PackageManager(  853): delete codoeFile: 
D/PackageManager(  853): result of delete: 1{393199987}
D/TimaKeyStoreProvider( 9059): TimaSignature is unavailable
D/ActivityThread( 9059): Added TimaKeyStore provider
D/AndroidRuntime( 8993): Shutting down VM
D/ResourcesManager(  853): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
D/ResourcesManager( 9059): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
D/ResourcesManager(  853): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
I/PCWCLIENTTRACE_LOG( 9059): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 9059): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 9059): new DMDBOpenHelper instance
D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
I/PCWCLIENTTRACE_PushUtil( 9059): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 9059): sales region : global
I/PCWCLIENTTRACE_PushUtil( 9059): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 9059): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  853): checkUser: useridlist=null, currentuser=0
W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
E/Zygote  ( 9075): MountEmulatedStorage()
E/Zygote  ( 9075): v2
I/libpersona( 9075): KNOX_SDCARD checking this for 10034
I/libpersona( 9075): KNOX_SDCARD not a persona
I/ActivityManager(  853): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=9075 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  853): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  853): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources(  853): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager(  853): clearDefaults: com.test.thalitest
I/CrashAnrDetector(  853): onPackageRemoved : com.test.thalitest
I/SELinux ( 9075): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 9075): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 9075): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 9075): TimaSignature is unavailable
D/ActivityThread( 9075): Added TimaKeyStore provider
D/ResourcesManager( 9075): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
I/FeatureConfig( 9075): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
D/ResourcesManager( 9075): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/ResourcesManager( 9075): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 9075): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9075): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9075): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9075): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ResourcesManager( 9075): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
W/ResourcesManager( 9075): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 9075): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9075): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 9075): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9075): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9075): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9075): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.

```
