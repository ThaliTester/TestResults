#### Test 56151093f3290d6_thali07_samsung-SM-G900F Logs


```
--------- beginning of system
,V/AlarmManager(  840): waitForAlarm result :4
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
--------- beginning of main
E/Zygote  ( 7521): MountEmulatedStorage()
I/libpersona( 7521): KNOX_SDCARD checking this for 10179
E/Zygote  ( 7521): v2
I/libpersona( 7521): KNOX_SDCARD not a persona
I/ActivityManager(  840): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler: pid=7521 uid=10179 gids={50179, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
I/SELinux ( 7521): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7521): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
E/SELinux ( 7521): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  840): Plugged
I/MotionRecognitionService(  840): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/TimaKeyStoreProvider( 7521): TimaSignature is unavailable
D/ActivityThread( 7521): Added TimaKeyStore provider
D/ResourcesManager( 7521): creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
W/ResourcesManager( 7521): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/UMC:Core( 7521): onCreate(): 
D/USER_AGENT( 7521): UMC/1.1.39 (SM-G900F) SAFE-5.3 KNOX-2.3
D/[SAMSUNG SMARCART NATIVE]( 7521): initialize...
D/[SAMSUNG SMARCART NATIVE]( 7521): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
I/CSTORAGE( 7521): ================================================
I/CSTORAGE( 7521):  CSTORAGE_SKM_LIB v1.0.8
I/CSTORAGE( 7521): ================================================
I/TZ_CCM_C_GetFunctionList: ( 7521): TZ_CCM_C_GetFunctionList was called
D/[SAMSUNG SMARCART NATIVE]( 7521): FINISHED: initialize rv:0
D/AndroidRuntime( 7527): 
D/AndroidRuntime( 7527): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7527): CheckJNI is OFF
D/AndroidRuntime( 7527): setted country_code = Germany
D/AndroidRuntime( 7527): setted countryiso_code = DE
D/AndroidRuntime( 7527): setted sales_code = DBT
D/AndroidRuntime( 7527): readGMSProperty: start
D/AndroidRuntime( 7527): readGMSProperty: already setted!!
D/AndroidRuntime( 7527): readGMSProperty: end
D/AndroidRuntime( 7527): addProductProperty: start
D/UMC:SecurityUtils( 7521): Loaded server certificates: 0
D/UMC:SecurityUtils( 7521): Loaded server certificates: 0
D/UMC:SecurityUtils( 7521): timaVersion on the device: 3.0
D/UMC:CloudMDMSecurity( 7521): New Flow
D/TimaService(  840): TIMA3: in ccmRegisterForDefaultCertificate
D/TimaService(  840): TIMA: in getTimaVersion
I/        (  840): CCM JNI: In ccm_register_for_default_cert
I/        (  840): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: (  840): DEBUG_CONTAINER_PROBLEM Enter TZ_CCM_C_Initialize_TLC!
I/TZ_CCM_C_Initialize: (  840): pInitArgs 0x96c01814 has not called C_Init before.
I/TZ_CCM_C_Initialize: (  840): &ctx = 0xa00b3c1c
I/TLC_TZ_CCM: (  840): creating new ccm context...
I/TLC_TZ_CCM: (  840): initializing ccm context...
I/TLC_TZ_CCM: (  840): root = /firmware/image, root_strlen = 15
I/TLC_TZ_CCM: (  840): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  840): input max_sendmsg_size = 19420
I/TZ: client_server_communication(  840): input max_recvmsg_size = 19420
I/TZ: client_server_communication(  840): root = /firmware/image, root_len = 15
I/TZ: client_server_communication(  840): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  840): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication(  840): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication(  840): Client_Server_Open was called
I/TZ: client_server_communication(  840): IClientServer::IClientServer()
I/TZ: client_server_communication(  840): BpClientServer::BpClientServer()
I/TZ: client_server_communication(  840): IClientServer::~IClientServer()
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
D/QSEECOMAPI: ( 1077): Loaded image: APP id = 2
I/TZ: qc_tlc_communication( 1077): TIMA: path = /firmware/image, fname = tz_ccm, tzapp is loaded
I/TZ: client_server_communication(  840): OpenSWConn(CCM) is successful
I/TZ: client_server_communication(  840): Client_Server_Open succeeded, serverName = CCM
I/TZ_CCM_C_Initialize: (  840): ctx = 0x9f2e5dc0, comm = 0x9f580f88, sendmsg = 0x9d524000, recvmsg = 0x9d528c00
I/TZ_init: (  840): TZ_init: sending initialization request...
I/TZ: client_server_communication(  840): Cmd id = 2, len = 19456
I/TZ: client_server_communication(  840): Calling Communicate()
I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1077): COMM
I/TZ_init: (  840): TZ_init: successful initialization
I/TLC_TZ_COMMON: key_db_init: (  840): Exercising TZ_DB_INIT in TLC
I/TZ: client_server_communication(  840): Cmd id = 17, len = 19456
I/TZ: client_server_communication(  840): Calling Communicate()
I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1077): COMM
I/TZ_COMMON: tlc_key_db_util: (  840): DB Operation suceeded
I/TLC_TZ_CCM: register for default cert: (  840): Exercising TZ_CCM_register_default_TLC
I/TZ: client_server_communication(  840): Cmd id = 25, len = 19456
I/TZ: client_server_communication(  840): Calling Communicate()
I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1077): COMM
I/TLC_TZ_CCM: register for default cert: (  840): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: (  840): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
I/TZ_CCM_C_Finalize: (  840): DEBUG_CONTAINER_PROBLEM Exercising TZ_CCM_C_Finalize_TLC
I/TZ: client_server_communication(  840): Cmd id = 41, len = 19456
I/TZ: client_server_communication(  840): Calling Communicate()
I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1077): COMM
I/TZ: client_server_communication(  840): Client_Server_Close was called
I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(1) 16
I/TZ_CCM_SERVER( 1077): CLOSESWCONN
D/QSEECOMAPI: ( 1077): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1077): QSEECom_shutdown_app, app_id = 2
I/TZ: client_server_communication(  840): Client_Server_Close succeeded
D/UMC:CloudMDMSecurity( 7521): ccmRegisterForDefaultCertificate: 0
D/UMC:CloudMDMSecurity( 7521): TIMA service call for password change success!!
V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UMC:AdminManager( 7521): init - start
D/UMC:AdminManager( 7521): loadAdmins
I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UMC:AdminManager( 7521): startPolicyHandlers
I/UMC:TestPolicyHandler( 7521): Setup is called in testpolicyhandler
D/Finsky  ( 6601): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6601): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6601): [1] 5.onFinished: Scheduling replication attempt 2.
D/UMC:AdminManager( 7521): init - end
V/UMC:AlarmHandler( 7521): Enter loadList
D/GSLBManager( 7521): migrateStoredUrlFromOldPref
E/AffinityControl( 7527): AffinityControl: registerfunction enter
D/GSLBManager( 7521): migrateStoredUrlFromOldPref : Migration Not Needed
D/UMC:UMCAdmin( 7521): deactivateUMCAdminIfNotRequired : -1
E/UMC:Utils( 7521): Admin not found in package com.samsung.knoxpb.mdm
D/UMC:UMCAdmin( 7521): deactivateUMCAdmin : -1
D/UMC:UMCAdmin( 7521): isContainer : 0
W/LicenseLogService(  840): log() failed
D/EnterpriseDeviceManagerService(  840): isManagedProfileUser(): userId = 0
E/UMC:UMCAdmin( 7521): No active admin owned by uid 10179
D/UMC:UMCAdmin( 7521): isContainer : 0
D/UMC:UMCAdmin( 7521): deactivateUMCAdmin - UMC App Admin deactivated
V/UMC:AlarmHandler( 7521): onReceive :Intent { flg=0x14 cmp=com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler (has extras) }
I/ActivityManager(  840): Killing 4877:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
D/AndroidRuntime( 7527): Calling main entry com.android.commands.am.Am
D/QuickStartReceiver( 7521): Msg Id : 2
D/QuickStartReceiver( 7521): model : SM-G900F
D/QuickStartReceiver( 7521): id : 100
E/PersonaManagerService(  840): inState():  stateMachine is null !!
V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  840): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  840): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  840): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 840  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  840): mDVFSHelper.acquire()
D/FocusedStackFrame(  840): Set to : 0
D/Launcher.HomeView( 1488): onPause
D/Launcher( 1488): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/AndroidRuntime( 7527): Shutting down VM
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
W/libprocessgroup(  840): failed to open /acct/uid_10035/pid_4877/cgroup.procs: No such file or directory
V/TaskCloserActivity( 7268): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/SurfaceFlinger(  249): id=14 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
E/Zygote  ( 7562): MountEmulatedStorage()
E/Zygote  ( 7562): v2
I/libpersona( 7562): KNOX_SDCARD checking this for 10200
I/libpersona( 7562): KNOX_SDCARD not a persona
I/ActivityManager(  840): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7562 uid=10200 gids={50200, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7562): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7562): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
E/SELinux ( 7562): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/StatusBarManagerService(  840): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/MicrophoneInputStream( 1554): mic_close gfk@24d1432b
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
V/AudioPolicyManager(  287): stopInput() input 30
V/AudioPolicyManager(  287): releaseInput() 30
V/AudioPolicyManager(  287): closeInput(30)
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
V/audio_hw_primary(  287): in_standby: enter
I/HotwordRecognitionRnr( 1554): Hotword detection finished
I/HotwordRecognitionRnr( 1554): Stopping hotword detection.
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/TimaKeyStoreProvider( 7562): TimaSignature is unavailable
D/ActivityThread( 7562): Added TimaKeyStore provider
V/WindowOrientationListener(  840): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  840): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  840): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  840): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  840): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  840): Display changed displayId=0
D/Launcher.HomeView( 1488): onStop
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2081): [237392/6] Surface widget pause on instance = 1
D/accuweather( 2081): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2081): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2081): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/SurfaceWidgetView( 1488): destroyHardwareResources():421935465
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2081): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
V/audio_hw_primary(  287): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  287): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  287): disable_audio_route: reset mixer path: audio-record
D/audio_route(  287): ++++ audio_route_update_mixer ==============
D/audio_route(  287): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  287): Setting mixer control: value: 0
D/audio_route(  287): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  287): disable_audio_route: exit
V/audio_hw_primary(  287): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  287): ++++ audio_route_update_mixer ==============
D/audio_route(  287): Setting mixer control: DEC2 Volume
D/audio_route(  287): Setting mixer control: value: 0
D/audio_route(  287): Setting mixer control: SLIM TX7 MUX, value: 0
D/audio_route(  287): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  287): Setting mixer control: value: 0
E/SMD     (  282): DCD ON
D/audio_route(  287): Setting mixer control: DEC2 MUX, value: 0
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/audio_route(  287): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  287): stop_input_stream: exit: status(0)
V/audio_hw_primary(  287): in_standby: exit:  status(0)
V/audio_hw_primary(  287): adev_close_input_stream
V/audio_hw_primary(  287): in_standby: enter
V/audio_hw_primary(  287): in_standby: exit:  status(0)
E/audio_hw_primary(  287): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  287): releaseInput() exit
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/Launcher( 1488): onTrimMemory. Level: 20
D/SurfaceWidgetView( 1488): destroyHardwareResources():421935465
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/StatusBarManagerService(  840): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/accuweather( 2081): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 2081): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager( 7562): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,I/WebViewFactory( 7562): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7562): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  840): CMD_RSSI_POLL : out!
,I/LibraryLoader( 7562): Loading: webviewchromium
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
I/LibraryLoader( 7562): Time to load native libraries: 2 ms (timestamps 7520-7522)
I/LibraryLoader( 7562): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7562): Binding Chromium to main looper Looper (main, tid 1) {1f2466f2}
,I/LibraryLoader( 7562): Expected native library version number "",actual native library version number ""
I/chromium( 7562): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/BrowserStartupController( 7562): Initializing chromium process, renderers=0
,W/art     ( 7562): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7562): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7562): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7562): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/Adreno-EGL( 7562): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7562): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7562): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7562): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7562): Remote Branch: 
I/Adreno-EGL( 7562): Local Patches: 
I/Adreno-EGL( 7562): Reconstruct Branch: 
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,W/chromium( 7562): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7562): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7562): Attempt to remove local handle scope entry from IRT, ignoring
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,W/AwContents( 7562): onDetachedFromWindow called when already detached. Ignoring
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/SystemWebViewEngine( 7562): CordovaWebView is running on device made by: samsung
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,W/art     ( 7562): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 7562): Attempt to remove local handle scope entry from IRT, ignoring
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/Activity( 7562): performCreate Call secproduct feature valuefalse
,D/Activity( 7562): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 7562): Render dirty regions requested: true
,D/ActivityManager(  840): post active user change for 0
,D/KnoxTimeoutHandler(  840): postActiveUserChange for user 0
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/KnoxTimeoutHandler(  840): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/OpenGLRenderer( 7562): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7562): HWUI protection enabled for context ,  &this =0xb3954b28 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7562): Enabling debug mode 0
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/InputMethodManagerService(  840): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
,I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/ActivityManager(  840): Displayed com.test.thalitest/.MainActivity: +629ms
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/Timeline( 7562): Timeline: Activity_idle id: android.os.BinderProxy@f5acc6d time:97876
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/JsMessageQueue( 7562): Set native->JS mode to OnlineEventsBridgeMode
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,I/chromium( 7562): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7562): 
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/jxcore_app_log( 7562): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1359586560
,D/JX-Cordova( 7562): jxcore cordova android initializing
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SurfaceFlinger(  249): id=14 Removed Starting com.test.thalitest (7/8)
,I/SurfaceFlinger(  249): id=14 Removed Starting com.test.thalitest (-2/8)
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/CustomFrequencyManagerService(  840): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 840  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  840): mDVFSHelper.release()
I/Timeline(  840): Timeline: Activity_windows_visible id: ActivityRecord{35308e3e u0 com.test.thalitest/.MainActivity t17} time:98114
D/CustomFrequencyManagerService(  840): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 840  pkgName : ACTIVITY_RESUME_BOOSTER@10
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/CustomFrequencyManagerService(  840): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 840  tag : ACTIVITY_RESUME_BOOSTER@10
,D/PowerManagerService(  840): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1168 (0x0)
,W/jxcore-log( 7562): Initializing JXcore engine
W/jxcore-log( 7562): JXcore engine is ready
,W/jxcore-log( 7562): Starting JXcore engine
,D/SSRM:m  (  840): SIOP:: AP = 370, PST = 429, CUR = 300
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/auditd  ( 2123): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  840): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  840): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7621): MountEmulatedStorage()
E/Zygote  ( 7621): v2
I/libpersona( 7621): KNOX_SDCARD checking this for 1000
I/libpersona( 7621): KNOX_SDCARD not a persona
,I/ActivityManager(  840): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7621 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/jxcore-log( 7562): Platform android
W/jxcore-log( 7562): 
,W/jxcore-log( 7562): Process ARCH arm
W/jxcore-log( 7562): 
,I/SELinux ( 7621): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7621): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7621): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7621): TimaSignature is unavailable
,D/ActivityThread( 7621): Added TimaKeyStore provider
,D/ResourcesManager( 7621): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7621):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7621):  SeDenialReceiver : File path = null
,I/ActivityManager(  840): Killing 6793:com.policydm/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  840): failed to open /acct/uid_1000/pid_6793/cgroup.procs: No such file or directory
,E/SMD     (  282): DCD ON
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore in!
,I/jxcore-log( 7562): JXcore Cordova bridge is ready!
I/jxcore-log( 7562): 
W/jxcore-log( 7562): JXcore engine is started
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  840): CMD_RSSI_POLL : out!
,E/Adreno-ES20( 7562): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7562): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/jxcore-log( 7562): Toggling radios to true
I/jxcore-log( 7562): 
,D/BluetoothAdapter( 7562): enable()
,D/BluetoothAdapter( 7562): enable(): BT is already enabled..!
,D/WifiService(  840): New client listening to asynchronous messages
,I/WifiManager( 7562): packageName : com.test.thalitest
,D/SecContentProvider(  840): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  840): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  840): mCursor = null
,D/WifiService(  840): setWifiEnabled: true pid=7562, uid=10200
,E/WifiService(  840): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  840): Permission Denial: getCurrentUser() from pid=7562, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  840): Failed getting userId using ActivityManagerNative
W/WifiService(  840): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7562, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  840): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  840): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  840): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  840): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  840): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  840): name = wifi_on
,I/WifiService(  840): disconnect: pid=7562, uid=10200
,I/wpa_supplicant( 1259): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7562): Radios toggled
I/jxcore-log( 7562): 
,I/jxcore-log( 7562): My device name is: samsung-SM-G900F
I/jxcore-log( 7562): 
,I/wpa_supplicant( 1259): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1259): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1259): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1259): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine(  840): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1259): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1259): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1259): Disconnected - do not scan
I/wpa_supplicant( 1259): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  840): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  840): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  840): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  840): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  840): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  840): InactiveState{ what=143375 }
,D/WifiP2pService(  840): P2pEnabledState{ what=143375 }
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/NativeCrypto( 1676): Read error: ssl=0xaf42fe00: I/O error during system call, Connection timed out
V/NativeCrypto( 1676): SSL shutdown failed: ssl=0xaf42fe00: I/O error during system call, Broken pipe
,E/WifiStateMachine(  840): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  840): updateNetworkInfo()
,D/ConnectivityService(  840): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  840): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,I/WifiTrafficPoller(  840): evaluateTrafficStatsPolling
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  840): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  840): DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  840): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  840): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  840): Validated
,I/CLocInfoService(  840): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1168): applyOpen
,E/WifiConfigStore(  840): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Hs20UtilService( 1359): Starting #6
,I/Hs20UtilService( 1359): Message received 5007
,D/NearbySettings( 1359): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1359): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1359): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
E/WifiStateMachine(  840): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1259): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1259): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1259): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1259): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1259): First Scan Start
D/ConnectivityService(  840): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1359): DMSUtil.isNetworkConnected - P2P: IDLE
I/wpa_supplicant( 1259): Scan requested (ret=0) - scan timeout 30 seconds
I/NearbySettings( 1359): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1359): MountReceiver.onReceive - Set preference state off
E/WifiStateMachine(  840): ConnectModeState: Network connection lost 
,V/NearbySettings( 1359): MountReceiver.mPrefHandler - 7002
,E/WifiStateMachine(  840): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,E/WifiStateMachine(  840): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  840): InactiveState{ what=143375 }
,D/WifiP2pService(  840): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  277): Clearing all IP addresses on wlan0
D/ConnectivityService(  840): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  840): calling update connectivity
D/ConnectivityService(  840):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  840):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  840): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  840): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/EntConnectivity(  840): Not allowed due to - mEnabled false
D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  840): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  840): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  840): Disconnected - quitting
E/WifiStateMachine(  840): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/WifiStateMachine(  840): updateConfiguredNetworkExpiration - currTime: 1452862874150
D/WifiStateMachine(  840): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,E/WifiStateMachine(  840): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  840): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/WifiNetworkAgent(  840): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityService(  840): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  840): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/WifiTrafficPoller(  840): evaluateTrafficStatsPolling
I/CLocInfoService(  840): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  840): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  840): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/TelephonyNetworkFactory( 1474): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/CSLegacyTypeTracker(  840): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  840): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,E/WifiStateMachine(  840): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  840): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,I/Hs20UtilService( 1359): Starting #7
,I/Hs20UtilService( 1359): Message received 5007
,D/ConnectivityService(  840): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  840): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/NearbySettings( 1359): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1359): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1359): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/SmartBondingService(  840): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  840): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  840): getSBEnabled() enabled =false
D/SmartBondingService(  840): getSBEnabled() enabled =false
D/SmartBondingService(  840): getSBEnabled() enabled =false
,E/WifiStateMachine(  840): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  840): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  840): setDetailed state send new extra info"NG700"
E/ConnectivityService(  840): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/SmartBondingService(  840): getNetworkEnabled : wifi : true mobile : true
D/SecContentProvider2(  840): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  840): mCursor = null
,E/ConnectivityService(  840): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/NetworkStats(  840): updateIfacesLocked()
V/NetworkStats(  840): performPollLocked(flags=0x1)
D/NtpTrustedTime(  840): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  840): UpdateStatsForKnox
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1168): getUpdateDataNetType(): 0
I/NearbySettings( 1359): DMSUtil.isNetworkConnected - P2P: IDLE
D/StatusBar.NetworkController( 1168): updateDataNetType()
D/StatusBar.NetworkController( 1168): NoService, mRoamingIconId = 0
I/NearbySettings( 1359): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1359): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1359): MountReceiver.mPrefHandler - 7002
,D/NtpTrustedTime(  840): currentTimeMillis() cache hit
,V/NetworkStats(  840): performPollLocked() took 8ms
D/NtpTrustedTime(  840): currentTimeMillis() cache hit
,D/NtpTrustedTime(  840): currentTimeMillis() cache hit
,D/NtpTrustedTime(  840): currentTimeMillis() cache hit
V/NetworkStats(  840): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  840): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1168): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/SecContentProvider2(  840): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  840): mCursor = null
,D/NtpTrustedTime(  840): currentTimeMillis() cache hit
,D/NtpTrustedTime(  840): currentTimeMillis() cache hit
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
,D/ConnectivityService(  840): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ApplicationPolicy(  840): updateDataUsageMap
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,D/Tethering(  840): MasterInitialState.processMessage what=3
,D/SmartBondingService(  840): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  840): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  840): getSBEnabled() enabled =false
D/SmartBondingService(  840): getSBEnabled() enabled =false
D/SmartBondingService(  840): getSBEnabled() enabled =false
D/SmartBondingService(  840): getNetworkEnabled : wifi : true mobile : true
I/CLocInfoService(  840): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  840): CLoinfo wifi false
I/SystemBroadcastReceiver( 7143): [#DCM#] [DCM_Performance] onReceive completed in time  1254 microsec. 
,E/Zygote  ( 7690): MountEmulatedStorage()
,E/Zygote  ( 7690): v2
I/libpersona( 7690): KNOX_SDCARD checking this for 1000
I/libpersona( 7690): KNOX_SDCARD not a persona
I/ActivityManager(  840): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7690 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/accuweather( 2081): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,W/SLocation(  840): No Active Data Connection
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7143): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7143): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7143): [#DCM#] setIsConnectedForExtractors 
,I/SELinux ( 7690): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7690): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SELinux ( 7690): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5370): type=WIFI subType= reason=null isConnected=false
,I/DBG_DM  ( 3796): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3796): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/TimaKeyStoreProvider( 7690): TimaSignature is unavailable
,D/ActivityThread( 7690): Added TimaKeyStore provider
,D/ResourcesManager( 7690): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG( 7690): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7690): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7690): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 7690): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7690): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7690): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7690): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7690): noConnectivity : true
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7716): MountEmulatedStorage()
,E/Zygote  ( 7716): v2
I/libpersona( 7716): KNOX_SDCARD checking this for 10002
,I/libpersona( 7716): KNOX_SDCARD not a persona
,I/ActivityManager(  840): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7716 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  840): Killing 5287:com.sec.spp.push/u0a38 (adj 15): bgCount ##41
,I/art     (  314): Explicit concurrent mark sweep GC freed 8744(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 302us total 16.693ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 253us total 8.266ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 8.297ms
,I/SELinux ( 7716): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7716): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7716): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  840): failed to open /acct/uid_10038/pid_5287/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7716): TimaSignature is unavailable
,D/ActivityThread( 7716): Added TimaKeyStore provider
,D/ResourcesManager( 7716): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  840): Killing 6087:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7733): MountEmulatedStorage()
I/libpersona( 7733): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7733): v2
I/libpersona( 7733): KNOX_SDCARD not a persona
,I/ActivityManager(  840): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7733 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7733): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7733): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7733): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7733): TimaSignature is unavailable
,D/ActivityThread( 7733): Added TimaKeyStore provider
,D/ResourcesManager( 7733): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,W/libprocessgroup(  840): failed to open /acct/uid_10042/pid_6087/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 7733): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7733): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7733): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/wpa_supplicant( 1259): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 1259): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1259): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1259): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1259): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
I/DIAGMON_AGENT( 7733): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,E/WifiStateMachine(  840): [1,452,862,875,212 ms] noteScanEnd no scan source
,I/DIAGMON_AGENT( 7733): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7733): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/WifiStateMachine(  840): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@329eeb02 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  840): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  840): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  840): setDetailed state send new extra info0x
,D/SecContentProvider2(  840): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  840): mCursor = null
,I/CLocInfoService(  840): External Intent Received android.net.wifi.SCAN_RESULTS
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7752): MountEmulatedStorage()
,E/Zygote  ( 7752): v2
I/libpersona( 7752): KNOX_SDCARD checking this for 10011
I/libpersona( 7752): KNOX_SDCARD not a persona
,I/wpa_supplicant( 1259): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 1259): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1259): Associated with C0.AA.48
,E/WifiStateMachine(  840): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  840): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,I/ActivityManager(  840): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7752 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SecContentProvider2(  840): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  840): mCursor = null
,I/SELinux ( 7752): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7752): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7752): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 1259): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1259): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  840): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  840): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  840): setDetailed state send new extra info"NG700"
D/SecContentProvider2(  840): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  840): mCursor = null
,I/wpa_supplicant( 1259): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1259): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1259): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  840): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  840): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 1259): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1259): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1259): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1259): Blacklist: Clear (temp) 
I/wpa_supplicant( 1259): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  840): Network connection established
D/WifiNative-HAL(  840): callSECApiVoid - ID [50]
E/WifiStateMachine(  840): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/CLocInfoService(  840): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  840): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService(  840): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  840): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  840): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  840): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  840): Got NetworkAgent Messenger
D/ConnectivityService(  840): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  840): updateNetworkInfo()
D/ConnectivityService(  840): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  840): NetworkAgent connected
,E/WifiStateMachine(  840): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  840): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  840): ObtainingIpAddress "NG700" nid=0
,E/WifiConfigStore(  840): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/TimaKeyStoreProvider( 7752): TimaSignature is unavailable
,D/CommandListener(  277): Setting iface cfg
,E/WifiStateMachine(  840): Start Dhcp Watchdog 2
D/ActivityThread( 7752): Added TimaKeyStore provider
D/SecContentProvider2(  840): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  840): mCursor = null
,D/ResourcesManager( 7752): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore in!
,E/WifiStateMachine(  840): calculateWifiScore() report new score 60
I/WifiStateMachine(  840): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  840): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  840): CMD_RSSI_POLL : out!
D/ConnectivityService(  840): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,E/WifiStateMachine(  840): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  840): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  840): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/SecContentProvider2(  840): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  840): mCursor = null
,I/ActivityManager(  840): Killing 6814:com.osp.app.signin/u0a45 (adj 15): bgCount ##41
,I/FOTA_Client( 7752): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7752): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7752): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7752): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7752): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  840): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  840): do suspend false
,D/WifiP2pService(  840): InactiveState{ what=143375 }
,D/WifiP2pService(  840): P2pEnabledState{ what=143375 }
,E/Zygote  ( 7768): MountEmulatedStorage()
,E/Zygote  ( 7768): v2
W/libprocessgroup(  840): failed to open /acct/uid_10045/pid_6814/cgroup.procs: No such file or directory
I/libpersona( 7768): KNOX_SDCARD checking this for 10019
I/libpersona( 7768): KNOX_SDCARD not a persona
,I/ActivityManager(  840): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7768 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  840): Killing 6835:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,I/SELinux ( 7768): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7768): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7768): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7768): TimaSignature is unavailable
,D/ActivityThread( 7768): Added TimaKeyStore provider
,D/ResourcesManager( 7768): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,W/libprocessgroup(  840): failed to open /acct/uid_10051/pid_6835/cgroup.procs: No such file or directory
,I/KLMS-2.4.503: ( 7768): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7768): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452862875558
,I/KLMS-2.4.503: ( 7768): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7768): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7768): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  840): Killing 6853:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7783): MountEmulatedStorage()
I/libpersona( 7783): KNOX_SDCARD checking this for 10037
E/Zygote  ( 7783): v2
I/libpersona( 7783): KNOX_SDCARD not a persona
,I/ActivityManager(  840): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7783 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7783): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7783): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7783): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7783): TimaSignature is unavailable
,D/ActivityThread( 7783): Added TimaKeyStore provider
,D/ResourcesManager( 7783): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7783): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/dhcpcd  ( 7803): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 7803): version 5.5.6 starting
,E/dhcpcd  ( 7803): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/Zygote  ( 7805): MountEmulatedStorage()
,E/Zygote  ( 7805): v2
I/libpersona( 7805): KNOX_SDCARD checking this for 1000
I/libpersona( 7805): KNOX_SDCARD not a persona
,I/ActivityManager(  840): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7805 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  840): Killing 6296:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/dhcpcd  ( 7803): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7803): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7803): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7803): bssid match
,I/dhcpcd  ( 7803): wlan0: rebinding lease of 192.168.1.135
I/SELinux ( 7805): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7805): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7805): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  840): failed to open /acct/uid_10058/pid_6853/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7805): TimaSignature is unavailable
,D/ActivityThread( 7805): Added TimaKeyStore provider
,D/ResourcesManager( 7805): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,W/libprocessgroup(  840): failed to open /acct/uid_1000/pid_6296/cgroup.procs: No such file or directory
,I/dhcpcd  ( 7803): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/dhcpcd  ( 7803): wlan0: leased 192.168.1.135 for 86400 seconds
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  840): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  840): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  840): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/Zygote  ( 7832): MountEmulatedStorage()
E/Zygote  ( 7832): v2
I/libpersona( 7832): KNOX_SDCARD checking this for 10038
I/libpersona( 7832): KNOX_SDCARD not a persona
,I/ActivityManager(  840): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7832 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  840): Killing 6529:com.sec.chaton/u0a86 (adj 15): bgCount ##41
,I/SELinux ( 7832): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7832): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7832): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7832): TimaSignature is unavailable
,D/ActivityThread( 7832): Added TimaKeyStore provider
,D/ResourcesManager( 7832): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService( 7832): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 7832): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7832): PushLog.txt file is not deleted.
,D/SPPClientService( 7832): PushLog.txt file is not deleted.
D/SPPClientService( 7832): ============PushLog. stop!
,W/libprocessgroup(  840): failed to open /acct/uid_10086/pid_6529/cgroup.procs: No such file or directory
,E/SPPClientService( 7832): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7866): MountEmulatedStorage()
E/Zygote  ( 7866): v2
I/libpersona( 7866): KNOX_SDCARD checking this for 10045
I/libpersona( 7866): KNOX_SDCARD not a persona
,I/ActivityManager(  840): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7866 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  840): Killing 6876:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,I/SELinux ( 7866): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7866): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7866): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,E/SPPClientService( 7832): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider( 7866): TimaSignature is unavailable
,D/ActivityThread( 7866): Added TimaKeyStore provider
,D/PowerManagerService(  840): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  840): getFinalBrightness : 15 -> 15
,D/PowerManagerService(  840): [s] DisplayPowerCallbacks : onStateChanged()
,W/libprocessgroup(  840): failed to open /acct/uid_10098/pid_6876/cgroup.procs: No such file or directory
,D/lights  (  840): lcd : 30 +
,E/WifiStateMachine(  840): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/lights  (  840): lcd : 30 -
,D/ResourcesManager( 7866): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/WifiP2pService(  840): InactiveState{ what=143375 }
D/WifiP2pService(  840): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  840): WifiStateMachine DHCP successful
,E/WifiStateMachine(  840): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  840): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  840): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  840): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  840): Not connected state, yet.
E/WifiStateMachine(  840): VerifyingLinkState enter
,D/WifiStateMachine(  840): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  840): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  840): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  840): callSECApiInt - ID [210]
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/WifiStateMachine(  840): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,D/lights  (  840): lcd : 22 +
,E/ConnectivityService(  840): updateNetworkInfo()
,D/ConnectivityService(  840): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  840): Adding iface wlan0 to network 503
,D/lights  (  840): lcd : 22 -
,I/CLocInfoService(  840): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  840): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  840): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  840): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/DisplayPowerController(  840): getFinalBrightness : 15 -> 15
,D/WifiWatchdogStateMachine.SingDnsChecker(  840): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  840): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/lights  (  840): lcd : 15 +
,E/WifiStateMachine(  840): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  840): Now, connected state.
,E/WifiStateMachine(  840): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,D/lights  (  840): lcd : 15 -
,D/DisplayPowerController(  840): getFinalBrightness : 15 -> 15
,E/WifiStateMachine(  840): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  840): evaluateTrafficStatsPolling
,I/CLocInfoService(  840): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  840): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  840): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,E/WifiStateMachine(  840): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  840): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  840): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  840): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  840): updateSourceRoutes : add src route for:192.168.1.135
V/        (  277): QcRouteController
,I/WifiTrafficPoller(  840): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  840): mBoosterFLAG : 0
,I/WifiTrafficPoller(  840): current booster mode : FullMode
,E/WifiStateMachine(  840): ConnectedState Enter  mScreenOn=true scanperiod=20000
I/SA      ( 7866): [SSP] onCreated
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiNative-HAL(  840): callSECApiVoid - ID [212]
,I/CLocInfoService(  840): External Intent Received android.net.wifi.STATE_CHANGE
,I/WifiStateMachine(  840): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,V/        (  277): QcRouteController
,I/SA      ( 7866): [TPM] There is no property file
,I/SA      ( 7866): [SCU] isHaveSA() - false
,I/SA      ( 7866): [TPM] getModelProperty : null
I/SA      ( 7866): [TPM] getCSCProperty : null
,I/SA      ( 7866): [DM] init START
,I/SA      ( 7866): [DM] This device is not a Vodafone
,W/ResourceType( 7866): Failure getting entry for 0x7f06000f (t=5 e=15) (error -75)
,W/ResourceType( 7866): Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,W/ResourceType( 7866): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 7866): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 7866): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 7866): Failure getting entry for 0x7f060001 (t=5 e=1) (error -75)
,W/ResourceType( 7866): Failure getting entry for 0x7f060013 (t=5 e=19) (error -75)
,V/        (  277): QcRouteController
,W/ResourceType( 7866): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7866): Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,W/ResourceType( 7866): Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
W/ResourceType( 7866): Failure getting entry for 0x7f060024 (t=5 e=36) (error -75)
,W/ResourceType( 7866): Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,W/ResourceType( 7866): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
W/ResourceType( 7866): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7866): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 7866): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 7866): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 7866): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 7866): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 7866): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,V/        (  277): QcRouteController
,I/SA      ( 7866): [SCU] isHaveSA() - false
I/SA      ( 7866): support phone number id : false
,I/SA      ( 7866): [DM] init END
,I/SA      ( 7866): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7866): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 7866): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7866): [SLFUCHKMGR] constructor called
,I/SA      ( 7866): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7866): [OR] == isSIMCardReady false ==
,I/SA      ( 7866): [SCU] == networkStateCheck == false
I/SA      ( 7866): [OR] onReceive END
,V/        (  277): QcRouteController
,I/ActivityManager(  840): Killing 6923:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,V/        (  277): QcRouteController
,V/        (  277): QcRouteController
,D/accuweather( 7351): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7351): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7351): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7351): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7351): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
V/        (  277): QcRouteController
,D/accuweather( 7351): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1317): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ConnectivityService(  840): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  840): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  840): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  840): updateNetworkInfo()
D/ConnectivityService(  840): calling update connectivity
E/ConnectivityService(  840): updateNetworkInfo()
D/ConnectivityService(  840): ignoring duplicate network state non-change
D/ConnectivityService(  840): ignoring duplicate network state non-change
D/ConnectivityService(  840): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  840): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  840): calling update connectivity
D/ConnectivityService(  840): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  840):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  840):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  840):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  840): currentScore = 0, newScore = 60
D/ConnectivityService(  840):    accepting network in place of null
D/ConnectivityService(  840): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  840): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  840): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  840): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  840): Validated
E/CSLegacyTypeTracker(  840): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  840): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  840): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 1474): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/ActivityManager(  840): Failed to clear dns cache for: com.vlingo.midas
D/ConnectivityService(  840): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  840): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/accuweather( 7351): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
D/EntConnectivity(  840): Not allowed due to - mEnabled false
D/ConnectivityService(  840): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  840): calling update connectivity
D/ConnectivityService(  840):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  840):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  840): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  840): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  840): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524290
D/ConnectivityService(  840):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  840):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  840): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  840): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  840): calling update connectivity
D/ConnectivityService(  840):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  840):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  840): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  840): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524290
D/SmartBondingService(  840): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  840): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  840): getSBEnabled() enabled =false
V/NetworkStats(  840): updateIfacesLocked()
D/NtpTrustedTime(  840): currentTimeMillis() cache hit
V/NetworkStats(  840): performPollLocked(flags=0x1)
D/SmartBondingService(  840): getSBEnabled() enabled =false
D/SmartBondingService(  840): getSBEnabled() enabled =false
D/NetworkStatsFactory(  840): UpdateStatsForKnox
D/ConnectivityService(  840): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  840): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  840): currentTimeMillis() cache hit
V/NetworkStats(  840): performPollLocked() took 2ms
D/StatusBar.NetworkController( 1168): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1168): updateDataNetType()
D/StatusBar.NetworkController( 1168): NoService, mRoamingIconId = 0
D/NtpTrustedTime(  840): currentTimeMillis() cache hit
D/NtpTrustedTime(  840): currentTimeMillis() cache hit
D/NtpTrustedTime(  840): currentTimeMillis() cache hit
V/NetworkStats(  840): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  840): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1168): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1168): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1168): updateDataNetType()
D/StatusBar.NetworkController( 1168): NoService, mRoamingIconId = 0
D/NtpTrustedTime(  840): currentTimeMillis() cache hit
D/NtpTrustedTime(  840): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1168): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/daemonapp( 1317): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7351): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
D/daemonapp( 1317): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
W/libprocessgroup(  840): failed to open /acct/uid_10033/pid_6923/cgroup.procs: No such file or directory
D/accuweather( 7351): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
D/accuweather( 7351): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7907): MountEmulatedStorage()
E/Zygote  ( 7907): v2
I/libpersona( 7907): KNOX_SDCARD checking this for 1000
I/libpersona( 7907): KNOX_SDCARD not a persona
I/ActivityManager(  840): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7907 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7907): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7907): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7907): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7907): TimaSignature is unavailable
,D/ActivityThread( 7907): Added TimaKeyStore provider
,D/ResourcesManager( 7907): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7907): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7907): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7907): premStatus:2
,I/KnoxUsageLogPro( 7907): isEulaShown : false
I/KnoxUsageLogPro( 7907): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7922): MountEmulatedStorage()
E/Zygote  ( 7922): v2
I/libpersona( 7922): KNOX_SDCARD checking this for 10086
I/libpersona( 7922): KNOX_SDCARD not a persona
,I/ActivityManager(  840): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.NetStateReceiver: pid=7922 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  840): Killing 6903:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,I/SELinux ( 7922): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7922): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7922): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7922): TimaSignature is unavailable
,D/ActivityThread( 7922): Added TimaKeyStore provider
,D/ResourcesManager( 7922): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7922): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  840): failed to open /acct/uid_10099/pid_6903/cgroup.procs: No such file or directory
,D/PushModule( 7922): [PushClientApplication] (main) PushClientApplication.onCreate()
,I/PushModule( 7922): [PushClientApplication] (main) PushModule version: 0.9.01.12
,D/PushModule( 7922): [PushClientApplication] (main) Discovered public push client. disable in app push client.
,D/ChatON  ( 7922): [1][isApplicationInstalled] com.android.mms was installed
,W/ContextImpl( 7922): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
,W/ActivityManager(  840): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,D/ChatON  ( 7922): [1][a] ChatONV isn't installed.
,D/ChatON  ( 7922): [1][a] ChatONVPlugIn.isAvailable()
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7941): MountEmulatedStorage()
E/Zygote  ( 7941): v2
I/libpersona( 7941): KNOX_SDCARD checking this for 10088
I/libpersona( 7941): KNOX_SDCARD not a persona
,I/ActivityManager(  840): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7941 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  840): Killing 6963:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,I/SELinux ( 7941): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7941): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SMD     (  282): DCD ON
,E/SELinux ( 7941): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,E/Watchdog(  840): !@Sync 3
,D/TimaKeyStoreProvider( 7941): TimaSignature is unavailable
,D/ActivityThread( 7941): Added TimaKeyStore provider
,D/ResourcesManager( 7941): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  840): failed to open /acct/uid_10003/pid_6963/cgroup.procs: No such file or directory
,D/ConnectivityService(  840): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  840): MasterInitialState.processMessage what=3
,D/SmartBondingService(  840): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  840): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  840): SmartBondingReceiver: wifi ap is not changed
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  840): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  840): getSBEnabled() enabled =false
D/SmartBondingService(  840): getSBEnabled() enabled =false
D/SmartBondingService(  840): getSBEnabled() enabled =false
,I/CLocInfoService(  840): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  840): CLocinfo wifi true 
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  840): getNetworkEnabled : wifi : true mobile : true
,W/ContextImpl( 2195): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2195): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/accuweather( 2081): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5370): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7143): [#DCM#] [DCM_Performance] onReceive completed in time  1134 microsec. 
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3796): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 3796): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7143): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7143): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7143): [#DCM#] setIsConnectedForExtractors 
,I/ActivityManager(  840): Killing 6978:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Headlines( 5520): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/HeadlinesChannelUtil( 5520): getCountryCode(): countryCode = DE
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  840): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7961 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 7961): MountEmulatedStorage()
,E/Zygote  ( 7961): v2
I/libpersona( 7961): KNOX_SDCARD checking this for 10128
I/libpersona( 7961): KNOX_SDCARD not a persona
,I/DatabaseRebuilderTask( 7143): [#DCM#] postDBrebuildIntent rebuildLocation =  true
,D/Headlines( 5520): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,I/art     (  314): Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 273us total 15.070ms
,D/HeadlinesCardManager( 5520): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5520): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5520): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5520): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5520): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5520): requestUpdateNewsWelcomeCard !!! no welcome card
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.619ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 7.865ms
,I/SELinux ( 7961): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7961): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7961): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FrameworkService( 7143): [#DCM#] onCreate FrameworkService 
,I/FrameworkService( 7143): [#DCM#] onCreate FrameworkService end 
I/DCMConfig( 7143): [#DCM#] getSuccessState = true
,I/FrameworkService( 7143): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
I/IntentHandler( 7143): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,W/libprocessgroup(  840): failed to open /acct/uid_10020/pid_6978/cgroup.procs: No such file or directory
,I/SystemUtils( 7143): [#DCM#] LM: false,AM:707461120
,D/TimaKeyStoreProvider( 7961): TimaSignature is unavailable
,D/ActivityThread( 7961): Added TimaKeyStore provider
,I/art     (  840): Explicit concurrent mark sweep GC freed 77137(4MB) AllocSpace objects, 14(354KB) LOS objects, 30% free, 36MB/52MB, paused 1.324ms total 94.975ms
,D/SecContentProvider2(  840): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  840): mCursor = null
,I/DCMThreadPoolExecutor( 7143): [#DCM#] Task being added DatabaseRebuilderTask
,I/DCMThreadPoolExecutor( 7143): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@130a4652 is submitted
I/FrameworkService( 7143): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 107017 mirosec. 
,I/DatabaseRebuilderTask( 7143): [#DCM#] createLuceneReader done 
,D/ResourcesManager( 7961): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/DatabaseRebuilderTask( 7143): [#DCM#] resyncLocation   
I/DatabaseRebuilderTask( 7143): [#DCM#] resyncLocation: querying only for documents with deleted = 0 
,I/DatabaseRebuilderTask( 7143): [#DCM#] topDocs hits = 0
I/DatabaseRebuilderTask( 7143): [#DCM#] No of Location data to be added:  0
,I/DatabaseRebuilderTask( 7143): [#DCM#] releaseLuceneReader done 
I/DatabaseRebuilderTask( 7143): [#DCM#] Starting media manager do operation 
,I/SystemUtils( 7143): [#DCM#] setHeavySharedPref set as  false
,I/IntentHandler( 7143): [#DCM#] Stopping service with ids up to  1
,I/DCMThreadPoolExecutor( 7143): [#DCM#] afterExecute FutureTask
I/DCMController( 7143): [#DCM#] task finished =  com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@130a4652
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7961): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7961): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7961): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7961): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/WebViewFactory( 7961): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7961): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7961): Loading: webviewchromium
,I/LibraryLoader( 7961): Time to load native libraries: 4 ms (timestamps 4041-4045)
,I/LibraryLoader( 7961): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7961): Binding Chromium to main looper Looper (main, tid 1) {7dd1afe}
,I/LibraryLoader( 7961): Expected native library version number "",actual native library version number ""
,I/chromium( 7961): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7961): Initializing chromium process, renderers=0
,W/art     ( 7961): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7961): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7961): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7961): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7961): Requires BLUETOOTH permission
,I/Choreographer( 7562): Skipped 206 frames!  The application may be doing too much work on its main thread.
,I/Adreno-EGL( 7961): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7961): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7961): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7961): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7961): Remote Branch: 
I/Adreno-EGL( 7961): Local Patches: 
I/Adreno-EGL( 7961): Reconstruct Branch: 
,I/chromium( 7562): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 7562): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/NSApplication( 7961): Starting up...
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8023): MountEmulatedStorage()
,E/Zygote  ( 8023): v2
I/libpersona( 8023): KNOX_SDCARD checking this for 10138
I/libpersona( 8023): KNOX_SDCARD not a persona
,I/ActivityManager(  840): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=8023 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  840): Killing 6989:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,I/SELinux ( 8023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8023): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8023): TimaSignature is unavailable
,D/ActivityThread( 8023): Added TimaKeyStore provider
,D/ResourcesManager( 8023): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,E/WifiStateMachine(  840): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  840): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  840): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  840): identical MTU - not setting
D/ConnectivityService(  840): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  840): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
E/WifiStateMachine(  840): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
V/        (  277): QcRouteController
D/SmartBondingService(  840): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
W/libprocessgroup(  840): failed to open /acct/uid_1000/pid_6989/cgroup.procs: No such file or directory
D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  840): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  840): getSBEnabled() enabled =false
D/SmartBondingService(  840): getSBEnabled() enabled =false
D/SmartBondingService(  840): getSBEnabled() enabled =false
,W/ResourcesManager( 8023): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8023): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 8023): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,V/        (  277): QcRouteController
,W/NetworkManagementService(  840): route cmd failed: 
W/NetworkManagementService(  840): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  840): '
W/NetworkManagementService(  840): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  840): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  840): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  840): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  840): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  840): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  840): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  840): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  840): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  840): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  840): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  840): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  840): calling update connectivity
D/ConnectivityService(  840):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  840):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  840): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  840): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  840): calling update connectivity
D/ConnectivityService(  840):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  840):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524295
,D/ConnectivityService(  840): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524295
,D/QuickConnect( 8023): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8023): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 8023): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8040): MountEmulatedStorage()
E/Zygote  ( 8040): v2
I/libpersona( 8040): KNOX_SDCARD checking this for 10163
I/libpersona( 8040): KNOX_SDCARD not a persona
,I/ActivityManager(  840): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=8040 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  840): Killing 7014:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,I/SELinux ( 8040): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8040): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8040): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  840): failed to open /acct/uid_10112/pid_7014/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8040): TimaSignature is unavailable
,D/ActivityThread( 8040): Added TimaKeyStore provider
,D/ResourcesManager( 8040): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8040): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8040): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8040): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8040): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManagerService(  840): exchangeData() failure , invalid userId
,D/RCPManagerService(  840): exchangeData() failure , invalid userId
,D/RCPManagerService(  840): exchangeData() failure , invalid userId
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  840): exchangeData() failure , invalid userId
,E/Zygote  ( 8066): MountEmulatedStorage()
,E/Zygote  ( 8066): v2
I/libpersona( 8066): KNOX_SDCARD checking this for 10078
I/libpersona( 8066): KNOX_SDCARD not a persona
I/ActivityManager(  840): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8066 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/SELinux ( 8066): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SELinux ( 8066): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/ConnectivityService(  840): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/SELinux ( 8066): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/RCPManagerService(  840): exchangeData() failure , invalid userId
V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/RCPManagerService(  840): exchangeData() failure , invalid userId
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,D/TimaKeyStoreProvider( 8066): TimaSignature is unavailable
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,D/ActivityThread( 8066): Added TimaKeyStore provider
V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/ActivityManager(  840): Killing 7033:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7621): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7621): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7621): StateMachine : Current State = 1
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7621): StateMachine : Changed Current State = 1
,D/ResourcesManager( 8066): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,I/ActivityManager(  840): Killing 7049:com.samsung.helphub/1000 (adj 15): bgCount ##41
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,D/com.peel.receiver.ConnectivityActionReceiver( 5625): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): last run: 1452855545076 -- System.currentTimeMillis()-last_run: 7332801
D/com.peel.receiver.ConnectivityActionReceiver( 5625): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): ... skip last_72_check
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 8066): onCreate
D/BadgeProvider( 8066): DatabaseHelper
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,E/Zygote  ( 8087): MountEmulatedStorage()
I/libpersona( 8087): KNOX_SDCARD checking this for 10178
E/Zygote  ( 8087): v2
I/libpersona( 8087): KNOX_SDCARD not a persona
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,I/ActivityManager(  840): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8087 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,I/SELinux ( 8087): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  840): failed to open /acct/uid_10118/pid_7033/cgroup.procs: No such file or directory
,W/libprocessgroup(  840): failed to open /acct/uid_1000/pid_7049/cgroup.procs: No such file or directory
,I/SELinux ( 8087): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8087): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,D/BadgeProvider( 8066): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,D/BadgeProvider( 8066): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8066): sendNotify, [notify] : null
D/BadgeProvider( 8066): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8066): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 8066): update, [UpdateCount] : 1
D/Launcher.Model( 1488): reloadBadges entered.
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,D/TimaKeyStoreProvider( 8087): TimaSignature is unavailable
,D/ActivityThread( 8087): Added TimaKeyStore provider
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,D/ResourcesManager( 8087): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  840): Killing 7085:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 8040): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2472): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/libprocessgroup(  840): failed to open /acct/uid_10166/pid_7085/cgroup.procs: No such file or directory
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2472): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7120): notifyNetworkActivated
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,W/ContextImpl( 7120): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,W/ActivityManager(  840): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
D/SecContentProvider2(  840): mCursor = null
,D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2472): [AccountUtils] Account not ready
W/Kids    ( 2472): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2472): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2472): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2472): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2472): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2472): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2472): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2472): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2472): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2472): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2472): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2472): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,W/ActivityManager(  840): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/hcjo    ( 7120): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7120): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7120): exit::IDLE
D/InitializeManagerStateMachine( 7120): entry::NETWORK_CHECK
,I/Hs20UtilService( 1359): Starting #8
,I/Hs20UtilService( 1359): Message received 5007
,D/NearbySettings( 1359): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1359): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1359): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  840): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1359): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1359): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1359): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7120): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7120): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7120): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7120): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,I/Hs20UtilService( 1359): Starting #9
,D/InitializeManagerStateMachine( 7120): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7120): entry::SUCCESS
D/hcjo    ( 7120): AutoUpdateManager:INITCHECK:onInitializeSuccess
I/Hs20UtilService( 1359): Message received 5007
,D/NearbySettings( 1359): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1359): MountReceiver.onReceive - Keep current state
D/hcjo    ( 7120): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7120): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7120): exit::SUCCESS
D/InitializeManagerStateMachine( 7120): entry::IDLE
,I/Hs20UtilService( 1359): Starting #10
,I/Hs20UtilService( 1359): Message received 5007
,D/NearbySettings( 1359): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1359): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1359): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1359): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1359): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1359): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1359): Starting #11
,I/Hs20UtilService( 1359): Message received 5007
,D/NearbySettings( 1359): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1359): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  840): callSECApi what=220
D/WifiStateMachine(  840): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 7690): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7690): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7690): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7690): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7733): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7733): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PowerManagerService(  840): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=840
,D/DisplayPowerController(  840): getFinalBrightness : 34 -> 34
,D/PowerManagerService(  840): [s] DisplayPowerCallbacks : onStateChanged()
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/lights  (  840): lcd : 22 +
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/lights  (  840): lcd : 22 -
,D/lights  (  840): lcd : 30 +
,D/lights  (  840): lcd : 30 -
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/FOTA_Client( 7752): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/DisplayPowerController(  840): getFinalBrightness : 34 -> 34
,D/lights  (  840): lcd : 34 +
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/FOTA_Client( 7752): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7752): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7752): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7752): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7768): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/lights  (  840): lcd : 34 -
,D/DisplayPowerController(  840): getFinalBrightness : 34 -> 34
I/KLMS-2.4.503: ( 7768): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452862878329
,I/KLMS-2.4.503: ( 7768): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7768): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7768): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7768): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7768): StateImplV2(): networkChangeListener().END
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SO_AGENT( 7783): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore in!
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  840): CMD_RSSI_POLL : out!
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7832): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 7866): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7866): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7866): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7866): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7866): [OR] == isSIMCardReady false ==
D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7866): [SCU] == networkStateCheck == true
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SA      ( 7866): [DM] getCountryCodeFromCSC : DE
,I/SA      ( 7866): isChinaCountryCode : false
,I/SA      ( 7866): [SCU] is ChinestModel Data Restricted   : false
,I/SA      ( 7866): [OR] == networkStateCheck true ==
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
I/SA      ( 7866): [OR] GetMyCountryZoneTask
,I/SA      ( 7866): [OR] onReceive END
,I/SA      ( 7866): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7866): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7866): [SSP] query invoked
,D/accuweather( 7351): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7351): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro( 7907): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7907): premStatus:2
,I/KnoxUsageLogPro( 7907): isEulaShown : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
I/KnoxUsageLogPro( 7907): KnoxUsageReceiver onReceive : not Processible, just return
D/LockPatternUtilsCache( 1168): value : false
,I/SA      ( 7866): [TPMU] GetMccFromDB : null
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SA      ( 7866): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7866): [TPM] isNoProxy(default) : true
,D/Headlines( 5520): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5520): getCountryCode(): countryCode = DE
,D/Headlines( 5520): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5520): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5520): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5520): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5520): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5520): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5520): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 8023): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8023): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 8023): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  840): exchangeData() failure , invalid userId
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/RCPManagerService(  840): exchangeData() failure , invalid userId
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7621): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7621): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7621): StateMachine : Current State = 1
D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7621): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 5625): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): last run: 1452855545076 -- System.currentTimeMillis()-last_run: 7333421
D/com.peel.receiver.ConnectivityActionReceiver( 5625): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): ... skip last_72_check
,E/File    ( 7866): fail readDirectory() errno=2
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ChimeraCfgMgr( 2472): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7120): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7120): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7120): exit::IDLE
D/InitializeManagerStateMachine( 7120): entry::NETWORK_CHECK
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ConnectivityService(  840): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7120): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7120): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7120): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7120): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7120): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7120): entry::SUCCESS
D/hcjo    ( 7120): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7120): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7120): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7120): exit::SUCCESS
,D/InitializeManagerStateMachine( 7120): entry::IDLE
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
D/SecContentProvider2(  840): mCursor = null
,D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/Kids    ( 2472): [AccountUtils] Account not ready
W/Kids    ( 2472): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2472): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2472): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2472): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2472): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2472): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2472): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2472): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2472): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2472): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2472): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2472): 	at java.lang.Thread.run(Thread.java:818)
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,V/AlarmManager(  840): waitForAlarm result :4
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7866): [RC New] Execute method=[GET] start
,I/SA      ( 7866): [RC New] Security=[true]
,I/System.out( 7866): Thread-1310(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7866): Thread-1310(ApacheHTTPLog):isShipBuild true
,I/System.out( 7866): Thread-1310(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1676): Connected
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1676): Message class com.google.f.a.a.p
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WifiStateMachine(  840): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  840): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/SMD     (  282): DCD ON
,I/SA      ( 7866): [RC New] [v2liruge] api execute + 631
,I/SA      ( 7866): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 7866): AsyncTask #1 calls detatch()
,I/SA      ( 7866): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 7866): [OCP] update openData : PL
,I/SA      ( 7866): [TPMU] getNetworkMcc : 
,I/SA      ( 7866): [SCU] saveMccToPreferece Start
,I/SA      ( 7866): [SCU] RegionMCC : 260
I/SA      ( 7866): [SSP] query invoked
,I/SA      ( 7866): [TPMU] GetMccFromDB : null
,I/SA      ( 7866): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7866): [SCU] saveMccToPreferece End
I/SA      ( 7866): [RC New] executeRequest [v2liruge] end. 697
I/SA      ( 7866): [RC New] Execute end
,I/SA      ( 7866): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7866): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  ( 7803): wlan0: sending IPv6 Router Solicitation
,D/PackageManager(  840): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager(  840): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 1488): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,E/Zygote  ( 8138): MountEmulatedStorage()
E/Zygote  ( 8138): v2
I/libpersona( 8138): KNOX_SDCARD checking this for 10034
I/libpersona( 8138): KNOX_SDCARD not a persona
,D/ResourcesManager(  840): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/ActivityManager(  840): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8138 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/InputReader(  840): Reconfiguring input devices.  changes=0x00000010
,W/ResourcesManager( 1488): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1488): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1488): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  840): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/SELinux ( 8138): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8138): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8138): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager( 1488): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/RegisteredServicesCache( 1468): empty dynamic service
,W/ResourcesManager( 1488): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1488): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 8138): TimaSignature is unavailable
,W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityThread( 8138): Added TimaKeyStore provider
D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,V/AlarmManager(  840): waitForAlarm result :8
,D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/SecContentProvider2(  840): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  840): mCursor = null
,D/ResourcesManager( 8138): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4351, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,I/FeatureConfig( 8138): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager(  840): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService(  840): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,D/ResourcesManager(  840): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  840): Plugged
I/MotionRecognitionService(  840): setPowerConnected  = true
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 1676): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_google_search.png
,D/ResourcesManager(  840): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Search.LoginHelper( 1554): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,D/ResourcesManager(  840): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,D/ResourcesManager(  840): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  840): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  840): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  840): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  840): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 8138): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8138): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8138): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8138): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8138): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/Atfwd_Sendcmd(  341): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  341): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/ResourcesManager( 8138): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 8138): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 8138): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 8138): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8138): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 8138): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8138): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 8138): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 8138): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8138): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8138): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 8138): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.,
W/ResourcesManager( 8138): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8138): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8138): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8138): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8138): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 8138): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8138): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 8138): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8138): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8138): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8138): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8138): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8138): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 8138): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8138): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8138): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8138): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8138): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8138): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 8138): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 8138): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 8138): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 8138): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 8138): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8138): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 8138): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8173): MountEmulatedStorage()
E/Zygote  ( 8173): v2
I/libpersona( 8173): KNOX_SDCARD checking this for 10035
I/libpersona( 8173): KNOX_SDCARD not a persona
,I/ActivityManager(  840): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=8173 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  840): Killing 6643:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,I/SELinux ( 8173): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8173): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8173): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8173): TimaSignature is unavailable
,D/ActivityThread( 8173): Added TimaKeyStore provider
,D/ResourcesManager( 8173): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/libprocessgroup(  840): failed to open /acct/uid_10012/pid_6643/cgroup.procs: No such file or directory
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): checkState() : APP TYPE = Full
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8194): MountEmulatedStorage()
E/Zygote  ( 8194): v2
I/libpersona( 8194): KNOX_SDCARD checking this for 10017
I/libpersona( 8194): KNOX_SDCARD not a persona
,I/ActivityManager(  840): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=8194 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,I/SELinux ( 8194): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8194): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8194): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8194): TimaSignature is unavailable
,D/ActivityThread( 8194): Added TimaKeyStore provider
,D/ResourcesManager( 8194): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/BluetoothManager( 8173): getConnectedDevices
,I/SecureStorage( 8194): [INFO]: SPID(0x00000000)Processing data
,D/-----SIC-----( 8173): ------------------skip uv
,D/-----SIC-----( 8173): ------------------skip SPO2
,D/-----SIC-----( 8173): ------------------skip TGH
,I/SecureStorage(  358): [INFO]: SPID(0x00000005)Credentials: uid 10017, gid 10017, pid 8194
I/SecureStorage(  358): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8173): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8173): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,V/MediaPlayer( 8173): decode(33, 19359868, 4230)
,V/MediaPlayerService(  287): decode(30, 19359868, 4230)
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore in!
,V/MediaPlayerService(  287): player type = 3
V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): constructor
I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  840): CMD_RSSI_POLL : out!
,V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): StagefrightPlayer
V/AwesomePlayer(  287): setListener
V/StagefrightPlayer(  287): initCheck
V/AwesomePlayer(  287): setAudioSink
V/StagefrightPlayer(  287): setDataSource(30, 19359868, 4230)
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb061b3d0, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
D/Utils   (  287): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  287): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  287): mBitrate = -1 bits/sec
I/OggExtractor(  287): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  287): current audio track index (0) is added to vector
V/AwesomePlayer(  287): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  287): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  287): prepare
,V/AwesomePlayer(  287): prepareAsync
,V/MediaPlayerService(  287): wait for prepare
V/AwesomePlayer(  287): onPrepareAsyncEvent
I/SecMediaClock(  287): SecMediaClock constructor
I/SecMediaClock(  287): reset
I/SecVideoCapture(  287): SecVideoCapture constructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): initAudioDecoder
V/AwesomePlayer(  287): checkOffloadExceptions is true
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/OMXCodec(  287): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  287): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  287): finishAsyncPrepare_l
V/AwesomePlayer(  287): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  287): notify(0xb061b3d0, 200, 973, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb061b3d0, 5, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb061b3d0, 1, 0, 0)
V/AudioCache(  287): prepared
V/AudioCache(  287): wait - success
V/MediaPlayerService(  287): start
V/StagefrightPlayer(  287): start
V/AwesomePlayer(  287): play
V/AwesomePlayer(  287): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  287): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  287): start of Playback, useOffload 0
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  287): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  287): Audio channels(1)
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  287): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  287): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb061b3d0, 6, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): addBatteryData
I/AudioPlayer(  287): First fillBuffer call!!
V/MediaPlayerService(  287): wait for playback complete
,V/AwesomePlayer(  287): postAudioEOS delayUs (0)
V/AwesomePlayer(  287): onCheckAudioStatus
V/AwesomePlayer(  287): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  287): onStreamDone
V/AwesomePlayer(  287): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  287): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb061b3d0, 2, 0, 0)
V/AudioCache(  287): playback complete - thread will wake up later
V/AwesomePlayer(  287): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb061b3d0, 7, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  287): addBatteryData
V/AudioCache(  287): wait - success
V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb061b3d0, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
D/AudioPlayer(  287): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop() sendCommand(0x74, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  287): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  287): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  287): ~OggSource --
I/OggExtractor(  287): ~OggExtractor ++
I/OggExtractor(  287): ~MyVorbisExtractor ++ 
I/OggExtractor(  287): ~MyVorbisExtractor --
I/OggExtractor(  287): ~OggExtractor --
,I/AudioPlayer(  287): reset out
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  287): SecVideoCapture destructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): mSecCapture clear
I/SecMediaClock(  287): SecMediaClock destructor
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): ~StagefrightPlayer
V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/AwesomePlayer(  287): destructor
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/MediaPlayer( 8173): decode(37, 19213040, 15440)
V/MediaPlayerService(  287): decode(30, 19213040, 15440)
,V/MediaPlayerService(  287): player type = 3
,V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): constructor
V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): StagefrightPlayer
V/AwesomePlayer(  287): setListener
,V/StagefrightPlayer(  287): initCheck
V/AwesomePlayer(  287): setAudioSink
V/StagefrightPlayer(  287): setDataSource(30, 19213040, 15440)
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54060, 8, 0, 0)
,V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
,D/Utils   (  287): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  287): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  287): mBitrate = -1 bits/sec
,I/OggExtractor(  287): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  287): current audio track index (0) is added to vector
V/AwesomePlayer(  287): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  287): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  287): prepare
V/AwesomePlayer(  287): prepareAsync
,V/MediaPlayerService(  287): wait for prepare
,V/AwesomePlayer(  287): onPrepareAsyncEvent
I/SecMediaClock(  287): SecMediaClock constructor
I/SecMediaClock(  287): reset
I/SecVideoCapture(  287): SecVideoCapture constructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): initAudioDecoder
V/AwesomePlayer(  287): checkOffloadExceptions is true
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthServiceInstalled() : HealthService is Installed.
,I/OMXCodec(  287): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  287): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  287): finishAsyncPrepare_l
V/AwesomePlayer(  287): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  287): notify(0xb0b54060, 200, 973, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54060, 5, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54060, 1, 0, 0)
V/AudioCache(  287): prepared
V/AudioCache(  287): wait - success
V/MediaPlayerService(  287): start
V/StagefrightPlayer(  287): start
V/AwesomePlayer(  287): play
V/AwesomePlayer(  287): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  287): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  287): start of Playback, useOffload 0
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  287): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  287): Audio channels(2)
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  287): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  287): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54060, 6, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): addBatteryData
,V/MediaPlayerService(  287): wait for playback complete
I/AudioPlayer(  287): First fillBuffer call!!
I/AudioPlayer(  287): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  287): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/ActivityManager(  840): Killing 7100:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): bgCount ##41
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  287): postAudioEOS delayUs (0)
,V/AwesomePlayer(  287): onCheckAudioStatus
V/AwesomePlayer(  287): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  287): onStreamDone
V/AwesomePlayer(  287): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  287): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
,V/AudioCache(  287): notify(0xb0b54060, 2, 0, 0)
V/AudioCache(  287): playback complete - thread will wake up later
V/AwesomePlayer(  287): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54060, 7, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  287): addBatteryData
V/AudioCache(  287): wait - success
V/StagefrightPlayer(  287): reset
,V/AwesomePlayer(  287): reset_l()
,V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54060, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
D/AudioPlayer(  287): reset: mPlaying=0 mReachedEOS=1 useOffload=0
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop() sendCommand(0x75, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
D/AdaptiveEventManager( 1168): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1168): M updateContainers()
D/AdaptiveEventContainerSmall( 1168): C updatePedoContainer()
I/UpdateIcingCorporaServi( 1554): Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
D/AdaptiveEventContainerSmall( 1168): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1168): pedoEvent == null
I/OggExtractor(  287): OggSource::stop() mExtractor ref count = 1
,I/OggExtractor(  287): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  287): ~OggSource --
I/OggExtractor(  287): ~OggExtractor ++
I/OggExtractor(  287): ~MyVorbisExtractor ++ 
I/OggExtractor(  287): ~MyVorbisExtractor --
I/OggExtractor(  287): ~OggExtractor --
,D/AdaptiveEventManager( 1168): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1168): M updateContainers()
D/AdaptiveEventContainerSmall( 1168): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1168): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1168): pedoEvent == null
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,I/AudioPlayer(  287): reset out
,V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
,I/SecVideoCapture(  287): SecVideoCapture destructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): mSecCapture clear
,I/SecMediaClock(  287): SecMediaClock destructor
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): ~StagefrightPlayer
V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): reset_l()
,V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/AwesomePlayer(  287): destructor
,V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
,V/MediaPlayer( 8173): decode(35, 19257568, 9226)
V/MediaPlayerService(  287): decode(30, 19257568, 9226)
,V/MediaPlayerService(  287): player type = 3
V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): constructor
,V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): StagefrightPlayer
V/AwesomePlayer(  287): setListener
V/StagefrightPlayer(  287): initCheck
V/AwesomePlayer(  287): setAudioSink
V/StagefrightPlayer(  287): setDataSource(30, 19257568, 9226)
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0a24ec0, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
D/Utils   (  287): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  287): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  287): mBitrate = -1 bits/sec
I/OggExtractor(  287): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  287): current audio track index (0) is added to vector
V/AwesomePlayer(  287): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  287): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  287): prepare
V/AwesomePlayer(  287): prepareAsync
V/MediaPlayerService(  287): wait for prepare
,V/AwesomePlayer(  287): onPrepareAsyncEvent
I/SecMediaClock(  287): SecMediaClock constructor
E/Zygote  ( 8242): MountEmulatedStorage()
E/Zygote  ( 8242): v2
I/libpersona( 8242): KNOX_SDCARD checking this for 10075
I/libpersona( 8242): KNOX_SDCARD not a persona
,I/SecMediaClock(  287): reset
I/SecVideoCapture(  287): SecVideoCapture constructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): initAudioDecoder
,V/AwesomePlayer(  287): checkOffloadExceptions is true
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  287): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/ActivityManager(  840): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=8242 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/OMXCodec(  287): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  287): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/SELinux ( 8242): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8242): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8242): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  287): finishAsyncPrepare_l
V/AwesomePlayer(  287): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache(  287): notify(0xb0a24ec0, 200, 973, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0a24ec0, 5, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0a24ec0, 1, 0, 0)
,V/AudioCache(  287): prepared
V/AudioCache(  287): wait - success
V/MediaPlayerService(  287): start
V/StagefrightPlayer(  287): start
V/AwesomePlayer(  287): play
V/AwesomePlayer(  287): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  287): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  287): start of Playback, useOffload 0
,W/libprocessgroup(  840): failed to open /acct/uid_10170/pid_7100/cgroup.procs: No such file or directory
,I/ActivityManager(  840): Killing 6234:com.google.android.gm/u0a114 (adj 15): bgCount ##41
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  287): Audio channels(2)
,I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  287): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  287): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  287): notify(0xb0a24ec0, 6, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): addBatteryData
I/AudioPlayer(  287): First fillBuffer call!!
,V/MediaPlayerService(  287): wait for playback complete
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  287): postAudioEOS delayUs (0)
,E/DatabaseUtils(  840): Writing exception to parcel
E/DatabaseUtils(  840): java.lang.NullPointerException: key == null
E/DatabaseUtils(  840): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils(  840): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils(  840): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils(  840): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/DatabaseUtils(  840): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils(  840): 	at android.os.Binder.execTransact(Binder.java:446)
,V/AwesomePlayer(  287): onCheckAudioStatus
V/AwesomePlayer(  287): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  287): onStreamDone
V/AwesomePlayer(  287): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  287): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0a24ec0, 2, 0, 0)
V/AudioCache(  287): playback complete - thread will wake up later
,V/AwesomePlayer(  287): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0a24ec0, 7, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  287): addBatteryData
V/AudioCache(  287): wait - success
V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0a24ec0, 8, 0, 0)
,V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
D/AudioPlayer(  287): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop() sendCommand(0x76, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  287): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  287): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  287): ~OggSource --
I/OggExtractor(  287): ~OggExtractor ++
,I/OggExtractor(  287): ~MyVorbisExtractor ++ 
I/OggExtractor(  287): ~MyVorbisExtractor --
I/OggExtractor(  287): ~OggExtractor --
,D/TimaKeyStoreProvider( 8242): TimaSignature is unavailable
I/AudioPlayer(  287): reset out
,V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  287): SecVideoCapture destructor
I/SecVideoCapture(  287): reset
D/ActivityThread( 8242): Added TimaKeyStore provider
V/AwesomePlayer(  287): mSecCapture clear
I/SecMediaClock(  287): SecMediaClock destructor
V/AwesomePlayer(  287): mSecMediaClock clear
,V/StagefrightPlayer(  287): ~StagefrightPlayer
V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/AwesomePlayer(  287): destructor
,V/AwesomePlayer(  287): reset_l()
,V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/MediaPlayer( 8173): decode(36, 19364180, 4890)
,V/MediaPlayerService(  287): decode(31, 19364180, 4890)
,V/MediaPlayerService(  287): player type = 3
,V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): constructor
V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): reset_l()
,V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
,V/StagefrightPlayer(  287): StagefrightPlayer
V/AwesomePlayer(  287): setListener
V/StagefrightPlayer(  287): initCheck
V/AwesomePlayer(  287): setAudioSink
V/StagefrightPlayer(  287): setDataSource(31, 19364180, 4890)
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  287): notify(0xb0b54560, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
,V/AwesomePlayer(  287): mSecMediaClock clear
D/Utils   (  287): printFileName fd(29) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  287): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  287): mBitrate = -1 bits/sec
I/OggExtractor(  287): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  287): current audio track index (0) is added to vector
V/AwesomePlayer(  287): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  287): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  287): prepare
V/AwesomePlayer(  287): prepareAsync
,V/MediaPlayerService(  287): wait for prepare
,V/AwesomePlayer(  287): onPrepareAsyncEvent
I/SecMediaClock(  287): SecMediaClock constructor
I/SecMediaClock(  287): reset
I/SecVideoCapture(  287): SecVideoCapture constructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): initAudioDecoder
V/AwesomePlayer(  287): checkOffloadExceptions is true
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/UpdateIcingCorporaServi( 1554): UpdateCorporaTask done [took 64 ms] updated apps [took 64 ms] 
,I/OMXCodec(  287): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
,I/AwesomePlayer(  287): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  287): finishAsyncPrepare_l
V/AwesomePlayer(  287): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  287): notify(0xb0b54560, 200, 973, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54560, 5, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54560, 1, 0, 0)
V/AudioCache(  287): prepared
V/AudioCache(  287): wait - success
V/MediaPlayerService(  287): start
V/StagefrightPlayer(  287): start
V/AwesomePlayer(  287): play
V/AwesomePlayer(  287): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  287): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  287): start of Playback, useOffload 0
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  287): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  287): Audio channels(1)
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  287): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  287): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54560, 6, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): addBatteryData
I/AudioPlayer(  287): First fillBuffer call!!
V/MediaPlayerService(  287): wait for playback complete
I/AudioPlayer(  287): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  287): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,D/ResourcesManager( 8242): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  287): postAudioEOS delayUs (0)
V/AwesomePlayer(  287): onCheckAudioStatus
V/AwesomePlayer(  287): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  287): onStreamDone
V/AwesomePlayer(  287): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  287): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54560, 2, 0, 0)
V/AudioCache(  287): playback complete - thread will wake up later
V/AwesomePlayer(  287): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54560, 7, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  287): addBatteryData
V/AudioCache(  287): wait - success
V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54560, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
D/AudioPlayer(  287): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop() sendCommand(0x77, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  287): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  287): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  287): ~OggSource --
I/OggExtractor(  287): ~OggExtractor ++
I/OggExtractor(  287): ~MyVorbisExtractor ++ 
I/OggExtractor(  287): ~MyVorbisExtractor --
I/OggExtractor(  287): ~OggExtractor --
,I/AudioPlayer(  287): reset out
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  287): SecVideoCapture destructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): mSecCapture clear
I/SecMediaClock(  287): SecMediaClock destructor
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): ~StagefrightPlayer
V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/AwesomePlayer(  287): destructor
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
,V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/MediaPlayer( 8173): decode(38, 19290344, 17329)
,V/MediaPlayerService(  287): decode(30, 19290344, 17329)
V/MediaPlayerService(  287): player type = 3
V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): constructor
V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): StagefrightPlayer
V/AwesomePlayer(  287): setListener
V/StagefrightPlayer(  287): initCheck
V/AwesomePlayer(  287): setAudioSink
V/StagefrightPlayer(  287): setDataSource(30, 19290344, 17329)
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xafa09290, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
D/Utils   (  287): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  287): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  287): mBitrate = -1 bits/sec
I/OggExtractor(  287): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  287): current audio track index (0) is added to vector
V/AwesomePlayer(  287): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  287): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  287): prepare
V/AwesomePlayer(  287): prepareAsync
V/MediaPlayerService(  287): wait for prepare
V/AwesomePlayer(  287): onPrepareAsyncEvent
I/SecMediaClock(  287): SecMediaClock constructor
I/SecMediaClock(  287): reset
I/SecVideoCapture(  287): SecVideoCapture constructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): initAudioDecoder
V/AwesomePlayer(  287): checkOffloadExceptions is true
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  287): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  287): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  287): finishAsyncPrepare_l
V/AwesomePlayer(  287): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  287): notify(0xafa09290, 200, 973, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xafa09290, 5, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xafa09290, 1, 0, 0)
V/AudioCache(  287): prepared
V/AudioCache(  287): wait - success
V/MediaPlayerService(  287): start
V/StagefrightPlayer(  287): start
V/AwesomePlayer(  287): play
V/AwesomePlayer(  287): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  287): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  287): start of Playback, useOffload 0
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  287): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  287): Audio channels(2)
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  287): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  287): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xafa09290, 6, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): addBatteryData
V/MediaPlayerService(  287): wait for playback complete
I/AudioPlayer(  287): First fillBuffer call!!
I/AudioPlayer(  287): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  287): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,D/FileShare-Server( 8242): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  287): postAudioEOS delayUs (0)
,V/AwesomePlayer(  287): onCheckAudioStatus
V/AwesomePlayer(  287): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  287): onStreamDone
V/AwesomePlayer(  287): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  287): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xafa09290, 2, 0, 0)
V/AudioCache(  287): playback complete - thread will wake up later
V/AwesomePlayer(  287): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xafa09290, 7, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  287): addBatteryData
V/AudioCache(  287): wait - success
V/StagefrightPlayer(  287): reset
,V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xafa09290, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
D/AudioPlayer(  287): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop() sendCommand(0x78, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  287): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  287): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  287): ~OggSource --
I/OggExtractor(  287): ~OggExtractor ++
I/OggExtractor(  287): ~MyVorbisExtractor ++ 
I/OggExtractor(  287): ~MyVorbisExtractor --
I/OggExtractor(  287): ~OggExtractor --
,I/AudioPlayer(  287): reset out
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  287): SecVideoCapture destructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): mSecCapture clear
I/SecMediaClock(  287): SecMediaClock destructor
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): ~StagefrightPlayer
V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/AwesomePlayer(  287): destructor
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/MediaPlayer( 8173): decode(39, 19190536, 6644)
V/MediaPlayerService(  287): decode(30, 19190536, 6644)
V/MediaPlayerService(  287): player type = 3
V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): constructor
,V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): StagefrightPlayer
V/AwesomePlayer(  287): setListener
V/StagefrightPlayer(  287): initCheck
V/AwesomePlayer(  287): setAudioSink
V/StagefrightPlayer(  287): setDataSource(30, 19190536, 6644)
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xaf7212e0, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
D/Utils   (  287): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  287): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  287): mBitrate = -1 bits/sec
I/OggExtractor(  287): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  287): current audio track index (0) is added to vector
V/AwesomePlayer(  287): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  287): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  287): prepare
V/AwesomePlayer(  287): prepareAsync
V/MediaPlayerService(  287): wait for prepare
,V/AwesomePlayer(  287): onPrepareAsyncEvent
I/SecMediaClock(  287): SecMediaClock constructor
I/SecMediaClock(  287): reset
I/SecVideoCapture(  287): SecVideoCapture constructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): initAudioDecoder
V/AwesomePlayer(  287): checkOffloadExceptions is true
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,I/OMXCodec(  287): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  287): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  287): finishAsyncPrepare_l
V/AwesomePlayer(  287): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  287): notify(0xaf7212e0, 200, 973, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xaf7212e0, 5, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache(  287): notify(0xaf7212e0, 1, 0, 0)
V/AudioCache(  287): prepared
V/AudioCache(  287): wait - success
V/MediaPlayerService(  287): start
V/StagefrightPlayer(  287): start
V/AwesomePlayer(  287): play
V/AwesomePlayer(  287): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  287): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  287): start of Playback, useOffload 0
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  287): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,E/Zygote  ( 8272): MountEmulatedStorage()
,E/Zygote  ( 8272): v2
I/libpersona( 8272): KNOX_SDCARD checking this for 1000
I/libpersona( 8272): KNOX_SDCARD not a persona
I/AudioPlayer(  287): Audio channels(1)
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  287): open(44100, 1, 0x0, 1, 0)
,I/ActivityManager(  840): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=8272 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
V/AwesomePlayer(  287): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xaf7212e0, 6, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): addBatteryData
,V/MediaPlayerService(  287): wait for playback complete
,I/ActivityManager(  840): Killing 7182:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##41
,I/art     (  840): Explicit concurrent mark sweep GC freed 53405(3MB) AllocSpace objects, 4(259KB) LOS objects, 30% free, 36MB/52MB, paused 3.672ms total 108.652ms
,I/AudioPlayer(  287): First fillBuffer call!!
I/SELinux ( 8272): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/AudioPlayer(  287): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
,I/SELinux ( 8272): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8272): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/AudioPlayer(  287): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,W/libprocessgroup(  840): failed to open /acct/uid_10114/pid_6234/cgroup.procs: No such file or directory
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  287): postAudioEOS delayUs (0)
V/AwesomePlayer(  287): onCheckAudioStatus
V/AwesomePlayer(  287): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  287): onStreamDone
V/AwesomePlayer(  287): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  287): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xaf7212e0, 2, 0, 0)
V/AudioCache(  287): playback complete - thread will wake up later
V/AwesomePlayer(  287): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xaf7212e0, 7, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  287): addBatteryData
V/AudioCache(  287): wait - success
V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xaf7212e0, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
D/AudioPlayer(  287): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop() sendCommand(0x79, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  287): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  287): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  287): ~OggSource --
I/OggExtractor(  287): ~OggExtractor ++
I/OggExtractor(  287): ~MyVorbisExtractor ++ 
I/OggExtractor(  287): ~MyVorbisExtractor --
I/OggExtractor(  287): ~OggExtractor --
,I/AudioPlayer(  287): reset out
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  287): SecVideoCapture destructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): mSecCapture clear
I/SecMediaClock(  287): SecMediaClock destructor
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): ~StagefrightPlayer
V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/AwesomePlayer(  287): destructor
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/MediaPlayer( 8173): decode(40, 19266876, 23389)
,V/MediaPlayerService(  287): decode(30, 19266876, 23389)
V/MediaPlayerService(  287): player type = 3
V/AwesomePlayer(  287): setDefault
,V/AwesomePlayer(  287): constructor
V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
,V/StagefrightPlayer(  287): StagefrightPlayer
V/AwesomePlayer(  287): setListener
V/StagefrightPlayer(  287): initCheck
V/AwesomePlayer(  287): setAudioSink
V/StagefrightPlayer(  287): setDataSource(30, 19266876, 23389)
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb061b3d0, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
D/Utils   (  287): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  287): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  287): mBitrate = -1 bits/sec
,I/OggExtractor(  287): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  287): current audio track index (0) is added to vector
V/AwesomePlayer(  287): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  287): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  287): prepare
V/AwesomePlayer(  287): prepareAsync
V/MediaPlayerService(  287): wait for prepare
V/AwesomePlayer(  287): onPrepareAsyncEvent
I/SecMediaClock(  287): SecMediaClock constructor
I/SecMediaClock(  287): reset
I/SecVideoCapture(  287): SecVideoCapture constructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): initAudioDecoder
V/AwesomePlayer(  287): checkOffloadExceptions is true
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  287): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  287): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  287): finishAsyncPrepare_l
V/AwesomePlayer(  287): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  287): notify(0xb061b3d0, 200, 973, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb061b3d0, 5, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb061b3d0, 1, 0, 0)
V/AudioCache(  287): prepared
V/AudioCache(  287): wait - success
V/MediaPlayerService(  287): start
V/StagefrightPlayer(  287): start
V/AwesomePlayer(  287): play
V/AwesomePlayer(  287): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  287): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  287): start of Playback, useOffload 0
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  287): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  287): Audio channels(2)
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  287): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  287): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb061b3d0, 6, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): addBatteryData
V/MediaPlayerService(  287): wait for playback complete
,I/AudioPlayer(  287): First fillBuffer call!!
I/AudioPlayer(  287): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  287): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  840): failed to open /acct/uid_10044/pid_7182/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8272): TimaSignature is unavailable
,D/ActivityThread( 8272): Added TimaKeyStore provider
,D/ResourcesManager( 8272): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] End Of Stream
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
V/AwesomePlayer(  287): postAudioEOS delayUs (0)
,V/AwesomePlayer(  287): onCheckAudioStatus
V/AwesomePlayer(  287): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  287): onStreamDone
V/AwesomePlayer(  287): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  287): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb061b3d0, 2, 0, 0)
V/AudioCache(  287): playback complete - thread will wake up later
V/AwesomePlayer(  287): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb061b3d0, 7, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=1)
,D/PowerManagerService(  840): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 840) eventTime = 108511
V/AwesomePlayer(  287): addBatteryData
V/AudioCache(  287): wait - success
V/StagefrightPlayer(  287): reset
D/PowerManagerService(  840): [s] UserActivityState : 2 -> 1
,D/PowerManagerService(  840): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=840 (0x0)
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb061b3d0, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
D/PowerManagerService(  840): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=840, ws=WorkSource{10059}) (elapsedTime=3474)
V/AwesomePlayer(  287): mAudioTrackVector clear
D/AudioPlayer(  287): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop() sendCommand(0x7a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  287): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  287): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  287): ~OggSource --
I/OggExtractor(  287): ~OggExtractor ++
I/OggExtractor(  287): ~MyVorbisExtractor ++ 
I/OggExtractor(  287): ~MyVorbisExtractor --
I/OggExtractor(  287): ~OggExtractor --
,I/AudioPlayer(  287): reset out
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  287): SecVideoCapture destructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): mSecCapture clear
I/SecMediaClock(  287): SecMediaClock destructor
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): ~StagefrightPlayer
V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/AwesomePlayer(  287): destructor
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/MediaPlayer( 8173): decode(41, 19156232, 8154)
V/MediaPlayerService(  287): decode(30, 19156232, 8154)
,V/MediaPlayerService(  287): player type = 3
V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): constructor
,V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): StagefrightPlayer
V/AwesomePlayer(  287): setListener
V/StagefrightPlayer(  287): initCheck
V/AwesomePlayer(  287): setAudioSink
V/StagefrightPlayer(  287): setDataSource(30, 19156232, 8154)
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54060, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
D/Utils   (  287): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  287): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  287): mBitrate = -1 bits/sec
I/OggExtractor(  287): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  287): current audio track index (0) is added to vector
V/AwesomePlayer(  287): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  287): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  287): prepare
V/AwesomePlayer(  287): prepareAsync
V/MediaPlayerService(  287): wait for prepare
V/AwesomePlayer(  287): onPrepareAsyncEvent
I/SecMediaClock(  287): SecMediaClock constructor
I/SecMediaClock(  287): reset
I/SecVideoCapture(  287): SecVideoCapture constructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): initAudioDecoder
V/AwesomePlayer(  287): checkOffloadExceptions is true
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  287): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  287): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  287): finishAsyncPrepare_l
V/AwesomePlayer(  287): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  287): notify(0xb0b54060, 200, 973, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54060, 5, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54060, 1, 0, 0)
V/AudioCache(  287): prepared
V/AudioCache(  287): wait - success
V/MediaPlayerService(  287): start
V/StagefrightPlayer(  287): start
V/AwesomePlayer(  287): play
V/AwesomePlayer(  287): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  287): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  287): start of Playback, useOffload 0
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  287): Audio channels(1)
,I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  287): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  287): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  287): notify(0xb0b54060, 6, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): addBatteryData
I/AudioPlayer(  287): First fillBuffer call!!
,I/AudioPlayer(  287): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
V/MediaPlayerService(  287): wait for playback complete
,E/AudioPlayer(  287): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,D/ShortcutReceiver( 8272):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  287): postAudioEOS delayUs (0)
,V/AwesomePlayer(  287): onCheckAudioStatus
V/AwesomePlayer(  287): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  287): onStreamDone
V/AwesomePlayer(  287): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  287): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54060, 2, 0, 0)
V/AudioCache(  287): playback complete - thread will wake up later
V/AwesomePlayer(  287): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54060, 7, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  287): addBatteryData
V/AudioCache(  287): wait - success
V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  287): notify(0xb0b54060, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
D/AudioPlayer(  287): reset: mPlaying=0 mReachedEOS=1 useOffload=0
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop() sendCommand(0x7b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  287): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  287): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  287): ~OggSource --
I/OggExtractor(  287): ~OggExtractor ++
,I/OggExtractor(  287): ~MyVorbisExtractor ++ 
I/OggExtractor(  287): ~MyVorbisExtractor --
I/OggExtractor(  287): ~OggExtractor --
,I/AudioPlayer(  287): reset out
,V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  287): SecVideoCapture destructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): mSecCapture clear
I/SecMediaClock(  287): SecMediaClock destructor
V/AwesomePlayer(  287): mSecMediaClock clear
,V/StagefrightPlayer(  287): ~StagefrightPlayer
V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/AwesomePlayer(  287): destructor
,V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
,V/AwesomePlayer(  287): mSecMediaClock clear
V/MediaPlayer( 8173): decode(42, 19129712, 4804)
,V/MediaPlayerService(  287): decode(30, 19129712, 4804)
,V/MediaPlayerService(  287): player type = 3
V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): constructor
,V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
,V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): StagefrightPlayer
V/AwesomePlayer(  287): setListener
V/StagefrightPlayer(  287): initCheck
V/AwesomePlayer(  287): setAudioSink
,V/StagefrightPlayer(  287): setDataSource(30, 19129712, 4804)
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0a24ec0, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
D/Utils   (  287): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  287): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  287): mBitrate = -1 bits/sec
I/OggExtractor(  287): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  287): current audio track index (0) is added to vector
V/AwesomePlayer(  287): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  287): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService(  287): prepare
V/AwesomePlayer(  287): prepareAsync
V/MediaPlayerService(  287): wait for prepare
V/AwesomePlayer(  287): onPrepareAsyncEvent
I/SecMediaClock(  287): SecMediaClock constructor
I/SecMediaClock(  287): reset
I/SecVideoCapture(  287): SecVideoCapture constructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): initAudioDecoder
V/AwesomePlayer(  287): checkOffloadExceptions is true
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  287): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  287): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  287): finishAsyncPrepare_l
V/AwesomePlayer(  287): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  287): notify(0xb0a24ec0, 200, 973, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0a24ec0, 5, 0, 0)
V/AudioCache(  287): ignored
,V/AwesomePlayer(  287): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0a24ec0, 1, 0, 0)
V/AudioCache(  287): prepared
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
V/AudioCache(  287): wait - success
V/MediaPlayerService(  287): start
V/StagefrightPlayer(  287): start
,V/AwesomePlayer(  287): play
,V/AwesomePlayer(  287): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  287): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  287): start of Playback, useOffload 0
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  287): Audio channels(1)
,I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  287): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  287): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  287): notify(0xb0a24ec0, 6, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): addBatteryData
I/AudioPlayer(  287): First fillBuffer call!!
V/MediaPlayerService(  287): wait for playback complete
,I/AudioPlayer(  287): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  287): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  287): postAudioEOS delayUs (0)
V/AwesomePlayer(  287): onCheckAudioStatus
V/AwesomePlayer(  287): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  287): onStreamDone
V/AwesomePlayer(  287): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  287): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0a24ec0, 2, 0, 0)
V/AudioCache(  287): playback complete - thread will wake up later
V/AwesomePlayer(  287): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0a24ec0, 7, 0, 0)
,V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  287): wait - success
V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): addBatteryData
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0a24ec0, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
D/AudioPlayer(  287): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  287): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  287): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  287): ~OggSource --
I/OggExtractor(  287): ~OggExtractor ++
I/OggExtractor(  287): ~MyVorbisExtractor ++ 
I/OggExtractor(  287): ~MyVorbisExtractor --
I/OggExtractor(  287): ~OggExtractor --
,I/AudioPlayer(  287): reset out
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  287): SecVideoCapture destructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): mSecCapture clear
I/SecMediaClock(  287): SecMediaClock destructor
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): ~StagefrightPlayer
V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/AwesomePlayer(  287): destructor
,V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
,V/MediaPlayer( 8173): decode(43, 19099164, 9400)
,V/MediaPlayerService(  287): decode(30, 19099164, 9400)
,V/MediaPlayerService(  287): player type = 3
V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): constructor
,V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): StagefrightPlayer
V/AwesomePlayer(  287): setListener
,V/StagefrightPlayer(  287): initCheck
V/AwesomePlayer(  287): setAudioSink
V/StagefrightPlayer(  287): setDataSource(30, 19099164, 9400)
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54560, 8, 0, 0)
V/AudioCache(  287): ignored
,V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/Utils   (  287): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  287): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  287): mBitrate = -1 bits/sec
I/OggExtractor(  287): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  287): current audio track index (0) is added to vector
V/AwesomePlayer(  287): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  287): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  287): prepare
V/AwesomePlayer(  287): prepareAsync
,V/MediaPlayerService(  287): wait for prepare
V/AwesomePlayer(  287): onPrepareAsyncEvent
I/SecMediaClock(  287): SecMediaClock constructor
I/SecMediaClock(  287): reset
,I/SecVideoCapture(  287): SecVideoCapture constructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): initAudioDecoder
V/AwesomePlayer(  287): checkOffloadExceptions is true
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  287): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  287): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  287): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  287): finishAsyncPrepare_l
V/MediaPlayer( 8173): decode(49, 19172584, 4112)
V/AwesomePlayer(  287): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache(  287): notify(0xb0b54560, 200, 973, 0)
V/AudioCache(  287): ignored
V/MediaPlayerService(  287): decode(35, 19172584, 4112)
V/AwesomePlayer(  287): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54560, 5, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54560, 1, 0, 0)
V/AudioCache(  287): prepared
V/AudioCache(  287): wait - success
V/MediaPlayerService(  287): start
V/StagefrightPlayer(  287): start
,V/AwesomePlayer(  287): play
V/AwesomePlayer(  287): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  287): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  287): start of Playback, useOffload 0
,V/MediaPlayerService(  287): player type = 3
V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): constructor
,V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
,V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): StagefrightPlayer
V/AwesomePlayer(  287): setListener
V/StagefrightPlayer(  287): initCheck
V/AwesomePlayer(  287): setAudioSink
I/OMXCodec(  287): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  287): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,V/StagefrightPlayer(  287): setDataSource(35, 19172584, 4112)
V/AwesomePlayer(  287): reset_l()
D/PackageBroadcastService( 2472): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xafa09290, 8, 0, 0)
I/AudioPlayer(  287): Audio channels(1)
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  287): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  287): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54560, 6, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): addBatteryData
V/MediaPlayerService(  287): wait for playback complete
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
,V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
I/AudioPlayer(  287): First fillBuffer call!!
I/AudioPlayer(  287): >>> setAudioEffect Read mAudioFormat : 1, event : 4194367, value : -2140176274
D/Utils   (  287): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
E/AudioPlayer(  287): >>> setAudioEffect Error mAudioFormat : 1, event : 4194367, value : -2140176274
,V/AwesomePlayer(  287): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  287): mBitrate = -1 bits/sec
I/OggExtractor(  287): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  287): current audio track index (0) is added to vector
V/AwesomePlayer(  287): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  287): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  287): prepare
V/AwesomePlayer(  287): prepareAsync
V/MediaPlayerService(  287): wait for prepare
V/AwesomePlayer(  287): onPrepareAsyncEvent
I/SecMediaClock(  287): SecMediaClock constructor
I/SecMediaClock(  287): reset
I/SecVideoCapture(  287): SecVideoCapture constructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): initAudioDecoder
V/AwesomePlayer(  287): checkOffloadExceptions is true
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  287): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
,I/AwesomePlayer(  287): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  287): finishAsyncPrepare_l
V/AwesomePlayer(  287): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  287): notify(0xafa09290, 200, 973, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xafa09290, 5, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache(  287): notify(0xafa09290, 1, 0, 0)
V/AudioCache(  287): prepared
V/AudioCache(  287): wait - success
V/MediaPlayerService(  287): start
V/StagefrightPlayer(  287): start
V/AwesomePlayer(  287): play
V/AwesomePlayer(  287): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  287): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  287): start of Playback, useOffload 0
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  287): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  287): Audio channels(1)
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  287): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  287): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  287): notify(0xafa09290, 6, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): addBatteryData
V/MediaPlayerService(  287): wait for playback complete
,I/AudioPlayer(  287): First fillBuffer call!!
I/AudioPlayer(  287): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  287): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  287): postAudioEOS delayUs (0)
V/AwesomePlayer(  287): onCheckAudioStatus
I/OMXCodec(  287): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  287): onCheckAudioStatus() set AUDIO_AT_EOS flag
,V/AwesomePlayer(  287): onStreamDone
V/AwesomePlayer(  287): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  287): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): postAudioEOS delayUs (0)
V/AudioCache(  287): notify(0xafa09290, 2, 0, 0)
V/AudioCache(  287): playback complete - thread will wake up later
V/AwesomePlayer(  287): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xafa09290, 7, 0, 0)
V/AudioCache(  287): ignored
,V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  287): addBatteryData
V/AudioCache(  287): wait - success
V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xafa09290, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
D/AudioPlayer(  287): reset: mPlaying=0 mReachedEOS=1 useOffload=0
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop() sendCommand(0x7e, OMX_CommandStateSet, OMX_StateIdle)
V/AwesomePlayer(  287): onCheckAudioStatus
I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  287): onCheckAudioStatus() set AUDIO_AT_EOS flag
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  287): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  287): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  287): ~OggSource --
I/OggExtractor(  287): ~OggExtractor ++
I/OggExtractor(  287): ~MyVorbisExtractor ++ 
I/OggExtractor(  287): ~MyVorbisExtractor --
I/OggExtractor(  287): ~OggExtractor --
,V/AwesomePlayer(  287): onStreamDone
V/AwesomePlayer(  287): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  287): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54560, 2, 0, 0)
V/AudioCache(  287): playback complete - thread will wake up later
V/AwesomePlayer(  287): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache(  287): notify(0xb0b54560, 7, 0, 0)
V/AudioCache(  287): ignored
I/AudioPlayer(  287): reset out
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  287): SecVideoCapture destructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): mSecCapture clear
I/SecMediaClock(  287): SecMediaClock destructor
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): ~StagefrightPlayer
V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/AwesomePlayer(  287): destructor
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  287): addBatteryData
V/AudioCache(  287): wait - success
V/StagefrightPlayer(  287): reset
,V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54560, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  287): mAudioTrackVector clear
D/AudioPlayer(  287): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthServiceInstalled() : HealthService is Installed.
I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  287): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  287): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  287): ~OggSource --
I/OggExtractor(  287): ~OggExtractor ++
I/OggExtractor(  287): ~MyVorbisExtractor ++ 
,I/OggExtractor(  287): ~MyVorbisExtractor --
I/OggExtractor(  287): ~OggExtractor --
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/AudioPlayer(  287): reset out
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  287): SecVideoCapture destructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): mSecCapture clear
I/SecMediaClock(  287): SecMediaClock destructor
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): ~StagefrightPlayer
V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/AwesomePlayer(  287): destructor
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/MediaPlayer( 8173): decode(44, 19307764, 52024)
,V/MediaPlayerService(  287): decode(30, 19307764, 52024)
,V/MediaPlayerService(  287): player type = 3
V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): constructor
,V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): StagefrightPlayer
V/AwesomePlayer(  287): setListener
V/StagefrightPlayer(  287): initCheck
V/AwesomePlayer(  287): setAudioSink
V/StagefrightPlayer(  287): setDataSource(30, 19307764, 52024)
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xaf7212e0, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
D/Utils   (  287): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  287): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  287): mBitrate = -1 bits/sec
I/OggExtractor(  287): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  287): current audio track index (0) is added to vector
V/AwesomePlayer(  287): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  287): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  287): prepare
V/AwesomePlayer(  287): prepareAsync
V/MediaPlayerService(  287): wait for prepare
,V/AwesomePlayer(  287): onPrepareAsyncEvent
I/SecMediaClock(  287): SecMediaClock constructor
I/SecMediaClock(  287): reset
I/SecVideoCapture(  287): SecVideoCapture constructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): initAudioDecoder
V/AwesomePlayer(  287): checkOffloadExceptions is true
,V/AudioPolicyManager(  287): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  287): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  287): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  287): finishAsyncPrepare_l
V/AwesomePlayer(  287): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache(  287): notify(0xaf7212e0, 200, 973, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xaf7212e0, 5, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xaf7212e0, 1, 0, 0)
V/AudioCache(  287): prepared
V/AudioCache(  287): wait - success
V/MediaPlayerService(  287): start
V/StagefrightPlayer(  287): start
V/AwesomePlayer(  287): play
V/AwesomePlayer(  287): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  287): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  287): start of Playback, useOffload 0
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  287): Audio channels(2)
,I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  287): open(48000, 2, 0x0, 1, 0)
,V/AwesomePlayer(  287): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
I/AudioPlayer(  287): First fillBuffer call!!
V/AudioCache(  287): notify(0xaf7212e0, 6, 0, 0)
I/AudioPlayer(  287): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  287): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
V/AudioCache(  287): ignored
,V/AwesomePlayer(  287): addBatteryData
,V/MediaPlayerService(  287): wait for playback complete
I/PeopleContactsSync( 2472): CP2 sync disabled
,I/ActivityManager(  840): Killing 5001:com.android.defcontainer/u0a5 (adj 15): bgCount ##41
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  287): postAudioEOS delayUs (0)
,V/AwesomePlayer(  287): onCheckAudioStatus
V/AwesomePlayer(  287): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  287): onStreamDone
V/AwesomePlayer(  287): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  287): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
,V/AudioCache(  287): notify(0xaf7212e0, 2, 0, 0)
V/AudioCache(  287): playback complete - thread will wake up later
V/AwesomePlayer(  287): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xaf7212e0, 7, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  287): addBatteryData
V/AudioCache(  287): wait - success
V/StagefrightPlayer(  287): reset
,V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xaf7212e0, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
D/AudioPlayer(  287): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop() sendCommand(0x7f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  287): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  287): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  287): ~OggSource --
I/OggExtractor(  287): ~OggExtractor ++
I/OggExtractor(  287): ~MyVorbisExtractor ++ 
I/OggExtractor(  287): ~MyVorbisExtractor --
I/OggExtractor(  287): ~OggExtractor --
,I/AudioPlayer(  287): reset out
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  287): SecVideoCapture destructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): mSecCapture clear
I/SecMediaClock(  287): SecMediaClock destructor
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): ~StagefrightPlayer
V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/AwesomePlayer(  287): destructor
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
,V/MediaPlayer( 8173): decode(45, 19172584, 4112)
V/MediaPlayerService(  287): decode(30, 19172584, 4112)
,V/MediaPlayerService(  287): player type = 3
V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): constructor
,V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
,V/StagefrightPlayer(  287): StagefrightPlayer
V/AwesomePlayer(  287): setListener
V/StagefrightPlayer(  287): initCheck
V/AwesomePlayer(  287): setAudioSink
V/StagefrightPlayer(  287): setDataSource(30, 19172584, 4112)
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb061b3d0, 8, 0, 0)
,V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
D/Utils   (  287): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  287): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  287): mBitrate = -1 bits/sec
I/OggExtractor(  287): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  287): current audio track index (0) is added to vector
V/AwesomePlayer(  287): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  287): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  287): prepare
,V/AwesomePlayer(  287): prepareAsync
V/MediaPlayerService(  287): wait for prepare
V/AwesomePlayer(  287): onPrepareAsyncEvent
I/SecMediaClock(  287): SecMediaClock constructor
I/SecMediaClock(  287): reset
I/SecVideoCapture(  287): SecVideoCapture constructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): initAudioDecoder
V/AwesomePlayer(  287): checkOffloadExceptions is true
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  287): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  287): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  287): finishAsyncPrepare_l
V/AwesomePlayer(  287): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  287): notify(0xb061b3d0, 200, 973, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb061b3d0, 5, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb061b3d0, 1, 0, 0)
V/AudioCache(  287): prepared
V/AudioCache(  287): wait - success
V/MediaPlayerService(  287): start
V/StagefrightPlayer(  287): start
,V/AwesomePlayer(  287): play
V/AwesomePlayer(  287): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  287): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  287): start of Playback, useOffload 0
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  287): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  287): Audio channels(1)
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  287): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  287): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb061b3d0, 6, 0, 0)
,V/AudioCache(  287): ignored
V/AwesomePlayer(  287): addBatteryData
I/AudioPlayer(  287): First fillBuffer call!!
I/AudioPlayer(  287): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  287): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  287): postAudioEOS delayUs (0)
V/AwesomePlayer(  287): onCheckAudioStatus
V/MediaPlayerService(  287): wait for playback complete
V/AwesomePlayer(  287): onCheckAudioStatus() set AUDIO_AT_EOS flag
,V/AwesomePlayer(  287): onStreamDone
V/AwesomePlayer(  287): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  287): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb061b3d0, 2, 0, 0)
V/AudioCache(  287): playback complete - thread will wake up later
V/AwesomePlayer(  287): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb061b3d0, 7, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  287): addBatteryData
V/AudioCache(  287): wait - success
,V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb061b3d0, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
D/AudioPlayer(  287): reset: mPlaying=0 mReachedEOS=1 useOffload=0
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor(  287): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  287): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  287): ~OggSource --
I/OggExtractor(  287): ~OggExtractor ++
I/OggExtractor(  287): ~MyVorbisExtractor ++ 
I/OggExtractor(  287): ~MyVorbisExtractor --
I/OggExtractor(  287): ~OggExtractor --
,I/AudioPlayer(  287): reset out
,V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  287): SecVideoCapture destructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): mSecCapture clear
I/SecMediaClock(  287): SecMediaClock destructor
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): ~StagefrightPlayer
,V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
,V/AwesomePlayer(  287): destructor
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
,V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/MediaPlayer( 8173): decode(46, 19235660, 21825)
,V/MediaPlayerService(  287): decode(30, 19235660, 21825)
V/MediaPlayerService(  287): player type = 3
V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): constructor
V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): StagefrightPlayer
V/AwesomePlayer(  287): setListener
V/StagefrightPlayer(  287): initCheck
V/AwesomePlayer(  287): setAudioSink
V/StagefrightPlayer(  287): setDataSource(30, 19235660, 21825)
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54060, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
D/Utils   (  287): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  287): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  287): mBitrate = -1 bits/sec
I/OggExtractor(  287): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  287): current audio track index (0) is added to vector
V/AwesomePlayer(  287): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  287): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  287): prepare
V/AwesomePlayer(  287): prepareAsync
V/MediaPlayerService(  287): wait for prepare
V/AwesomePlayer(  287): onPrepareAsyncEvent
,I/SecMediaClock(  287): SecMediaClock constructor
I/SecMediaClock(  287): reset
I/SecVideoCapture(  287): SecVideoCapture constructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): initAudioDecoder
V/AwesomePlayer(  287): checkOffloadExceptions is true
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  287): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  287): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  287): finishAsyncPrepare_l
V/AwesomePlayer(  287): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  287): notify(0xb0b54060, 200, 973, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54060, 5, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache(  287): notify(0xb0b54060, 1, 0, 0)
V/AudioCache(  287): prepared
V/AudioCache(  287): wait - success
V/MediaPlayerService(  287): start
V/StagefrightPlayer(  287): start
V/AwesomePlayer(  287): play
V/AwesomePlayer(  287): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  287): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  287): start of Playback, useOffload 0
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  287): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  287): Audio channels(2)
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  287): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  287): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  287): notify(0xb0b54060, 6, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): addBatteryData
V/MediaPlayerService(  287): wait for playback complete
I/AudioPlayer(  287): First fillBuffer call!!
I/AudioPlayer(  287): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  287): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SecureStorage(  358): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
I/SecureStorage(  358): [INFO]: SPID(0x00000005)PID: 8194, TID: 8206
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  287): postAudioEOS delayUs (0)
,V/AwesomePlayer(  287): onCheckAudioStatus
V/AwesomePlayer(  287): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  287): onStreamDone
V/AwesomePlayer(  287): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  287): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54060, 2, 0, 0)
V/AudioCache(  287): playback complete - thread will wake up later
V/AwesomePlayer(  287): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0b54060, 7, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  287): addBatteryData
,V/AudioCache(  287): wait - success
V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,V/AudioCache(  287): notify(0xb0b54060, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
D/AudioPlayer(  287): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor(  287): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  287): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  287): ~OggSource --
I/OggExtractor(  287): ~OggExtractor ++
I/OggExtractor(  287): ~MyVorbisExtractor ++ 
I/OggExtractor(  287): ~MyVorbisExtractor --
,I/OggExtractor(  287): ~OggExtractor --
,I/AudioPlayer(  287): reset out
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  287): SecVideoCapture destructor
I/SecVideoCapture(  287): reset
,V/AwesomePlayer(  287): mSecCapture clear
I/SecMediaClock(  287): SecMediaClock destructor
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): ~StagefrightPlayer
V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/AwesomePlayer(  287): destructor
,V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
,V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/MediaPlayer( 8173): decode(47, 19134596, 21552)
,V/MediaPlayerService(  287): decode(30, 19134596, 21552)
,V/MediaPlayerService(  287): player type = 3
V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): constructor
,V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): StagefrightPlayer
V/AwesomePlayer(  287): setListener
V/StagefrightPlayer(  287): initCheck
V/AwesomePlayer(  287): setAudioSink
V/StagefrightPlayer(  287): setDataSource(30, 19134596, 21552)
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0a24ec0, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
D/Utils   (  287): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/libprocessgroup(  840): failed to open /acct/uid_10005/pid_5001/cgroup.procs: No such file or directory
,V/AwesomePlayer(  287): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  287): mBitrate = -1 bits/sec
I/OggExtractor(  287): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  287): current audio track index (0) is added to vector
V/AwesomePlayer(  287): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  287): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  287): prepare
V/AwesomePlayer(  287): prepareAsync
V/MediaPlayerService(  287): wait for prepare
V/AwesomePlayer(  287): onPrepareAsyncEvent
I/SecMediaClock(  287): SecMediaClock constructor
I/SecMediaClock(  287): reset
I/SecVideoCapture(  287): SecVideoCapture constructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): initAudioDecoder
V/AwesomePlayer(  287): checkOffloadExceptions is true
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  287): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  287): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  287): finishAsyncPrepare_l
V/AwesomePlayer(  287): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  287): notify(0xb0a24ec0, 200, 973, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0a24ec0, 5, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0a24ec0, 1, 0, 0)
V/AudioCache(  287): prepared
V/AudioCache(  287): wait - success
V/MediaPlayerService(  287): start
V/StagefrightPlayer(  287): start
,V/AwesomePlayer(  287): play
V/AwesomePlayer(  287): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  287): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  287): start of Playback, useOffload 0
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  287): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/AudioPlayer(  287): Audio channels(2)
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  287): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  287): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0a24ec0, 6, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): addBatteryData
I/AudioPlayer(  287): First fillBuffer call!!
V/MediaPlayerService(  287): wait for playback complete
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] End Of Stream
D/LockPatternUtilsCache( 1168): value : false
V/AwesomePlayer(  287): postAudioEOS delayUs (0)
,V/AwesomePlayer(  287): onCheckAudioStatus
,V/AwesomePlayer(  287): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  287): onStreamDone
V/AwesomePlayer(  287): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  287): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0a24ec0, 2, 0, 0)
V/AudioCache(  287): playback complete - thread will wake up later
V/AwesomePlayer(  287): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache(  287): notify(0xb0a24ec0, 7, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  287): addBatteryData
V/AudioCache(  287): wait - success
V/StagefrightPlayer(  287): reset
,V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xb0a24ec0, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
,D/AudioPlayer(  287): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  287): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  287): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  287): ~OggSource --
I/OggExtractor(  287): ~OggExtractor ++
I/OggExtractor(  287): ~MyVorbisExtractor ++ 
I/OggExtractor(  287): ~MyVorbisExtractor --
I/OggExtractor(  287): ~OggExtractor --
,I/AudioPlayer(  287): reset out
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  287): SecVideoCapture destructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): mSecCapture clear
I/SecMediaClock(  287): SecMediaClock destructor
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): ~StagefrightPlayer
V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/AwesomePlayer(  287): destructor
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/MediaPlayer( 8173): decode(48, 19228560, 7017)
V/MediaPlayerService(  287): decode(30, 19228560, 7017)
,V/MediaPlayerService(  287): player type = 3
V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): constructor
,V/AwesomePlayer(  287): setDefault
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): StagefrightPlayer
V/AwesomePlayer(  287): setListener
V/StagefrightPlayer(  287): initCheck
V/AwesomePlayer(  287): setAudioSink
V/StagefrightPlayer(  287): setDataSource(30, 19228560, 7017)
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xafa09290, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
D/Utils   (  287): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  287): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  287): mBitrate = -1 bits/sec
I/OggExtractor(  287): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer(  287): current audio track index (0) is added to vector
V/AwesomePlayer(  287): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  287): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  287): prepare
V/AwesomePlayer(  287): prepareAsync
V/MediaPlayerService(  287): wait for prepare
V/AwesomePlayer(  287): onPrepareAsyncEvent
,I/SecMediaClock(  287): SecMediaClock constructor
I/SecMediaClock(  287): reset
I/SecVideoCapture(  287): SecVideoCapture constructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): initAudioDecoder
V/AwesomePlayer(  287): checkOffloadExceptions is true
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  287): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  287): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
,I/AwesomePlayer(  287): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  287): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  287): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  287): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  287): finishAsyncPrepare_l
,V/AwesomePlayer(  287): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  287): notify(0xafa09290, 200, 973, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xafa09290, 5, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xafa09290, 1, 0, 0)
V/AudioCache(  287): prepared
,V/AudioCache(  287): wait - success
V/MediaPlayerService(  287): start
V/StagefrightPlayer(  287): start
V/AwesomePlayer(  287): play
V/AwesomePlayer(  287): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  287): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  287): start of Playback, useOffload 0
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  287): >>>UHQA initOutputFormat 16
I/OMXCodec(  287): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/AudioPlayer(  287): Audio channels(2)
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  287): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  287): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  287): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xafa09290, 6, 0, 0)
,V/AudioCache(  287): ignored
V/AwesomePlayer(  287): addBatteryData
I/AudioPlayer(  287): First fillBuffer call!!
I/AudioPlayer(  287): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  287): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
V/MediaPlayerService(  287): wait for playback complete
,I/OMXCodec(  287): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  287): postAudioEOS delayUs (0)
V/AwesomePlayer(  287): onCheckAudioStatus
V/AwesomePlayer(  287): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  287): onStreamDone
V/AwesomePlayer(  287): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  287): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xafa09290, 2, 0, 0)
V/AudioCache(  287): playback complete - thread will wake up later
V/AwesomePlayer(  287): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xafa09290, 7, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  287): wait - success
V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): addBatteryData
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  287): notify(0xafa09290, 8, 0, 0)
V/AudioCache(  287): ignored
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
D/AudioPlayer(  287): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  287): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  287): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  287): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  287): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  287): ~OggSource --
I/OggExtractor(  287): ~OggExtractor ++
I/OggExtractor(  287): ~MyVorbisExtractor ++ 
I/OggExtractor(  287): ~MyVorbisExtractor --
I/OggExtractor(  287): ~OggExtractor --
,I/AudioPlayer(  287): reset out
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  287): SecVideoCapture destructor
I/SecVideoCapture(  287): reset
V/AwesomePlayer(  287): mSecCapture clear
I/SecMediaClock(  287): SecMediaClock destructor
V/AwesomePlayer(  287): mSecMediaClock clear
V/StagefrightPlayer(  287): ~StagefrightPlayer
V/StagefrightPlayer(  287): reset
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
V/AwesomePlayer(  287): destructor
V/AwesomePlayer(  287): reset_l()
V/AwesomePlayer(  287): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  287): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  287): mAudioTrackVector clear
V/AwesomePlayer(  287): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  287): mSecCapture clear
V/AwesomePlayer(  287): mSecMediaClock clear
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/GAV4    ( 7961): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SecureStorage( 8194): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 8194): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
,I/SecSQLiteOpenHelper( 8173): getWritableDatabase(pwd)
,I/SecSQLiteOpenHelper( 8173): getDatabaseLocked(b,b,pwd)...
,I/SecSQLiteOpenHelper( 8173): Open platform.db in secure mode
,D/SecSQLiteDatabase( 8173): Android Version: 5.0
D/SecSQLiteDatabase( 8173): Load library secsqlite.so for Android 5.0
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,I/SecSQLiteDatabase( 8173): openSecureDatabase...
,I/SecSQLiteDatabase( 8173): private openSecureDatabase...
,I/SecSQLiteConnectionPool( 8173): OpenSecure
I/SecSQLiteConnectionPool( 8173): OpenSecure with password
I/SecSQLiteConnectionPool( 8173): openSecureConnectionLocked
,I/SecSQLiteDatabase( 8173): ...private openSecureDatabase
,I/SecSQLiteDatabase( 8173): ...openSecureDatabase
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SurfaceFlinger(  249): id=16 Removed Toast (8/8)
I/SurfaceFlinger(  249): id=16 Removed Toast (-2/8)
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SecSQLiteOpenHelper( 8173): ...getDatabaseLocked(b,b,pwd)
,D/SecSQLiteOpenHelper( 8173): ...getDatabaseLocked(b,b,pwd)
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8173): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,W/System.err( 8173): java.lang.NumberFormatException: Invalid int: "null"
,W/System.err( 8173): 	at java.lang.Integer.invalidInt(Integer.java:138)
W/System.err( 8173): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err( 8173): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err( 8173): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:449)
W/System.err( 8173): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1173)
W/System.err( 8173): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8173): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 8173): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 420, PST = 428, CUR = 300
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7690): mConnectivityHandler : connected
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7690): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 7690): ================================================
I/CSTORAGE( 7690):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
,I/CSTORAGE( 7690): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7690): [GetString-S]
E/art     ( 7690): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI( 7690): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7690): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7690): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7690): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7690): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7690): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 7803): wlan0: sending IPv6 Router Solicitation
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  840): CMD_RSSI_POLL : out!
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...,
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,I/GAV3    ( 8173): Thread[GAThread,5,main]: No campaign data found.
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  840): CMD_RSSI_POLL : out!
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/dhcpcd  ( 7803): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7803): wlan0: no IPv6 Routers available
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/PreloadUpdateManagerStateMachine( 7120): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7120): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7120): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7120): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7120): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7120): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7120): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7120): entry::IDLE
,E/SMD     (  282): DCD ON
,D/PreloadUpdateManagerStateMachine( 7120): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7120): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7120): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7120): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7120): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7120): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7120): entry::IDLE
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/AlarmManager(  840): waitForAlarm result :4
,D/FactoryTest( 6701): Not factory mode
D/FactoryTest( 6701): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6701): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6701): still no open session command from host, so toast
,W/ContextImpl( 6701): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 6701): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6701): Timeline: Activity_launch_request id:com.android.settings time:117107
,E/PersonaManagerService(  840): inState():  stateMachine is null !!
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  840): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  840): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 840  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  840): mDVFSHelper.acquire()
,V/AlarmManager(  840): waitForAlarm result :4
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,E/MTPRx   ( 6701): started activity for popup
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SQLiteSecureOpenHelper( 3560): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3560): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ResourcesManager( 6701): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6701): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6701): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6701): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6701): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6701): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6701): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6701): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  840): CMD_RSSI_POLL : out!
,E/SettingsReceiverActivity( 6701): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/InputMethodManagerService(  840): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,E/ActivityManager(  840): Invalid thumbnail dimensions: 576x576
,W/InputMethodManagerService(  840): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@670f8ab attribute=null, token = android.os.BinderProxy@35e4039e
,I/SQLiteSecureOpenHelper( 3560): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3560): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6701): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6701): dev.kiessupport is : TRUE
,D/Activity( 6701): performCreate Call secproduct feature valuefalse
,D/Activity( 6701): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ActivityManager(  840): post active user change for 0
D/KnoxTimeoutHandler(  840): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  840): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/Timeline( 7562): Timeline: Activity_idle id: android.os.BinderProxy@f5acc6d time:117375
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6601): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6601): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6601): [1] 5.onFinished: Scheduling replication attempt 3.
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 1
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/SMD     (  282): DCD ON
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/SSRM:m  (  840): SIOP:: AP = 380, PST = 419, CUR = 300
,D/CustomFrequencyManagerService(  840): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 840  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  840): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  840): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 840  pkgName : ACTIVITY_RESUME_BOOSTER@10
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  840): CMD_RSSI_POLL : out!
,D/CustomFrequencyManagerService(  840): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 840  tag : ACTIVITY_RESUME_BOOSTER@10
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/SMD     (  282): DCD ON
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,I/ServiceManager(  341): Waiting for service AtCmdFwd...,
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  840): CMD_RSSI_POLL : out!
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  840): CMD_RSSI_POLL : out!
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  840): Plugged
I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 2
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  840): CMD_RSSI_POLL : out!
,D/SSRM:m  (  840): SIOP:: AP = 340, PST = 405, CUR = 300
,D/X       (  840): broadcastSiopLevelIntent:: currentSiopLevel = -1
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
I/SystemBroadcastReceiver( 7143): [#DCM#] [DCM_Performance] onReceive completed in time  1111 microsec. 
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,D/ContentApp( 1226):  LEVEL : -1
,I/SystemBroadcastReceiver( 7143): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7143): [#DCM#] onReceive action = EVENT_SIOP
,E/Zygote  ( 8376): MountEmulatedStorage()
,E/Zygote  ( 8376): v2
I/libpersona( 8376): KNOX_SDCARD checking this for 10054
I/libpersona( 8376): KNOX_SDCARD not a persona
I/ActivityManager(  840): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=8376 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,I/SELinux ( 8376): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8376): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8376): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8376): TimaSignature is unavailable
,D/ActivityThread( 8376): Added TimaKeyStore provider
,D/ResourcesManager( 8376): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8376): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8376): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8376): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8376): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8376): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/TranscodeReceiver( 8376): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 8376): core_num = 4
,W/linker  ( 8376): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 8376): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 8376): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
,D/videowall-Global( 8376): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 8376):  SIOP_LEVEL: -1
,I/ActivityManager(  840): Killing 5714:com.android.mms/u0a50 (adj 15): bgCount ##41
,D/CountryDetector(  840): No listener is left
,W/libprocessgroup(  840): failed to open /acct/uid_10050/pid_5714/cgroup.procs: No such file or directory
,E/SMD     (  282): DCD ON
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  840): CMD_RSSI_POLL : out!
,D/PowerManagerService(  840): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  840): getFinalBrightness : 15 -> 15
,D/PowerManagerService(  840): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  840): lcd : 28 +
,D/lights  (  840): lcd : 28 -
,D/lights  (  840): lcd : 20 +
,D/lights  (  840): lcd : 20 -
,D/lights  (  840): lcd : 15 +
D/DisplayPowerController(  840): getFinalBrightness : 15 -> 15
,D/lights  (  840): lcd : 15 -
,D/DisplayPowerController(  840): getFinalBrightness : 15 -> 15
,E/Watchdog(  840): !@Sync 4
,E/SMD     (  282): DCD ON
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  840): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/SMD     (  282): DCD ON
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,V/AlarmManager(  840): waitForAlarm result :4
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  840): Plugged
I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/art     ( 1676): Explicit concurrent mark sweep GC freed 32196(1946KB) AllocSpace objects, 22(1782KB) LOS objects, 40% free, 17MB/29MB, paused 651us total 49.442ms
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6601): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6601): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6601): [1] 5.onFinished: Scheduling replication attempt 4.
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  840): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  840): CMD_RSSI_POLL : out!
,D/PowerManagerService(  840): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  840): Nap time (uid 1000)...
I/PowerManagerService(  840): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  840): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService(  840): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  840): SecHardwareInterface.setBatteryADC : false
,D/InputManager-JNI(  840): setDeviceInteractive: 0
D/PowerManagerService(  840): handleSandman : startDream()
,E/PowerManagerService(  840): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService(  840): Sleeping (uid 1000)...
D/PowerManagerService(  840): [s] UserActivityState : 4 -> 0
,D/InputManager-JNI(  840): sysfs_write +: /sys/class/input/event2/device/enabled: 0
D/PowerManagerService(  840): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService(  840): [input device light] handleInputDeviceLightOff
,D/InputManager-JNI(  840): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,I/SurfaceFlinger(  249): id=17 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  840): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  840): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/SContextService(  840): 	.unregisterCallback : 1, client=
,D/SContextService(  840): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@11426c3b, Service = Auto Rotation, used = 1
,W/CAE     (  840): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  840): stop(ContextProvider.java:149)
,V/CAE     (  840): clear(AutoRotationRunner.java:182)
,V/CAE     (  840): disable(AutoRotationRunner.java:171)
,I/CAE     (  840): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  840): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  300): sendContextData: -78, 7, 0, 0
,D/CAE     (  840): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  840): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  840): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/CAE     (  840): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  840): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  840): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  840): removeSContextService() : service = Auto Rotation
D/SContextService(  840): ===== SContext Service List =====
,D/SContextManager(  840):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@2c46abc4, service=Auto Rotation
,D/KeyguardViewMediator( 1168): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1168): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1168): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1168): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/KeyguardViewMediator( 1168): timeout : 5000
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/DisplayPowerController(  840): ColorFade: onAnimationStart
,D/DisplayPowerController(  840): getFinalBrightness : 34 -> 0
,D/lights  (  840): lcd : 13 +
,I/SQLiteSecureOpenHelper( 3560): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3560): getDatabaseLocked(b,b,pwd)...
,D/lights  (  840): lcd : 13 -
,D/lights  (  840): lcd : 4 +
,D/lights  (  840): lcd : 4 -
,D/lights  (  840): lcd : 0 +
,D/DisplayPowerController(  840): getFinalBrightness : 34 -> 0
,D/lights  (  840): lcd : 0 -
,D/KeyguardViewMediator( 1168): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1168): handleNotifyScreenOff
,D/LightsService(  840): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 840) 
D/LightsService(  840): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  840): [SvcLED]  onSensorChanged::light value = 18
,D/SensorManager(  840): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  840): unregisterListener ::   
D/lights  (  840): led_pattern : 5 +
,D/BatteryService(  840): turn on LED for fully charged
,D/lights  (  840): led_pattern : 5 -
D/LightsService(  840): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  840): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  840): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  840): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  840): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  300): sendContextData: -76, 13, -46, 0
,I/CAE     (  840): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 13, 1, 52,
D/SensorHubManager(  840): SendSensorHubData: send data = -63, 14, 13, 1, 52
D/Sensorhubs(  300): sendContextData: -63, 14, 13, 1, 52
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  840):  handler : SCREEN_OFF end 
,D/WifiStateMachine(  840): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  840): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  840): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  840): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  840): do suspend true
D/NotificationService(  840): ACTION_SCREEN_OFF
D/LightsService(  840): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 840) 
D/LightsService(  840): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/LightsService(  840): [SvcLED]  onSensorChanged::light value = 18
,D/SensorManager(  840): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  840): unregisterListener ::   
D/LightsService(  840): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  287): adev_set_parameters: enter: screen_state=off
V/voice   (  287): voice_set_parameters: enter: screen_state=off
V/voice   (  287): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  287): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  287): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  287): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  287): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  840): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  840): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController(  840): Bridge Server is not available
,D/VolumePanel( 1168): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1168): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1168): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1168): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  840): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  840): MSG_ACTION_SCREEN_OFF called
,D/DisplayPowerState(  840): !@ ColorFade entry
D/DisplayPowerController(  840): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  840): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,I/AutomaticBrightnessController(  840): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
I/AutomaticBrightnessController(  840): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/AutomaticBrightnessController(  840): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  840): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,D/SensorManager(  840): unregisterListener ::   
E/Sensors (  840): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/NfcService( 1468): call the applyRotuiing
,D/SensorManager(  840): unregisterListener ::   
,D/STATUSBAR-PhoneStatusBar( 1168):      ACTION_SCREEN_OFF is finished!!!! 
,D/DisplayPowerController(  840): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  840): getFinalBrightness : 0 -> 0
I/DisplayManagerService(  840): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,V/ActivityManager(  840): Display changed displayId=0
,E/StatusBar( 1168): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1168): dismissHelpPopup 
,D/accuweather( 2081): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 2081): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
,D/accuweather( 2081): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/StatusBar.NetworkController( 1168): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,I/SystemBroadcastReceiver( 7143): [#DCM#] [DCM_Performance] onReceive completed in time  264 microsec. 
,I/SystemBroadcastReceiver( 7143): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7143): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 7143): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,W/ActivityManager(  840): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  840): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/PowerManagerService(  840): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:m  (  840): SIOP:: AP = 340, PST = 390, CUR = 300
,I/rmt_storage(  273): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
I/rmt_storage(  273): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  273): wakelock acquired: 1, error no: 42
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1229454592)
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1229454592) wakelock released: 1, error no: 22
I/rmt_storage(  273): 
,I/rmt_storage(  273): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  840): Excessive delay in setPowerMode(): 257ms
,D/MISC PowerHAL(  840): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/PowerManagerService(  840): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  840): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  840): Got set_interactive hint
,I/PowerManagerService(  840): [PWL] Off : 0s ago
,I/PowerManagerService(  840): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  840): [PWL]     mDisplayReady : false
D/DisplayPowerController(  840): getFinalBrightness : 0 -> 0
D/PowerManagerService(  840): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  840): [PWL] sb release: PowerManagerService.Display
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager(  840): waitForAlarm result :4
,D/KeyguardViewMediator( 1168): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/KeyguardViewMediator( 1168): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService(  840): [PWL] Off : 5s ago
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 330, PST = 378, CUR = 300
,V/AlarmManager(  840): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  840): stay LED for fully charged
D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1676): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,E/SMD     (  282): DCD ON
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6570): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6570): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6570): 	at kfv.a(PG:65)
E/HttpOperation( 6570): 	at kff.u(PG:385)
E/HttpOperation( 6570): 	at kfb.a(PG:29)
E/HttpOperation( 6570): 	at kff.l(PG:132)
E/HttpOperation( 6570): 	at dsf.a(PG:807)
E/HttpOperation( 6570): 	at fhk.a(PG:1126)
E/HttpOperation( 6570): 	at fhk.a(PG:908)
E/HttpOperation( 6570): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6570): 	at ihi.a(PG:22)
E/HttpOperation( 6570): 	at kft.a(PG:91)
E/HttpOperation( 6570): 	at kfv.a(PG:62)
E/HttpOperation( 6570): 	... 8 more
E/HttpOperation( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6570): 	at gde.c(Unknown Source)
E/HttpOperation( 6570): 	at gde.b(Unknown Source)
E/HttpOperation( 6570): 	at ihi.a(PG:19)
E/HttpOperation( 6570): 	... 10 more
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6570): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6570): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6570): 	at kfv.a(PG:65)
E/HttpOperation( 6570): 	at kff.u(PG:385)
E/HttpOperation( 6570): 	at kfb.a(PG:29)
E/HttpOperation( 6570): 	at kff.l(PG:132)
E/HttpOperation( 6570): 	at ieo.a(PG:43)
E/HttpOperation( 6570): 	at iep.a(PG:93)
E/HttpOperation( 6570): 	at fhn.a(PG:59)
E/HttpOperation( 6570): 	at lex.a(PG:85)
E/HttpOperation( 6570): 	at lex.b(PG:132)
E/HttpOperation( 6570): 	at fhk.a(PG:1146)
E/HttpOperation( 6570): 	at fhk.a(PG:908)
E/HttpOperation( 6570): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6570): 	at ihi.a(PG:22)
E/HttpOperation( 6570): 	at kft.a(PG:91)
E/HttpOperation( 6570): 	at kfv.a(PG:62)
E/HttpOperation( 6570): 	... 12 more
E/HttpOperation( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6570): 	at gde.c(Unknown Source)
E/HttpOperation( 6570): 	at gde.b(Unknown Source)
E/HttpOperation( 6570): 	at ihi.a(PG:19)
E/HttpOperation( 6570): 	... 14 more
E/ExperimentLoader( 6570): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6570): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6570): 	at kfv.a(PG:65)
E/ExperimentLoader( 6570): 	at kff.u(PG:385)
E/ExperimentLoader( 6570): 	at kfb.a(PG:29)
E/ExperimentLoader( 6570): 	at kff.l(PG:132)
E/ExperimentLoader( 6570): 	at ieo.a(PG:43)
E/ExperimentLoader( 6570): 	at iep.a(PG:93)
E/ExperimentLoader( 6570): 	at fhn.a(PG:59)
E/ExperimentLoader( 6570): 	at lex.a(PG:85)
E/ExperimentLoader( 6570): 	at lex.b(PG:132)
E/ExperimentLoader( 6570): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6570): 	at fhk.a(PG:908)
E/ExperimentLoader( 6570): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6570): 	at ihi.a(PG:22)
E/ExperimentLoader( 6570): 	at kft.a(PG:91)
E/ExperimentLoader( 6570): 	at kfv.a(PG:62)
E/ExperimentLoader( 6570): 	... 12 more
E/ExperimentLoader( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6570): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6570): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6570): 	at ihi.a(PG:19)
E/ExperimentLoader( 6570): 	... 14 more
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
D/SecContentProvider2(  840): mCursor = null
,D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,E/HttpOperation( 6570): [getaccountstatus] Unexpected exception
E/HttpOperation( 6570): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6570): 	at kfv.a(PG:65)
E/HttpOperation( 6570): 	at kff.u(PG:385)
E/HttpOperation( 6570): 	at kfb.a(PG:29)
E/HttpOperation( 6570): 	at ixd.a(PG:248)
E/HttpOperation( 6570): 	at ixd.b(PG:206)
E/HttpOperation( 6570): 	at ixd.a(PG:175)
E/HttpOperation( 6570): 	at fig.a(PG:78)
E/HttpOperation( 6570): 	at lex.a(PG:85)
E/HttpOperation( 6570): 	at lex.b(PG:132)
E/HttpOperation( 6570): 	at fhk.a(PG:1146)
E/HttpOperation( 6570): 	at fhk.a(PG:908)
E/HttpOperation( 6570): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6570): 	at ihi.a(PG:22)
E/HttpOperation( 6570): 	at kft.a(PG:91)
E/HttpOperation( 6570): 	at kfv.a(PG:62)
E/HttpOperation( 6570): 	... 12 more
E/HttpOperation( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6570): 	at gde.c(Unknown Source)
E/HttpOperation( 6570): 	at gde.b(Unknown Source)
E/HttpOperation( 6570): 	at ihi.a(PG:19)
E/HttpOperation( 6570): 	... 14 more
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
E/EsSyncAdapterService( 6570): Sync failure
E/EsSyncAdapterService( 6570): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6570): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6570): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6570): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6570): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6570): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6570): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6570): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6570): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6570): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6570): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6570): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6570): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6570): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6570): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6570): 	... 10 more
E/EsSyncAdapterService( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6570): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6570): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6570): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6570): 	... 12 more
E/EsSyncAdapterService( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6570): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6570): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6570): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6570): 	... 14 more
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  840): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 151009, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  840): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  840): mCursor = null
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SQLiteLog( 1676): (10) POSIX Error : 11 SQLite Error : 3850
,I/PowerManagerService(  840): [PWL] Off : 15s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/SSRM:m  (  840): SIOP:: AP = 320, PST = 369, CUR = 300
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 4
,E/Watchdog(  840): !@Sync 5
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 310, PST = 359, CUR = 300
,I/PowerManagerService(  840): [PWL] Off : 30s ago
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :4
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  840): stay LED for fully charged
D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/VacuumService( 1676): Vacuum at: now=1452862945611 tag=VacuumService
,I/GoogleURLConnFactory( 1676): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Uploader( 1676): No account for auth token provided
,I/System.out( 1676): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1676): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1676): (HTTPLog)-Thread-205-750337393: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6601): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6601): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6601): [1] 5.onFinished: Scheduling replication attempt 5.
,I/qtaguid ( 1676): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1676, getuid(): 10012
,I/qtaguid ( 1676): Tagging socket 62 with tag 120100000000{4609,0} uid -1, pid: 1676, getuid(): 10012
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,E/Uploader( 1676): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1676): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1676): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1676): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1676): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1676): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1676): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1676): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1676): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1676): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/qtaguid ( 1676): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1676, getuid(): 10012
,W/Uploader( 1676): No account for auth token provided
,I/qtaguid ( 1676): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1676, getuid(): 10012
,W/Uploader( 1676): No account for auth token provided
,I/qtaguid ( 1676): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1676, getuid(): 10012
,W/Uploader( 1676):  no longer exists, so no auth token.
,I/qtaguid ( 1676): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1676, getuid(): 10012
,E/SQLiteLog( 1676): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :4
,D/SSRM:m  (  840): SIOP:: AP = 310, PST = 350, CUR = 300
,V/AlarmManager(  840): waitForAlarm result :4
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7446): Starting books sync, d
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1676): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
,D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7446): Authentication error
E/BooksAccountManager( 7446): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7446): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7446): null auth token
,I/qtaguid ( 7446): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7446, getuid(): 10082
,I/qtaguid ( 7446): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7446, getuid(): 10082
,I/qtaguid ( 7446): Untagging socket 34
,W/ApiaryClient( 7446): Error response from books API: {
W/ApiaryClient( 7446):  "error": {
W/ApiaryClient( 7446):   "errors": [
W/ApiaryClient( 7446):    {
W/ApiaryClient( 7446):     "domain": "global",
W/ApiaryClient( 7446):     "reason": "required",
W/ApiaryClient( 7446):     "message": "Login Required",
W/ApiaryClient( 7446):     "locationType": "header",
W/ApiaryClient( 7446):     "location": "Authorization"
W/ApiaryClient( 7446):    }
W/ApiaryClient( 7446):   ],
W/ApiaryClient( 7446):   "code": 401,
W/ApiaryClient( 7446):   "message": "Login Required"
W/ApiaryClient( 7446):  }
W/ApiaryClient( 7446): }
,W/ApiaryClient( 7446): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-670313014904777318&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7446): Headers suppressed
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,D/BatteryService(  840): stay LED for fully charged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
,D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7446): Authentication error
E/BooksAccountManager( 7446): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7446): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7446): null auth token
,I/qtaguid ( 7446): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7446, getuid(): 10082
,I/qtaguid ( 7446): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7446, getuid(): 10082
,I/qtaguid ( 7446): Untagging socket 34
,W/ApiaryClient( 7446): Error response from books API: {
W/ApiaryClient( 7446):  "error": {
W/ApiaryClient( 7446):   "errors": [
W/ApiaryClient( 7446):    {
W/ApiaryClient( 7446):     "domain": "global",
W/ApiaryClient( 7446):     "reason": "required",
W/ApiaryClient( 7446):     "message": "Login Required",
W/ApiaryClient( 7446):     "locationType": "header",
W/ApiaryClient( 7446):     "location": "Authorization"
W/ApiaryClient( 7446):    }
W/ApiaryClient( 7446):   ],
W/ApiaryClient( 7446):   "code": 401,
W/ApiaryClient( 7446):   "message": "Login Required"
W/ApiaryClient( 7446):  }
W/ApiaryClient( 7446): }
,W/ApiaryClient( 7446): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-670313014904777318&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7446): Headers suppressed
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
,D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,E/BooksAccountManager( 7446): Authentication error
E/BooksAccountManager( 7446): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7446): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7446): null auth token
,I/qtaguid ( 7446): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7446, getuid(): 10082
,I/qtaguid ( 7446): Untagging socket 34
,W/ApiaryClient( 7446): Error response from books API: {
W/ApiaryClient( 7446):  "error": {
W/ApiaryClient( 7446):   "errors": [
W/ApiaryClient( 7446):    {
W/ApiaryClient( 7446):     "domain": "global",
W/ApiaryClient( 7446):     "reason": "required",
W/ApiaryClient( 7446):     "message": "Login Required",
W/ApiaryClient( 7446):     "locationType": "header",
W/ApiaryClient( 7446):     "location": "Authorization"
W/ApiaryClient( 7446):    }
W/ApiaryClient( 7446):   ],
W/ApiaryClient( 7446):   "code": 401,
W/ApiaryClient( 7446):   "message": "Login Required"
W/ApiaryClient( 7446):  }
W/ApiaryClient( 7446): }
,W/ApiaryClient( 7446): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-670313014904777318&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7446): Headers suppressed
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/BooksSync( 7446): Soft error
E/BooksSync( 7446): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-670313014904777318&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7446): Headers suppressed
E/BooksSync( 7446): 
E/BooksSync( 7446): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7446): Sync error
E/BooksSync( 7446): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-670313014904777318&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7446): Headers suppressed
E/BooksSync( 7446): 
E/BooksSync( 7446): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7446): Finished books sync
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  840): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 152819, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  840): Explicit concurrent mark sweep GC freed 72569(4MB) AllocSpace objects, 36(3MB) LOS objects, 30% free, 36MB/52MB, paused 3.585ms total 137.984ms
,D/SecContentProvider2(  840): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  840): mCursor = null
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,E/HttpOperation( 6570): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6570): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6570): 	at kfv.a(PG:65)
E/HttpOperation( 6570): 	at kff.u(PG:385)
E/HttpOperation( 6570): 	at kfb.a(PG:29)
E/HttpOperation( 6570): 	at kff.l(PG:132)
E/HttpOperation( 6570): 	at dsf.a(PG:807)
E/HttpOperation( 6570): 	at fhk.a(PG:1126)
E/HttpOperation( 6570): 	at fhk.a(PG:908)
E/HttpOperation( 6570): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6570): 	at ihi.a(PG:22)
E/HttpOperation( 6570): 	at kft.a(PG:91)
E/HttpOperation( 6570): 	at kfv.a(PG:62)
E/HttpOperation( 6570): 	... 8 more
E/HttpOperation( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6570): 	at gde.c(Unknown Source)
E/HttpOperation( 6570): 	at gde.b(Unknown Source)
E/HttpOperation( 6570): 	at ihi.a(PG:19)
E/HttpOperation( 6570): 	... 10 more
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
D/SecContentProvider2(  840): mCursor = null
,D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6570): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6570): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6570): 	at kfv.a(PG:65)
E/HttpOperation( 6570): 	at kff.u(PG:385)
E/HttpOperation( 6570): 	at kfb.a(PG:29)
E/HttpOperation( 6570): 	at kff.l(PG:132)
E/HttpOperation( 6570): 	at ieo.a(PG:43)
E/HttpOperation( 6570): 	at iep.a(PG:93)
E/HttpOperation( 6570): 	at fhn.a(PG:59)
E/HttpOperation( 6570): 	at lex.a(PG:85)
E/HttpOperation( 6570): 	at lex.b(PG:132)
E/HttpOperation( 6570): 	at fhk.a(PG:1146)
E/HttpOperation( 6570): 	at fhk.a(PG:908)
E/HttpOperation( 6570): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6570): 	at ihi.a(PG:22)
E/HttpOperation( 6570): 	at kft.a(PG:91)
E/HttpOperation( 6570): 	at kfv.a(PG:62)
E/HttpOperation( 6570): 	... 12 more
E/HttpOperation( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6570): 	at gde.c(Unknown Source)
E/HttpOperation( 6570): 	at gde.b(Unknown Source)
E/HttpOperation( 6570): 	at ihi.a(PG:19)
E/HttpOperation( 6570): 	... 14 more
,E/ExperimentLoader( 6570): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6570): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6570): 	at kfv.a(PG:65)
E/ExperimentLoader( 6570): 	at kff.u(PG:385)
E/ExperimentLoader( 6570): 	at kfb.a(PG:29)
E/ExperimentLoader( 6570): 	at kff.l(PG:132)
E/ExperimentLoader( 6570): 	at ieo.a(PG:43)
E/ExperimentLoader( 6570): 	at iep.a(PG:93)
E/ExperimentLoader( 6570): 	at fhn.a(PG:59)
E/ExperimentLoader( 6570): 	at lex.a(PG:85)
E/ExperimentLoader( 6570): 	at lex.b(PG:132)
E/ExperimentLoader( 6570): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6570): 	at fhk.a(PG:908)
E/ExperimentLoader( 6570): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6570): 	at ihi.a(PG:22)
E/ExperimentLoader( 6570): 	at kft.a(PG:91)
E/ExperimentLoader( 6570): 	at kfv.a(PG:62)
E/ExperimentLoader( 6570): 	... 12 more
E/ExperimentLoader( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6570): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6570): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6570): 	at ihi.a(PG:19)
E/ExperimentLoader( 6570): 	... 14 more
I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
D/SecContentProvider2(  840): mCursor = null
D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6570): [getaccountstatus] Unexpected exception
E/HttpOperation( 6570): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6570): 	at kfv.a(PG:65)
E/HttpOperation( 6570): 	at kff.u(PG:385)
E/HttpOperation( 6570): 	at kfb.a(PG:29)
E/HttpOperation( 6570): 	at ixd.a(PG:248)
E/HttpOperation( 6570): 	at ixd.b(PG:206)
E/HttpOperation( 6570): 	at ixd.a(PG:175)
E/HttpOperation( 6570): 	at fig.a(PG:78)
E/HttpOperation( 6570): 	at lex.a(PG:85)
E/HttpOperation( 6570): 	at lex.b(PG:132)
E/HttpOperation( 6570): 	at fhk.a(PG:1146)
E/HttpOperation( 6570): 	at fhk.a(PG:908)
E/HttpOperation( 6570): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6570): 	at ihi.a(PG:22)
E/HttpOperation( 6570): 	at kft.a(PG:91)
E/HttpOperation( 6570): 	at kfv.a(PG:62)
E/HttpOperation( 6570): 	... 12 more
E/HttpOperation( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6570): 	at gde.c(Unknown Source)
E/HttpOperation( 6570): 	at gde.b(Unknown Source)
E/HttpOperation( 6570): 	at ihi.a(PG:19)
E/HttpOperation( 6570): 	... 14 more
E/EsSyncAdapterService( 6570): Sync failure
E/EsSyncAdapterService( 6570): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6570): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6570): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6570): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6570): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6570): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6570): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6570): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6570): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6570): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6570): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6570): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6570): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6570): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6570): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6570): 	... 10 more
E/EsSyncAdapterService( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6570): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6570): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6570): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6570): 	... 12 more
E/EsSyncAdapterService( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6570): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6570): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6570): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6570): 	... 14 more
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
D/SyncManager(  840): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 182556, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  840): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  840): mCursor = null
,E/SQLiteLog( 1676): (10) POSIX Error : 11 SQLite Error : 3850
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 5
,I/PowerManagerService(  840): [PWL] Off : 50s ago
,D/SSRM:m  (  840): SIOP:: AP = 310, PST = 343, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  840): waitForAlarm result :4
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  840): stay LED for fully charged
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  840): !@Sync 6
,E/SMD     (  282): DCD ON
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6601): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6601): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6601): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 310, PST = 337, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 300, PST = 325, CUR = 300
,V/AlarmManager(  840): waitForAlarm result :4
,E/SMD     (  282): DCD ON
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  840): stay LED for fully charged
D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  341): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  341): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  840): [PWL] Off : 75s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 300, PST = 317, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/Watchdog(  840): !@Sync 7
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 300, PST = 313, CUR = 300
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 300, PST = 309, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :4
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  840): stay LED for fully charged
D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7446): Starting books sync, d
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7446): Authentication error
E/BooksAccountManager( 7446): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7446): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7446): null auth token
,I/qtaguid ( 7446): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7446, getuid(): 10082
,I/qtaguid ( 7446): Untagging socket 34
,W/ApiaryClient( 7446): Error response from books API: {
W/ApiaryClient( 7446):  "error": {
W/ApiaryClient( 7446):   "errors": [
W/ApiaryClient( 7446):    {
W/ApiaryClient( 7446):     "domain": "global",
W/ApiaryClient( 7446):     "reason": "required",
W/ApiaryClient( 7446):     "message": "Login Required",
W/ApiaryClient( 7446):     "locationType": "header",
W/ApiaryClient( 7446):     "location": "Authorization"
W/ApiaryClient( 7446):    }
W/ApiaryClient( 7446):   ],
W/ApiaryClient( 7446):   "code": 401,
W/ApiaryClient( 7446):   "message": "Login Required"
W/ApiaryClient( 7446):  }
W/ApiaryClient( 7446): }
,W/ApiaryClient( 7446): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6754436400064475473&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7446): Headers suppressed
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1676): Explicit concurrent mark sweep GC freed 61255(3MB) AllocSpace objects, 55(3MB) LOS objects, 39% free, 18MB/30MB, paused 824us total 98.526ms
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1676): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
,D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7446): Authentication error
E/BooksAccountManager( 7446): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7446): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7446): null auth token
,I/qtaguid ( 7446): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7446, getuid(): 10082
,I/qtaguid ( 7446): Untagging socket 34
,W/ApiaryClient( 7446): Error response from books API: {
W/ApiaryClient( 7446):  "error": {
W/ApiaryClient( 7446):   "errors": [
W/ApiaryClient( 7446):    {
W/ApiaryClient( 7446):     "domain": "global",
W/ApiaryClient( 7446):     "reason": "required",
W/ApiaryClient( 7446):     "message": "Login Required",
W/ApiaryClient( 7446):     "locationType": "header",
W/ApiaryClient( 7446):     "location": "Authorization"
W/ApiaryClient( 7446):    }
W/ApiaryClient( 7446):   ],
W/ApiaryClient( 7446):   "code": 401,
W/ApiaryClient( 7446):   "message": "Login Required"
W/ApiaryClient( 7446):  }
W/ApiaryClient( 7446): }
,W/ApiaryClient( 7446): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6754436400064475473&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7446): Headers suppressed
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  840): [PWL] Off : 105s ago
,I/PowerManagerService(  840): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  840): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  840): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=840, ws=WorkSource{10082}) (elapsedTime=2699)
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  282): DCD ON
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
,D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7446): Authentication error
E/BooksAccountManager( 7446): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7446): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7446): null auth token
,I/qtaguid ( 7446): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7446, getuid(): 10082
,I/qtaguid ( 7446): Untagging socket 34
,W/ApiaryClient( 7446): Error response from books API: {
W/ApiaryClient( 7446):  "error": {
W/ApiaryClient( 7446):   "errors": [
W/ApiaryClient( 7446):    {
W/ApiaryClient( 7446):     "domain": "global",
W/ApiaryClient( 7446):     "reason": "required",
W/ApiaryClient( 7446):     "message": "Login Required",
W/ApiaryClient( 7446):     "locationType": "header",
W/ApiaryClient( 7446):     "location": "Authorization"
W/ApiaryClient( 7446):    }
W/ApiaryClient( 7446):   ],
W/ApiaryClient( 7446):   "code": 401,
W/ApiaryClient( 7446):   "message": "Login Required"
W/ApiaryClient( 7446):  }
W/ApiaryClient( 7446): }
,W/ApiaryClient( 7446): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6754436400064475473&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7446): Headers suppressed
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7446): Soft error
E/BooksSync( 7446): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6754436400064475473&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7446): Headers suppressed
E/BooksSync( 7446): 
E/BooksSync( 7446): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7446): Sync error
E/BooksSync( 7446): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6754436400064475473&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7446): Headers suppressed
E/BooksSync( 7446): 
E/BooksSync( 7446): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7446): Finished books sync
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  840): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 218202, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  840): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  840): mCursor = null
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/SSRM:m  (  840): SIOP:: AP = 300, PST = 306, CUR = 300
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 3
,E/Watchdog(  840): !@Sync 8
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 300, PST = 304, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :8
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 302, CUR = 300
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  840): stay LED for fully charged
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ResourcesManager( 1676): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
D/SecContentProvider2(  840): mCursor = null
,D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6570): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6570): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6570): 	at kfv.a(PG:65)
E/HttpOperation( 6570): 	at kff.u(PG:385)
E/HttpOperation( 6570): 	at kfb.a(PG:29)
E/HttpOperation( 6570): 	at kff.l(PG:132)
E/HttpOperation( 6570): 	at dsf.a(PG:807)
E/HttpOperation( 6570): 	at fhk.a(PG:1126)
E/HttpOperation( 6570): 	at fhk.a(PG:908)
E/HttpOperation( 6570): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6570): 	at ihi.a(PG:22)
E/HttpOperation( 6570): 	at kft.a(PG:91)
E/HttpOperation( 6570): 	at kfv.a(PG:62)
E/HttpOperation( 6570): 	... 8 more
E/HttpOperation( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6570): 	at gde.c(Unknown Source)
E/HttpOperation( 6570): 	at gde.b(Unknown Source)
E/HttpOperation( 6570): 	at ihi.a(PG:19)
E/HttpOperation( 6570): 	... 10 more
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
D/SecContentProvider2(  840): mCursor = null
,D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
E/HttpOperation( 6570): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6570): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6570): 	at kfv.a(PG:65)
E/HttpOperation( 6570): 	at kff.u(PG:385)
E/HttpOperation( 6570): 	at kfb.a(PG:29)
E/HttpOperation( 6570): 	at kff.l(PG:132)
E/HttpOperation( 6570): 	at ieo.a(PG:43)
E/HttpOperation( 6570): 	at iep.a(PG:93)
E/HttpOperation( 6570): 	at fhn.a(PG:59)
E/HttpOperation( 6570): 	at lex.a(PG:85)
E/HttpOperation( 6570): 	at lex.b(PG:132)
E/HttpOperation( 6570): 	at fhk.a(PG:1146)
E/HttpOperation( 6570): 	at fhk.a(PG:908)
E/HttpOperation( 6570): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6570): 	at ihi.a(PG:22)
E/HttpOperation( 6570): 	at kft.a(PG:91)
E/HttpOperation( 6570): 	at kfv.a(PG:62)
E/HttpOperation( 6570): 	... 12 more
E/HttpOperation( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6570): 	at gde.c(Unknown Source)
E/HttpOperation( 6570): 	at gde.b(Unknown Source)
E/HttpOperation( 6570): 	at ihi.a(PG:19)
E/HttpOperation( 6570): 	... 14 more
E/ExperimentLoader( 6570): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6570): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6570): 	at kfv.a(PG:65)
E/ExperimentLoader( 6570): 	at kff.u(PG:385)
E/ExperimentLoader( 6570): 	at kfb.a(PG:29)
E/ExperimentLoader( 6570): 	at kff.l(PG:132)
E/ExperimentLoader( 6570): 	at ieo.a(PG:43)
E/ExperimentLoader( 6570): 	at iep.a(PG:93)
E/ExperimentLoader( 6570): 	at fhn.a(PG:59)
E/ExperimentLoader( 6570): 	at lex.a(PG:85)
E/ExperimentLoader( 6570): 	at lex.b(PG:132)
E/ExperimentLoader( 6570): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6570): 	at fhk.a(PG:908)
E/ExperimentLoader( 6570): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6570): 	at ihi.a(PG:22)
E/ExperimentLoader( 6570): 	at kft.a(PG:91)
E/ExperimentLoader( 6570): 	at kfv.a(PG:62)
E/ExperimentLoader( 6570): 	... 12 more
E/ExperimentLoader( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6570): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6570): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6570): 	at ihi.a(PG:19)
E/ExperimentLoader( 6570): 	... 14 more
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,E/SQLiteLog( 1676): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
,D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,E/HttpOperation( 6570): [getaccountstatus] Unexpected exception
E/HttpOperation( 6570): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6570): 	at kfv.a(PG:65)
E/HttpOperation( 6570): 	at kff.u(PG:385)
E/HttpOperation( 6570): 	at kfb.a(PG:29)
E/HttpOperation( 6570): 	at ixd.a(PG:248)
E/HttpOperation( 6570): 	at ixd.b(PG:206)
E/HttpOperation( 6570): 	at ixd.a(PG:175)
E/HttpOperation( 6570): 	at fig.a(PG:78)
E/HttpOperation( 6570): 	at lex.a(PG:85)
E/HttpOperation( 6570): 	at lex.b(PG:132)
E/HttpOperation( 6570): 	at fhk.a(PG:1146)
E/HttpOperation( 6570): 	at fhk.a(PG:908)
E/HttpOperation( 6570): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6570): 	at ihi.a(PG:22)
E/HttpOperation( 6570): 	at kft.a(PG:91)
E/HttpOperation( 6570): 	at kfv.a(PG:62)
E/HttpOperation( 6570): 	... 12 more
E/HttpOperation( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6570): 	at gde.c(Unknown Source)
E/HttpOperation( 6570): 	at gde.b(Unknown Source)
E/HttpOperation( 6570): 	at ihi.a(PG:19)
E/HttpOperation( 6570): 	... 14 more
,E/EsSyncAdapterService( 6570): Sync failure
E/EsSyncAdapterService( 6570): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6570): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6570): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6570): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6570): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6570): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6570): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6570): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6570): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6570): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6570): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6570): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6570): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6570): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6570): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6570): 	... 10 more
E/EsSyncAdapterService( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6570): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6570): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6570): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6570): 	... 12 more
E/EsSyncAdapterService( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6570): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6570): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6570): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6570): 	... 14 more
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  840): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 247472, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  840): Explicit concurrent mark sweep GC freed 47826(2MB) AllocSpace objects, 40(1225KB) LOS objects, 30% free, 36MB/52MB, paused 1.564ms total 108.603ms
,D/SecContentProvider2(  840): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  840): mCursor = null
,E/SQLiteLog( 1676): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  840): [PWL] Off : 140s ago
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 300, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  840): !@Sync 9
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 298, CUR = 300
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 296, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :4
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/BatteryService(  840): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 295, CUR = 300
,E/SMD     (  282): DCD ON
,D/TimaService(  840): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  840): TimaServiceHandler.handleMessage what =1
,D/TimaService(  840): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  840): initializing...
,I/TLC_TIMA_PKM_initialize(  840): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  840): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  840): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  840): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  840): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  840): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  840): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  840): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  840): App is not loaded in QSEE
,D/QSEECOMAPI: (  840): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  840): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  840): Trustlet response is completed
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  840): !@Sync 10
,E/SMD     (  282): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  840): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  840): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  840): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  840): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  840): [PWL] Off : 180s ago,
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 294, CUR = 300
,E/SMD     (  282): DCD ON
,I/Atfwd_Sendcmd(  341): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  341): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 293, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  840): stay LED for fully charged
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7446): Starting books sync, d
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7446): Authentication error
E/BooksAccountManager( 7446): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7446): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7446): null auth token
,I/qtaguid ( 7446): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7446, getuid(): 10082
,I/qtaguid ( 7446): Untagging socket 34
,W/ApiaryClient( 7446): Error response from books API: {
W/ApiaryClient( 7446):  "error": {
W/ApiaryClient( 7446):   "errors": [
W/ApiaryClient( 7446):    {
W/ApiaryClient( 7446):     "domain": "global",
W/ApiaryClient( 7446):     "reason": "required",
W/ApiaryClient( 7446):     "message": "Login Required",
W/ApiaryClient( 7446):     "locationType": "header",
W/ApiaryClient( 7446):     "location": "Authorization"
W/ApiaryClient( 7446):    }
W/ApiaryClient( 7446):   ],
W/ApiaryClient( 7446):   "code": 401,
W/ApiaryClient( 7446):   "message": "Login Required"
W/ApiaryClient( 7446):  }
W/ApiaryClient( 7446): }
,W/ApiaryClient( 7446): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3443190280215369684&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7446): Headers suppressed
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  840): waitForAlarm result :4
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8594): MountEmulatedStorage()
,I/ActivityManager(  840): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8594 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 8594): v2
I/libpersona( 8594): KNOX_SDCARD checking this for 10081
I/libpersona( 8594): KNOX_SDCARD not a persona
,I/SELinux ( 8594): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8594): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8594): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/art     (  314): Explicit concurrent mark sweep GC freed 8704(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 534us total 36.271ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 392us total 12ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 390us total 21.512ms
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 8594): TimaSignature is unavailable
,D/ActivityThread( 8594): Added TimaKeyStore provider
,D/ResourcesManager( 8594): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7446): Authentication error
E/BooksAccountManager( 7446): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7446): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7446): null auth token
,I/qtaguid ( 7446): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7446, getuid(): 10082
,I/qtaguid ( 7446): Untagging socket 34
,W/ApiaryClient( 7446): Error response from books API: {
W/ApiaryClient( 7446):  "error": {
W/ApiaryClient( 7446):   "errors": [
W/ApiaryClient( 7446):    {
W/ApiaryClient( 7446):     "domain": "global",
W/ApiaryClient( 7446):     "reason": "required",
W/ApiaryClient( 7446):     "message": "Login Required",
W/ApiaryClient( 7446):     "locationType": "header",
W/ApiaryClient( 7446):     "location": "Authorization"
W/ApiaryClient( 7446):    }
W/ApiaryClient( 7446):   ],
W/ApiaryClient( 7446):   "code": 401,
W/ApiaryClient( 7446):   "message": "Login Required"
W/ApiaryClient( 7446):  }
W/ApiaryClient( 7446): }
,W/ApiaryClient( 7446): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3443190280215369684&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7446): Headers suppressed
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7446): Authentication error
E/BooksAccountManager( 7446): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7446): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7446): null auth token
,I/qtaguid ( 7446): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7446, getuid(): 10082
,I/qtaguid ( 7446): Untagging socket 34
,W/ApiaryClient( 7446): Error response from books API: {
W/ApiaryClient( 7446):  "error": {
W/ApiaryClient( 7446):   "errors": [
W/ApiaryClient( 7446):    {
W/ApiaryClient( 7446):     "domain": "global",
W/ApiaryClient( 7446):     "reason": "required",
W/ApiaryClient( 7446):     "message": "Login Required",
W/ApiaryClient( 7446):     "locationType": "header",
W/ApiaryClient( 7446):     "location": "Authorization"
W/ApiaryClient( 7446):    }
W/ApiaryClient( 7446):   ],,
W/ApiaryClient( 7446):   "code": 401,
W/ApiaryClient( 7446):   "message": "Login Required"
W/ApiaryClient( 7446):  }
W/ApiaryClient( 7446): }
,W/ApiaryClient( 7446): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3443190280215369684&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7446): Headers suppressed
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7446): Soft error
E/BooksSync( 7446): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3443190280215369684&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7446): Headers suppressed
E/BooksSync( 7446): 
E/BooksSync( 7446): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7446): Sync error
E/BooksSync( 7446): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3443190280215369684&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7446): Headers suppressed
E/BooksSync( 7446): 
E/BooksSync( 7446): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7446): Finished books sync
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  840): Killing 7369:com.sec.android.widgetapp.digitalclock/u0a94 (adj 15): bgCount ##41
,D/SyncManager(  840): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 311344, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2854): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 2854): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  840): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  840): mCursor = null
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  840): failed to open /acct/uid_10094/pid_7369/cgroup.procs: No such file or directory
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 292, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  840): !@Sync 11
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 291, CUR = 300
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  282): DCD ON
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1676): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_store.png
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6601): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6601): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6601): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6601): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6601): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6601): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6601): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 6601): Ignoring header User-Agent because its value was null.
,I/System.out( 6601): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6601): (HTTPLog)-Static: isShipBuild true
I/System.out( 6601): (HTTPLog)-Thread-1098-442993622: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :4
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  840): stay LED for fully charged
D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/PowerManagerService(  840): [PWL] Off : 225s ago
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  840): !@Sync 12
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON,
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,E/SMD     (  282): DCD ON
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/AlarmManager(  840): waitForAlarm result :8
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,E/HttpOperation( 6570): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6570): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6570): 	at kfv.a(PG:65)
E/HttpOperation( 6570): 	at kff.u(PG:385)
E/HttpOperation( 6570): 	at kfb.a(PG:29)
E/HttpOperation( 6570): 	at kff.l(PG:132)
E/HttpOperation( 6570): 	at dsf.a(PG:807)
E/HttpOperation( 6570): 	at fhk.a(PG:1126)
E/HttpOperation( 6570): 	at fhk.a(PG:908)
E/HttpOperation( 6570): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6570): 	at ihi.a(PG:22)
E/HttpOperation( 6570): 	at kft.a(PG:91)
E/HttpOperation( 6570): 	at kfv.a(PG:62)
E/HttpOperation( 6570): 	... 8 more
E/HttpOperation( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6570): 	at gde.c(Unknown Source)
E/HttpOperation( 6570): 	at gde.b(Unknown Source)
E/HttpOperation( 6570): 	at ihi.a(PG:19)
E/HttpOperation( 6570): 	... 10 more
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
D/SecContentProvider2(  840): mCursor = null
,D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6570): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6570): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6570): 	at kfv.a(PG:65)
E/HttpOperation( 6570): 	at kff.u(PG:385)
E/HttpOperation( 6570): 	at kfb.a(PG:29)
E/HttpOperation( 6570): 	at kff.l(PG:132)
E/HttpOperation( 6570): 	at ieo.a(PG:43)
E/HttpOperation( 6570): 	at iep.a(PG:93)
E/HttpOperation( 6570): 	at fhn.a(PG:59)
E/HttpOperation( 6570): 	at lex.a(PG:85)
E/HttpOperation( 6570): 	at lex.b(PG:132)
E/HttpOperation( 6570): 	at fhk.a(PG:1146)
E/HttpOperation( 6570): 	at fhk.a(PG:908)
E/HttpOperation( 6570): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6570): 	at ihi.a(PG:22)
E/HttpOperation( 6570): 	at kft.a(PG:91)
E/HttpOperation( 6570): 	at kfv.a(PG:62)
E/HttpOperation( 6570): 	... 12 more
E/HttpOperation( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6570): 	at gde.c(Unknown Source)
E/HttpOperation( 6570): 	at gde.b(Unknown Source)
E/HttpOperation( 6570): 	at ihi.a(PG:19)
E/HttpOperation( 6570): 	... 14 more
E/ExperimentLoader( 6570): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6570): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6570): 	at kfv.a(PG:65)
E/ExperimentLoader( 6570): 	at kff.u(PG:385)
E/ExperimentLoader( 6570): 	at kfb.a(PG:29)
E/ExperimentLoader( 6570): 	at kff.l(PG:132)
E/ExperimentLoader( 6570): 	at ieo.a(PG:43)
E/ExperimentLoader( 6570): 	at iep.a(PG:93)
E/ExperimentLoader( 6570): 	at fhn.a(PG:59)
E/ExperimentLoader( 6570): 	at lex.a(PG:85)
E/ExperimentLoader( 6570): 	at lex.b(PG:132)
E/ExperimentLoader( 6570): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6570): 	at fhk.a(PG:908)
E/ExperimentLoader( 6570): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6570): 	at ihi.a(PG:22)
E/ExperimentLoader( 6570): 	at kft.a(PG:91)
E/ExperimentLoader( 6570): 	at kfv.a(PG:62)
E/ExperimentLoader( 6570): 	... 12 more
E/ExperimentLoader( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6570): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6570): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6570): 	at ihi.a(PG:19)
E/ExperimentLoader( 6570): 	... 14 more
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
,D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6570): [getaccountstatus] Unexpected exception
E/HttpOperation( 6570): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6570): 	at kfv.a(PG:65)
E/HttpOperation( 6570): 	at kff.u(PG:385)
E/HttpOperation( 6570): 	at kfb.a(PG:29)
E/HttpOperation( 6570): 	at ixd.a(PG:248)
E/HttpOperation( 6570): 	at ixd.b(PG:206)
E/HttpOperation( 6570): 	at ixd.a(PG:175)
E/HttpOperation( 6570): 	at fig.a(PG:78)
E/HttpOperation( 6570): 	at lex.a(PG:85)
E/HttpOperation( 6570): 	at lex.b(PG:132)
E/HttpOperation( 6570): 	at fhk.a(PG:1146)
E/HttpOperation( 6570): 	at fhk.a(PG:908)
E/HttpOperation( 6570): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6570): 	at ihi.a(PG:22)
E/HttpOperation( 6570): 	at kft.a(PG:91)
E/HttpOperation( 6570): 	at kfv.a(PG:62)
E/HttpOperation( 6570): 	... 12 more
E/HttpOperation( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6570): 	at gde.c(Unknown Source)
E/HttpOperation( 6570): 	at gde.b(Unknown Source)
E/HttpOperation( 6570): 	at ihi.a(PG:19)
E/HttpOperation( 6570): 	... 14 more
,E/EsSyncAdapterService( 6570): Sync failure
E/EsSyncAdapterService( 6570): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6570): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6570): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6570): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6570): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6570): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6570): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6570): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6570): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6570): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6570): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6570): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6570): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6570): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6570): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6570): 	... 10 more
E/EsSyncAdapterService( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6570): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6570): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6570): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6570): 	... 12 more
E/EsSyncAdapterService( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6570): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6570): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6570): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6570): 	... 14 more
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  840): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 395691, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  840): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  840): mCursor = null
,E/SQLiteLog( 1676): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 13
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 5
,I/PowerManagerService(  840): [PWL] Off : 275s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :4
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  840): !@Sync 14
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/Atfwd_Sendcmd(  341): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  341): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  840): stay LED for fully charged
D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  840): !@Sync 15
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/PowerManagerService(  840): [PWL] Off : 330s ago
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/bootchecker(  337): bootchecker wake up!!
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/AlarmManager(  840): waitForAlarm result :4
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  840): stay LED for fully charged
D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7446): Starting books sync, d
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7446): Authentication error
E/BooksAccountManager( 7446): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7446): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7446): null auth token
,I/qtaguid ( 7446): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7446, getuid(): 10082
,I/qtaguid ( 7446): Untagging socket 34
,W/ApiaryClient( 7446): Error response from books API: {
W/ApiaryClient( 7446):  "error": {
W/ApiaryClient( 7446):   "errors": [
W/ApiaryClient( 7446):    {
W/ApiaryClient( 7446):     "domain": "global",
W/ApiaryClient( 7446):     "reason": "required",
W/ApiaryClient( 7446):     "message": "Login Required",
W/ApiaryClient( 7446):     "locationType": "header",
W/ApiaryClient( 7446):     "location": "Authorization"
W/ApiaryClient( 7446):    }
W/ApiaryClient( 7446):   ],
W/ApiaryClient( 7446):   "code": 401,
W/ApiaryClient( 7446):   "message": "Login Required"
W/ApiaryClient( 7446):  }
W/ApiaryClient( 7446): }
,W/ApiaryClient( 7446): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3727272374081054863&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7446): Headers suppressed
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 3
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7446): Authentication error
E/BooksAccountManager( 7446): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7446): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7446): null auth token
,I/qtaguid ( 7446): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7446, getuid(): 10082
,I/qtaguid ( 7446): Untagging socket 34
,W/ApiaryClient( 7446): Error response from books API: {
W/ApiaryClient( 7446):  "error": {
W/ApiaryClient( 7446):   "errors": [
W/ApiaryClient( 7446):    {
W/ApiaryClient( 7446):     "domain": "global",
W/ApiaryClient( 7446):     "reason": "required",
W/ApiaryClient( 7446):     "message": "Login Required",
W/ApiaryClient( 7446):     "locationType": "header",
W/ApiaryClient( 7446):     "location": "Authorization"
W/ApiaryClient( 7446):    }
W/ApiaryClient( 7446):   ],
W/ApiaryClient( 7446):   "code": 401,
W/ApiaryClient( 7446):   "message": "Login Required"
W/ApiaryClient( 7446):  }
W/ApiaryClient( 7446): }
,W/ApiaryClient( 7446): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3727272374081054863&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7446): Headers suppressed
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1676): Explicit concurrent mark sweep GC freed 40903(2MB) AllocSpace objects, 31(2MB) LOS objects, 40% free, 18MB/30MB, paused 1.021ms total 70.726ms
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1676): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7446): Authentication error
E/BooksAccountManager( 7446): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7446): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7446): null auth token
,I/qtaguid ( 7446): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7446, getuid(): 10082
,I/qtaguid ( 7446): Untagging socket 34
,W/ApiaryClient( 7446): Error response from books API: {
W/ApiaryClient( 7446):  "error": {
W/ApiaryClient( 7446):   "errors": [
W/ApiaryClient( 7446):    {
W/ApiaryClient( 7446):     "domain": "global",
W/ApiaryClient( 7446):     "reason": "required",
W/ApiaryClient( 7446):     "message": "Login Required",
W/ApiaryClient( 7446):     "locationType": "header",
W/ApiaryClient( 7446):     "location": "Authorization"
W/ApiaryClient( 7446):    }
W/ApiaryClient( 7446):   ],
W/ApiaryClient( 7446):   "code": 401,
W/ApiaryClient( 7446):   "message": "Login Required"
W/ApiaryClient( 7446):  }
W/ApiaryClient( 7446): }
,W/ApiaryClient( 7446): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3727272374081054863&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7446): Headers suppressed
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7446): Soft error
E/BooksSync( 7446): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3727272374081054863&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7446): Headers suppressed
E/BooksSync( 7446): 
E/BooksSync( 7446): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7446): Sync error
E/BooksSync( 7446): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3727272374081054863&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7446): Headers suppressed
E/BooksSync( 7446): 
E/BooksSync( 7446): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7446): Finished books sync
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  840): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 467645, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/art     (  840): Explicit concurrent mark sweep GC freed 57469(3MB) AllocSpace objects, 77(1882KB) LOS objects, 30% free, 36MB/52MB, paused 1.609ms total 127.477ms
,D/SecContentProvider2(  840): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  840): mCursor = null
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  840): !@Sync 16
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  840): stay LED for fully charged
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/AlarmManager(  840): waitForAlarm result :8
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): stay LED for fully charged
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
I/MotionRecognitionService(  840): setPowerConnected  = true
D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  840): !@Sync 17
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,D/BatteryService(  840): stay LED for fully charged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/PowerManagerService(  840): [PWL] Off : 390s ago
,E/SMD     (  282): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  840): !@Sync 18
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/Atfwd_Sendcmd(  341): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  341): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :8
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,I/Atfwd_Daemon(  341): Stop the daemon....
,E/Watchdog(  840): !@Sync 19
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  840): [PWL] Off : 455s ago
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,D/TimaService(  840): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  840): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  840): TimaServiceHandler.handleMessage what =1
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  840): !@Sync 20
,E/SMD     (  282): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  840): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  840): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  840): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  840): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  840): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  840): stay LED for fully charged
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
I/MotionRecognitionService(  840): setPowerConnected  = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ResourcesManager( 1676): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
,D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6570): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6570): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6570): 	at kfv.a(PG:65)
E/HttpOperation( 6570): 	at kff.u(PG:385)
E/HttpOperation( 6570): 	at kfb.a(PG:29)
E/HttpOperation( 6570): 	at kff.l(PG:132)
E/HttpOperation( 6570): 	at dsf.a(PG:807)
E/HttpOperation( 6570): 	at fhk.a(PG:1126)
E/HttpOperation( 6570): 	at fhk.a(PG:908)
E/HttpOperation( 6570): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6570): 	at ihi.a(PG:22)
E/HttpOperation( 6570): 	at kft.a(PG:91)
E/HttpOperation( 6570): 	at kfv.a(PG:62)
E/HttpOperation( 6570): 	... 8 more
E/HttpOperation( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6570): 	at gde.c(Unknown Source)
E/HttpOperation( 6570): 	at gde.b(Unknown Source)
E/HttpOperation( 6570): 	at ihi.a(PG:19)
E/HttpOperation( 6570): 	... 10 more
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,E/Watchdog(  840): !@Sync 21
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
D/SecContentProvider2(  840): mCursor = null
D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6570): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6570): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6570): 	at kfv.a(PG:65)
E/HttpOperation( 6570): 	at kff.u(PG:385)
E/HttpOperation( 6570): 	at kfb.a(PG:29)
E/HttpOperation( 6570): 	at kff.l(PG:132)
E/HttpOperation( 6570): 	at ieo.a(PG:43)
E/HttpOperation( 6570): 	at iep.a(PG:93)
E/HttpOperation( 6570): 	at fhn.a(PG:59)
E/HttpOperation( 6570): 	at lex.a(PG:85)
E/HttpOperation( 6570): 	at lex.b(PG:132)
E/HttpOperation( 6570): 	at fhk.a(PG:1146)
E/HttpOperation( 6570): 	at fhk.a(PG:908)
E/HttpOperation( 6570): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6570): 	at ihi.a(PG:22)
E/HttpOperation( 6570): 	at kft.a(PG:91)
E/HttpOperation( 6570): 	at kfv.a(PG:62)
E/HttpOperation( 6570): 	... 12 more
E/HttpOperation( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6570): 	at gde.c(Unknown Source)
E/HttpOperation( 6570): 	at gde.b(Unknown Source)
E/HttpOperation( 6570): 	at ihi.a(PG:19)
E/HttpOperation( 6570): 	... 14 more
E/ExperimentLoader( 6570): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6570): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6570): 	at kfv.a(PG:65)
E/ExperimentLoader( 6570): 	at kff.u(PG:385)
E/ExperimentLoader( 6570): 	at kfb.a(PG:29)
E/ExperimentLoader( 6570): 	at kff.l(PG:132)
E/ExperimentLoader( 6570): 	at ieo.a(PG:43)
E/ExperimentLoader( 6570): 	at iep.a(PG:93)
E/ExperimentLoader( 6570): 	at fhn.a(PG:59)
E/ExperimentLoader( 6570): 	at lex.a(PG:85)
E/ExperimentLoader( 6570): 	at lex.b(PG:132)
E/ExperimentLoader( 6570): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6570): 	at fhk.a(PG:908)
E/ExperimentLoader( 6570): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6570): 	at ihi.a(PG:22)
E/ExperimentLoader( 6570): 	at kft.a(PG:91)
E/ExperimentLoader( 6570): 	at kfv.a(PG:62)
E/ExperimentLoader( 6570): 	... 12 more
E/ExperimentLoader( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6570): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6570): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6570): 	at ihi.a(PG:19)
E/ExperimentLoader( 6570): 	... 14 more
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/SMD     (  282): DCD ON
I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
,D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6570): [getaccountstatus] Unexpected exception
E/HttpOperation( 6570): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6570): 	at kfv.a(PG:65)
E/HttpOperation( 6570): 	at kff.u(PG:385)
E/HttpOperation( 6570): 	at kfb.a(PG:29)
E/HttpOperation( 6570): 	at ixd.a(PG:248)
E/HttpOperation( 6570): 	at ixd.b(PG:206)
E/HttpOperation( 6570): 	at ixd.a(PG:175)
E/HttpOperation( 6570): 	at fig.a(PG:78)
E/HttpOperation( 6570): 	at lex.a(PG:85)
E/HttpOperation( 6570): 	at lex.b(PG:132)
E/HttpOperation( 6570): 	at fhk.a(PG:1146)
E/HttpOperation( 6570): 	at fhk.a(PG:908)
E/HttpOperation( 6570): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6570): 	at ihi.a(PG:22)
E/HttpOperation( 6570): 	at kft.a(PG:91)
E/HttpOperation( 6570): 	at kfv.a(PG:62)
E/HttpOperation( 6570): 	... 12 more
E/HttpOperation( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6570): 	at gde.c(Unknown Source)
E/HttpOperation( 6570): 	at gde.b(Unknown Source)
E/HttpOperation( 6570): 	at ihi.a(PG:19)
E/HttpOperation( 6570): 	... 14 more
E/EsSyncAdapterService( 6570): Sync failure
E/EsSyncAdapterService( 6570): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6570): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6570): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6570): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6570): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6570): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6570): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6570): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6570): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6570): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6570): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6570): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6570): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6570): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6570): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6570): 	... 10 more
E/EsSyncAdapterService( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6570): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6570): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6570): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6570): 	... 12 more
E/EsSyncAdapterService( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6570): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6570): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6570): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6570): 	... 14 more
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
D/SyncManager(  840): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 642696, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  840): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  840): mCursor = null
,E/SQLiteLog( 1676): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  840): [PWL] Off : 525s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  840): waitForAlarm result :4
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  840): !@Sync 22
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,D/BatteryService(  840): stay LED for fully charged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 280, PST = 289, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 280, PST = 288, CUR = 300
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,E/Watchdog(  840): !@Sync 23
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 286, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  840): stay LED for fully charged
D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 284, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 282, CUR = 300
,E/Watchdog(  840): !@Sync 24
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  840): [PWL] Off : 600s ago
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 280, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 278, CUR = 300
,V/AlarmManager(  840): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  840): stay LED for fully charged
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7446): Starting books sync, d
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
D/SecContentProvider2(  840): mCursor = null
,D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7446): Authentication error
E/BooksAccountManager( 7446): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7446): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7446): null auth token
,I/PhoneStatusBar( 1168): Icon Only
I/qtaguid ( 7446): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7446, getuid(): 10082
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) ,
,I/qtaguid ( 7446): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7446, getuid(): 10082
,I/qtaguid ( 7446): Untagging socket 34
,W/ApiaryClient( 7446): Error response from books API: {
W/ApiaryClient( 7446):  "error": {
W/ApiaryClient( 7446):   "errors": [
W/ApiaryClient( 7446):    {
W/ApiaryClient( 7446):     "domain": "global",
W/ApiaryClient( 7446):     "reason": "required",
W/ApiaryClient( 7446):     "message": "Login Required",
W/ApiaryClient( 7446):     "locationType": "header",
W/ApiaryClient( 7446):     "location": "Authorization"
W/ApiaryClient( 7446):    }
W/ApiaryClient( 7446):   ],
W/ApiaryClient( 7446):   "code": 401,
W/ApiaryClient( 7446):   "message": "Login Required"
W/ApiaryClient( 7446):  }
W/ApiaryClient( 7446): }
,W/ApiaryClient( 7446): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6122102268677014486&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7446): Headers suppressed
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7446): Authentication error
E/BooksAccountManager( 7446): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7446): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7446): null auth token
,I/qtaguid ( 7446): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7446, getuid(): 10082
I/qtaguid ( 7446): Tagging socket 40 with tag 10000000000{256,0} uid -1, pid: 7446, getuid(): 10082
,I/qtaguid ( 7446): Untagging socket 34
,W/ApiaryClient( 7446): Error response from books API: {
W/ApiaryClient( 7446):  "error": {
W/ApiaryClient( 7446):   "errors": [
W/ApiaryClient( 7446):    {
W/ApiaryClient( 7446):     "domain": "global",
W/ApiaryClient( 7446):     "reason": "required",
W/ApiaryClient( 7446):     "message": "Login Required",
W/ApiaryClient( 7446):     "locationType": "header",
W/ApiaryClient( 7446):     "location": "Authorization"
W/ApiaryClient( 7446):    }
W/ApiaryClient( 7446):   ],
W/ApiaryClient( 7446):   "code": 401,
W/ApiaryClient( 7446):   "message": "Login Required"
W/ApiaryClient( 7446):  }
W/ApiaryClient( 7446): }
,W/ApiaryClient( 7446): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6122102268677014486&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7446): Headers suppressed
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7446): Authentication error
E/BooksAccountManager( 7446): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7446): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7446): null auth token
,I/qtaguid ( 7446): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7446, getuid(): 10082
,I/qtaguid ( 7446): Untagging socket 34
,W/ApiaryClient( 7446): Error response from books API: {
W/ApiaryClient( 7446):  "error": {
W/ApiaryClient( 7446):   "errors": [
W/ApiaryClient( 7446):    {
W/ApiaryClient( 7446):     "domain": "global",
W/ApiaryClient( 7446):     "reason": "required",
W/ApiaryClient( 7446):     "message": "Login Required",
W/ApiaryClient( 7446):     "locationType": "header",
W/ApiaryClient( 7446):     "location": "Authorization"
W/ApiaryClient( 7446):    }
W/ApiaryClient( 7446):   ],
W/ApiaryClient( 7446):   "code": 401,
W/ApiaryClient( 7446):   "message": "Login Required"
W/ApiaryClient( 7446):  }
W/ApiaryClient( 7446): }
,W/ApiaryClient( 7446): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6122102268677014486&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7446): Headers suppressed
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7446): Soft error
E/BooksSync( 7446): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6122102268677014486&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7446): Headers suppressed
E/BooksSync( 7446): 
E/BooksSync( 7446): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7446): Sync error
E/BooksSync( 7446): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6122102268677014486&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7446): Headers suppressed
E/BooksSync( 7446): 
E/BooksSync( 7446): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7446): Finished books sync
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,D/SyncManager(  840): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 753273, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  840): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  840): mCursor = null
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 280, PST = 277, CUR = 300
,E/Watchdog(  840): !@Sync 25
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 275, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 273, CUR = 300
,V/AlarmManager(  840): waitForAlarm result :4
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 272, CUR = 300
,E/Watchdog(  840): !@Sync 26
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 271, CUR = 300
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  840): [PWL] Off : 680s ago
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 271, CUR = 300
,E/Watchdog(  840): !@Sync 27
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 271, CUR = 300
,E/Watchdog(  840): !@Sync 28
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,D/BatteryService(  840): stay LED for fully charged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 270, CUR = 300
,E/Watchdog(  840): !@Sync 29
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 270, CUR = 300
,I/PowerManagerService(  840): [PWL] Off : 765s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/TimaService(  840): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  840): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  840): TimaServiceHandler.handleMessage what =1
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 270, CUR = 300
,E/Watchdog(  840): !@Sync 30
,E/SMD     (  282): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  840): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  840): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  840): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  840): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 270, CUR = 300
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 270, CUR = 300
,E/Watchdog(  840): !@Sync 31
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,D/BatteryService(  840): stay LED for fully charged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged,
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 269, CUR = 300
,E/Watchdog(  840): !@Sync 32
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 268, CUR = 300
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,D/BatteryService(  840): stay LED for fully charged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 267, CUR = 300
,I/PowerManagerService(  840): [PWL] Off : 855s ago
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 266, CUR = 300
,E/Watchdog(  840): !@Sync 33
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :4
,D/LightsService(  840): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  840): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  840): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  840): stay LED for fully charged
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  840): Plugged
I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1676): Message class com.google.f.a.a.i
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/EventLogService( 2472): Aggregate from 1452861316055 (log), 1452861316055 (data)
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LightsService(  840): [SvcLED]  onSensorChanged::light value = 12
,E/LightSensor(  840): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  840): unregisterListener ::   
,D/LightsService(  840): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 266, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,D/BatteryService(  840): stay LED for fully charged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 265, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 264, CUR = 300
,E/Watchdog(  840): !@Sync 34
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 263, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 262, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 261, CUR = 300
,E/Watchdog(  840): !@Sync 35
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  840): [PWL] Off : 950s ago
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 261, CUR = 300
,E/Watchdog(  840): !@Sync 36
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 37
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6570): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6570): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6570): 	at kfv.a(PG:65)
E/HttpOperation( 6570): 	at kff.u(PG:385)
E/HttpOperation( 6570): 	at kfb.a(PG:29)
E/HttpOperation( 6570): 	at kff.l(PG:132)
E/HttpOperation( 6570): 	at dsf.a(PG:807)
E/HttpOperation( 6570): 	at fhk.a(PG:1126)
E/HttpOperation( 6570): 	at fhk.a(PG:908)
E/HttpOperation( 6570): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6570): 	at ihi.a(PG:22)
E/HttpOperation( 6570): 	at kft.a(PG:91)
E/HttpOperation( 6570): 	at kfv.a(PG:62)
E/HttpOperation( 6570): 	... 8 more
E/HttpOperation( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6570): 	at gde.c(Unknown Source)
E/HttpOperation( 6570): 	at gde.b(Unknown Source)
E/HttpOperation( 6570): 	at ihi.a(PG:19)
E/HttpOperation( 6570): 	... 10 more
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
,D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,E/HttpOperation( 6570): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6570): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6570): 	at kfv.a(PG:65)
E/HttpOperation( 6570): 	at kff.u(PG:385)
E/HttpOperation( 6570): 	at kfb.a(PG:29)
E/HttpOperation( 6570): 	at kff.l(PG:132)
E/HttpOperation( 6570): 	at ieo.a(PG:43)
E/HttpOperation( 6570): 	at iep.a(PG:93)
E/HttpOperation( 6570): 	at fhn.a(PG:59)
E/HttpOperation( 6570): 	at lex.a(PG:85)
E/HttpOperation( 6570): 	at lex.b(PG:132)
E/HttpOperation( 6570): 	at fhk.a(PG:1146)
E/HttpOperation( 6570): 	at fhk.a(PG:908)
E/HttpOperation( 6570): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6570): 	at ihi.a(PG:22)
E/HttpOperation( 6570): 	at kft.a(PG:91)
E/HttpOperation( 6570): 	at kfv.a(PG:62)
E/HttpOperation( 6570): 	... 12 more
E/HttpOperation( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6570): 	at gde.c(Unknown Source)
E/HttpOperation( 6570): 	at gde.b(Unknown Source)
E/HttpOperation( 6570): 	at ihi.a(PG:19)
E/HttpOperation( 6570): 	... 14 more
,E/ExperimentLoader( 6570): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6570): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6570): 	at kfv.a(PG:65)
E/ExperimentLoader( 6570): 	at kff.u(PG:385)
E/ExperimentLoader( 6570): 	at kfb.a(PG:29)
E/ExperimentLoader( 6570): 	at kff.l(PG:132)
E/ExperimentLoader( 6570): 	at ieo.a(PG:43)
E/ExperimentLoader( 6570): 	at iep.a(PG:93)
E/ExperimentLoader( 6570): 	at fhn.a(PG:59)
E/ExperimentLoader( 6570): 	at lex.a(PG:85)
E/ExperimentLoader( 6570): 	at lex.b(PG:132)
E/ExperimentLoader( 6570): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6570): 	at fhk.a(PG:908)
E/ExperimentLoader( 6570): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6570): 	at ihi.a(PG:22)
E/ExperimentLoader( 6570): 	at kft.a(PG:91)
E/ExperimentLoader( 6570): 	at kfv.a(PG:62)
E/ExperimentLoader( 6570): 	... 12 more
E/ExperimentLoader( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6570): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6570): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6570): 	at ihi.a(PG:19)
E/ExperimentLoader( 6570): 	... 14 more
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
,D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
E/HttpOperation( 6570): [getaccountstatus] Unexpected exception
E/HttpOperation( 6570): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6570): 	at kfv.a(PG:65)
E/HttpOperation( 6570): 	at kff.u(PG:385)
E/HttpOperation( 6570): 	at kfb.a(PG:29)
E/HttpOperation( 6570): 	at ixd.a(PG:248)
E/HttpOperation( 6570): 	at ixd.b(PG:206)
E/HttpOperation( 6570): 	at ixd.a(PG:175)
E/HttpOperation( 6570): 	at fig.a(PG:78)
E/HttpOperation( 6570): 	at lex.a(PG:85)
E/HttpOperation( 6570): 	at lex.b(PG:132)
E/HttpOperation( 6570): 	at fhk.a(PG:1146)
E/HttpOperation( 6570): 	at fhk.a(PG:908)
E/HttpOperation( 6570): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6570): 	at ihi.a(PG:22)
E/HttpOperation( 6570): 	at kft.a(PG:91)
E/HttpOperation( 6570): 	at kfv.a(PG:62)
E/HttpOperation( 6570): 	... 12 more
E/HttpOperation( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6570): 	at gde.c(Unknown Source)
E/HttpOperation( 6570): 	at gde.b(Unknown Source)
E/HttpOperation( 6570): 	at ihi.a(PG:19)
E/HttpOperation( 6570): 	... 14 more
,D/PanelView( 1168): There is/are notification(s) 
E/EsSyncAdapterService( 6570): Sync failure
E/EsSyncAdapterService( 6570): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6570): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6570): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6570): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6570): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6570): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6570): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6570): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6570): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6570): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6570): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6570): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6570): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6570): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6570): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6570): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6570): 	... 10 more
E/EsSyncAdapterService( 6570): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6570): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6570): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6570): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6570): 	... 12 more
E/EsSyncAdapterService( 6570): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6570): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6570): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6570): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6570): 	... 14 more
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  840): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1135792, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1676): (10) POSIX Error : 11 SQLite Error : 3850
,I/art     (  840): Explicit concurrent mark sweep GC freed 76635(6MB) AllocSpace objects, 208(3MB) LOS objects, 30% free, 36MB/52MB, paused 1.907ms total 299.627ms
,D/SecContentProvider2(  840): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  840): mCursor = null
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 270, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,D/BatteryService(  840): stay LED for fully charged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 38
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :4
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  840): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 39
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  840): [PWL] Off : 1050s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/TimaService(  840): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  840): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  840): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  840): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  840): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  840): Updating Usage Statistics in DB @ 1452863984818
,I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
,W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
,W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
,W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
,W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
,W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
,W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  840): ::getAppControlDB: Exception to create DB
W/System.err(  840): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  840): ,	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  840): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128),
W/System.err(  840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  840): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  840): Done Updating Usage Statistics in DB @ 1452863985052
,E/Watchdog(  840): !@Sync 40
,E/SMD     (  282): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  840): TIMA: response_id = 3
D/SSRM:m  (  840): SIOP:: AP = 270, PST = 262, CUR = 300
,I/TLC_TIMA_PKM_measure_kernel(  840): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  840): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  840): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 262, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 262, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 41
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 42
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  840): stay LED for fully charged
D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7446): Starting books sync, d
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 261, CUR = 300
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
,D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7446): Authentication error
E/BooksAccountManager( 7446): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7446): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7446): null auth token
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,I/qtaguid ( 7446): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7446, getuid(): 10082
,I/qtaguid ( 7446): Untagging socket 34
,W/ApiaryClient( 7446): Error response from books API: {
W/ApiaryClient( 7446):  "error": {
W/ApiaryClient( 7446):   "errors": [
W/ApiaryClient( 7446):    {
W/ApiaryClient( 7446):     "domain": "global",
W/ApiaryClient( 7446):     "reason": "required",
W/ApiaryClient( 7446):     "message": "Login Required",
W/ApiaryClient( 7446):     "locationType": "header",
W/ApiaryClient( 7446):     "location": "Authorization"
W/ApiaryClient( 7446):    }
W/ApiaryClient( 7446):   ],
W/ApiaryClient( 7446):   "code": 401,
W/ApiaryClient( 7446):   "message": "Login Required"
W/ApiaryClient( 7446):  }
W/ApiaryClient( 7446): }
,W/ApiaryClient( 7446): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4032739604437733690&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7446): Headers suppressed
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  282): DCD ON
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7446): Authentication error
E/BooksAccountManager( 7446): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7446): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7446): null auth token
,I/qtaguid ( 7446): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7446, getuid(): 10082
,I/qtaguid ( 7446): Tagging socket 41 with tag 10000000000{256,0} uid -1, pid: 7446, getuid(): 10082
,I/qtaguid ( 7446): Untagging socket 34
,W/ApiaryClient( 7446): Error response from books API: {
W/ApiaryClient( 7446):  "error": {
W/ApiaryClient( 7446):   "errors": [
W/ApiaryClient( 7446):    {
W/ApiaryClient( 7446):     "domain": "global",
W/ApiaryClient( 7446):     "reason": "required",
W/ApiaryClient( 7446):     "message": "Login Required",
W/ApiaryClient( 7446):     "locationType": "header",
W/ApiaryClient( 7446):     "location": "Authorization"
W/ApiaryClient( 7446):    }
W/ApiaryClient( 7446):   ],
W/ApiaryClient( 7446):   "code": 401,
W/ApiaryClient( 7446):   "message": "Login Required"
W/ApiaryClient( 7446):  }
W/ApiaryClient( 7446): }
,W/ApiaryClient( 7446): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4032739604437733690&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7446): Headers suppressed
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  840): waitForAlarm result :8
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1676): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  840): uri = 14 selection = getSealedState
,D/SecContentProvider2(  840): mCursor = null
,D/SecContentProvider2(  840): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  840): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  840): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1676): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1676): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1676): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1676): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1676): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7446): Authentication error
E/BooksAccountManager( 7446): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7446): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7446): null auth token
,I/qtaguid ( 7446): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7446, getuid(): 10082
,I/art     ( 1168): Explicit concurrent mark sweep GC freed 100089(4MB) AllocSpace objects, 62(5MB) LOS objects, 30% free, 37MB/53MB, paused 643us total 78.767ms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,I/qtaguid ( 7446): Untagging socket 34
,W/ApiaryClient( 7446): Error response from books API: {
W/ApiaryClient( 7446):  "error": {
W/ApiaryClient( 7446):   "errors": [
W/ApiaryClient( 7446):    {
W/ApiaryClient( 7446):     "domain": "global",
W/ApiaryClient( 7446):     "reason": "required",
W/ApiaryClient( 7446):     "message": "Login Required",
W/ApiaryClient( 7446):     "locationType": "header",
W/ApiaryClient( 7446):     "location": "Authorization"
W/ApiaryClient( 7446):    }
W/ApiaryClient( 7446):   ],
W/ApiaryClient( 7446):   "code": 401,
W/ApiaryClient( 7446):   "message": "Login Required"
W/ApiaryClient( 7446):  }
W/ApiaryClient( 7446): }
,W/ApiaryClient( 7446): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4032739604437733690&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7446): Headers suppressed
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7446): Soft error
E/BooksSync( 7446): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4032739604437733690&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7446): Headers suppressed
E/BooksSync( 7446): 
E/BooksSync( 7446): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7446): Sync error
E/BooksSync( 7446): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7446): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4032739604437733690&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7446): Headers suppressed
E/BooksSync( 7446): 
E/BooksSync( 7446): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7446): Finished books sync
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  840): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1283587, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  840): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  840): mCursor = null
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 261, CUR = 300
,I/PowerManagerService(  840): [PWL] Off : 1155s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 43
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 44
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 45
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 46
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  840): stay LED for fully charged
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  840): [PWL] Off : 1265s ago
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 47
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED,
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 48
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  840): stay LED for fully charged
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 49
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  840): stay LED for fully charged
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,D/BatteryService(  840): stay LED for fully charged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  840): stay LED for fully charged
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/TimaService(  840): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  840): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  840): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  840): !@Sync 50
,E/SMD     (  282): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  840): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  840): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  840): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  840): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  840): [PWL] Off : 1380s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 51
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 52
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 53
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 54
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  840): [PWL] Off : 1500s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 55
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 56
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  840): stay LED for fully charged
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 57
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  840): stay LED for fully charged
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 58
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  840): [PWL] Off : 1625s ago
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 59
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/NetworkStatsFactory(  840): UpdateStatsForKnox
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/BatteryService(  840): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/TimaService(  840): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  840): TimaServiceHandler.handleMessage what =1
,D/TimaService(  840): TIMA: checkEvent, operation: 50000 subject: 10000
,E/Watchdog(  840): !@Sync 60
,E/SMD     (  282): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  840): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  840): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  840): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  840): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 61
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 62
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  840): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  840): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  840): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  840):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  840): Plugged
,I/MotionRecognitionService(  840): setPowerConnected  = true
,D/BatteryService(  840): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  840): [PWL] Off : 1755s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  840): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  840): !@Sync 63
,E/SMD     (  282): DCD ON
,V/AlarmManager(  840): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,I/ActivityManager(  840): Killing 8087:com.samsung.android.service.travel/u0a178 (adj 15): empty for 1800s
,I/ActivityManager(  840): Killing 7621:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1800s
,I/ActivityManager(  840): Killing 8040:com.android.email/u0a163 (adj 15): empty for 1800s
,I/ActivityManager(  840): Killing 8023:com.samsung.android.sconnect/u0a138 (adj 15): empty for 1800s
,I/ActivityManager(  840): Killing 7961:com.google.android.apps.magazines/u0a128 (adj 15): empty for 1800s
,I/ActivityManager(  840): Killing 7941:com.android.chrome/u0a88 (adj 15): empty for 1801s
,I/ActivityManager(  840): Killing 7351:com.sec.android.widgetapp.ap.hero.accuweather/u0a71 (adj 15): empty for 1801s
,I/ActivityManager(  840): Killing 7866:com.osp.app.signin/u0a45 (adj 15): empty for 1801s
,I/ActivityManager(  840): Killing 7805:com.policydm/1000 (adj 15): empty for 1801s
,I/ActivityManager(  840): Killing 7783:com.sec.android.soagent/u0a37 (adj 15): empty for 1801s
,I/ActivityManager(  840): Killing 7768:com.samsung.klmsagent/u0a19 (adj 15): empty for 1801s
,I/ActivityManager(  840): Killing 7752:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1801s
,I/ActivityManager(  840): Killing 7733:com.sec.android.diagmonagent/1000 (adj 15): empty for 1801s
,I/ActivityManager(  840): Killing 7716:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1801s
,I/ActivityManager(  840): Killing 5370:com.google.android.music:main/u0a126 (adj 15): empty for 1801s
,I/ActivityManager(  840): Killing 7690:com.sec.pcw.device/1000 (adj 15): empty for 1801s
,I/ActivityManager(  840): Killing 8066:com.sec.android.provider.badge/u0a78 (adj 15): empty for 1801s
,I/ActivityManager(  840): Killing 7143:com.samsung.dcm:DCMService/u0a4 (adj 15): empty for 1802s
,I/ActivityManager(  840): Killing 7268:com.sec.android.widgetapp.activeapplicationwidget/u0a158 (adj 15): empty for 1808s
,I/ActivityManager(  840): Killing 7521:com.sec.enterprise.knox.cloudmdm.smdms/u0a179 (adj 15): empty for 1809s
,I/ActivityManager(  840): Killing 7423:com.sec.android.app.camera/u0a154 (adj 15): empty for 1826s
,I/ActivityManager(  840): Killing 7405:com.sec.android.GeoLookout/u0a113 (adj 15): empty for 1826s
,I/ActivityManager(  840): Killing 7387:com.sec.android.widgetapp.dualclockdigital/u0a103 (adj 15): empty for 1826s
,D/LightsService(  840): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  840): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  840): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,I/ProcessStatsService(  840): Prepared write state in 9ms
,I/ProcessStatsService(  840): Prepared write state in 27ms
,V/NetworkStats(  840): performPollLocked(flags=0x3)
D/NtpTrustedTime(  840): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  840): UpdateStatsForKnox
,D/ConnectivityService(  840): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  840): performPollLocked() took 14ms
D/NtpTrustedTime(  840): currentTimeMillis() cache hit
,D/NtpTrustedTime(  840): currentTimeMillis() cache hit
D/NtpTrustedTime(  840): currentTimeMillis() cache hit
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/art     ( 1676): Explicit concurrent mark sweep GC freed 38985(2MB) AllocSpace objects, 28(2MB) LOS objects, 39% free, 18MB/30MB, paused 660us total 40.606ms
,I/GLSUser ( 1676): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1676): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1676): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1676): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1676): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LightsService(  840): [SvcLED]  onSensorChanged::light value = 5
,E/LightSensor(  840): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  840): unregisterListener ::   
D/LightsService(  840): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,E/SMD     (  282): DCD ON
,D/GCM     ( 1676): Message class com.google.f.a.a.i
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  840): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ProcessStatsService(  840): Pruning old procstats: /data/system/procstats/state-2016-01-14-16-22-17.bin
,W/libprocessgroup(  840): failed to open /acct/uid_10103/pid_7387/cgroup.procs: No such file or directory
,W/libprocessgroup(  840): failed to open /acct/uid_10178/pid_8087/cgroup.procs: No such file or directory
,W/libprocessgroup(  840): failed to open /acct/uid_10113/pid_7405/cgroup.procs: No such file or directory
,W/libprocessgroup(  840): failed to open /acct/uid_10154/pid_7423/cgroup.procs: No such file or directory
,W/libprocessgroup(  840): failed to open /acct/uid_10179/pid_7521/cgroup.procs: No such file or directory
,W/libprocessgroup(  840): failed to open /acct/uid_10002/pid_7716/cgroup.procs: No such file or directory
,W/libprocessgroup(  840): failed to open /acct/uid_10158/pid_7268/cgroup.procs: No such file or directory
,W/libprocessgroup(  840): failed to open /acct/uid_1000/pid_7690/cgroup.procs: No such file or directory
,W/libprocessgroup(  840): failed to open /acct/uid_10004/pid_7143/cgroup.procs: No such file or directory
,W/libprocessgroup(  840): failed to open /acct/uid_10088/pid_7941/cgroup.procs: No such file or directory
,W/libprocessgroup(  840): failed to open /acct/uid_1000/pid_7733/cgroup.procs: No such file or directory
,W/libprocessgroup(  840): failed to open /acct/uid_10019/pid_7768/cgroup.procs: No such file or directory
,W/libprocessgroup(  840): failed to open /acct/uid_10011/pid_7752/cgroup.procs: No such file or directory
,W/libprocessgroup(  840): failed to open /acct/uid_10078/pid_8066/cgroup.procs: No such file or directory
,W/libprocessgroup(  840): failed to open /acct/uid_1000/pid_7621/cgroup.procs: No such file or directory
W/libprocessgroup(  840): failed to open /acct/uid_10037/pid_7783/cgroup.procs: No such file or directory
,W/libprocessgroup(  840): failed to open /acct/uid_1000/pid_7805/cgroup.procs: No such file or directory
,W/libprocessgroup(  840): failed to open /acct/uid_10045/pid_7866/cgroup.procs: No such file or directory
,W/libprocessgroup(  840): failed to open /acct/uid_10138/pid_8023/cgroup.procs: No such file or directory
W/libprocessgroup(  840): failed to open /acct/uid_10071/pid_7351/cgroup.procs: No such file or directory
,W/libprocessgroup(  840): failed to open /acct/uid_10126/pid_5370/cgroup.procs: No such file or directory
,W/libprocessgroup(  840): failed to open /acct/uid_10128/pid_7961/cgroup.procs: No such file or directory
,W/libprocessgroup(  840): failed to open /acct/uid_10163/pid_8040/cgroup.procs: No such file or directory
,E/SQLiteLog( 1676): (10) POSIX Error : 11 SQLite Error : 3850
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8928): 
D/AndroidRuntime( 8928): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8928): CheckJNI is OFF
D/AndroidRuntime( 8928): setted country_code = Germany
D/AndroidRuntime( 8928): setted countryiso_code = DE
D/AndroidRuntime( 8928): setted sales_code = DBT
D/AndroidRuntime( 8928): readGMSProperty: start
D/AndroidRuntime( 8928): readGMSProperty: already setted!!
D/AndroidRuntime( 8928): readGMSProperty: end
D/AndroidRuntime( 8928): addProductProperty: start
E/AffinityControl( 8928): AffinityControl: registerfunction enter
D/AndroidRuntime( 8928): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  840): START PACKAGE DELETE: observer{440820900}
D/PackageManager(  840): pkg{<packageName>}
D/PackageManager(  840): user{0}
D/PackageManager(  840): caller{2000}
D/PackageManager(  840): flags{3}
D/PersonaManagerService(  840): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  840): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  840): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  840): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  840): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  840): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  840): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  840): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  840): getApplicationUninstallationEnabled
D/ApplicationPolicy(  840): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  840): !@killApplicatoin: 10200, uninstall pkg
I/ActivityManager(  840): Force stopping com.test.thalitest appid=10200 user=-1: uninstall pkg
I/ActivityManager(  840): Killing 7562:com.test.thalitest/u0a200 (adj 0): stop com.test.thalitest
I/ActivityManager(  840): Killing 6046:com.sec.android.gallery3d/u0a48 (adj 15): empty for 1800s
I/ActivityManager(  840): Killing 7832:com.sec.spp.push/u0a38 (adj 15): empty for 1800s
I/ActivityManager(  840): Killing 8138:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty for 1800s
I/ActivityManager(  840):   Force finishing activity ActivityRecord{35308e3e u0 com.test.thalitest/.MainActivity t17}
D/FocusedStackFrame(  840): Set to : 0
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/WifiService(  840): Client connection lost with reason: 4
I/ActivityManager(  840): Killing 8242:com.samsung.android.app.FileShareServer/u0a75 (adj 15): empty for 1800s
D/ConnectivityService(  840): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  840): Force stopping com.test.thalitest appid=10200 user=0: pkg removed
I/ActivityManager(  840): Killing 7907:com.sec.knox.bridge/1000 (adj 15): empty for 1800s
E/JavaBinder(  840): !!! FAILED BINDER TRANSACTION !!!
I/art     ( 4732): Explicit concurrent mark sweep GC freed 5025(278KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 369us total 17.110ms
I/ActivityManager(  840): Killing 7922:com.sec.chaton/u0a86 (adj 15): empty for 1800s
D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader(  840): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
I/art     ( 1554): Explicit concurrent mark sweep GC freed 20898(1319KB) AllocSpace objects, 1(39KB) LOS objects, 39% free, 16MB/27MB, paused 769us total 66.350ms
W/GeofencerStateMachine( 2214): Ignoring removeGeofence because network location is disabled.
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/SamsungIME( 1873): mOCRHelper is null
E/Zygote  ( 8957): MountEmulatedStorage()
I/libpersona( 8957): KNOX_SDCARD checking this for 10019
E/Zygote  ( 8957): v2
I/libpersona( 8957): KNOX_SDCARD not a persona
I/ActivityManager(  840): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8957 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/talkback/talkback.apk
I/SELinux ( 8957): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8957): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8957): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  840): failed to open /acct/uid_10038/pid_7832/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 8957): TimaSignature is unavailable
D/ActivityThread( 8957): Added TimaKeyStore provider
W/libprocessgroup(  840): failed to open /acct/uid_10034/pid_8138/cgroup.procs: No such file or directory
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
W/libprocessgroup(  840): failed to open /acct/uid_10075/pid_8242/cgroup.procs: No such file or directory
W/libprocessgroup(  840): failed to open /acct/uid_10048/pid_6046/cgroup.procs: No such file or directory
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/SurfaceWidgetView( 1488): destroyHardwareResources():421935465
D/EnterpriseDeviceManagerService(  840): Package has changed for user 0
D/ResourcesManager( 8957): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
V/WindowOrientationListener(  840): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  840): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/EnterpriseDeviceManagerService(  840): Admin package name: com.google.android.gms
V/WindowManager(  840): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  840): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  840): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/art     (  840): Explicit concurrent mark sweep GC freed 82855(7MB) AllocSpace objects, 247(4MB) LOS objects, 30% free, 36MB/52MB, paused 2.276ms total 212.996ms
D/Launcher( 1488): onRestart, Launcher: 427523052
D/Launcher( 1488): onStart, Launcher: 427523052
D/Launcher.HomeView( 1488): onStart
I/art     (  840): WaitForGcToComplete blocked for 126.713ms for cause Explicit
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2081): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 2081): [237392/6] SurfaceWidget drawing first frame
D/ResourcesManager(  840): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/SurfaceFlinger(  249): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
D/StatusBarManagerService(  840): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/StatusBarManagerService(  840): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
W/libprocessgroup(  840): failed to open /acct/uid_1000/pid_7907/cgroup.procs: No such file or directory
W/libprocessgroup(  840): failed to open /acct/uid_10086/pid_7922/cgroup.procs: No such file or directory
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/SecContentProvider2(  840): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  840): mCursor = null
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/InputMethodManagerService(  840): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/ContextImpl(  840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService(  840): Got RemoteException sending setActive(false) notification to pid 7562 uid 10200
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/RegisteredServicesCache( 1468): empty dynamic service
W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
I/KLMS-2.4.503: ( 8957): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.503: ( 8957): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1452864681991
D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
I/KLMS-2.4.503: ( 8957): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.503: ( 8957): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/Books/Books.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/Books/Books.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/Timeline(  840): Timeline: Activity_windows_visible id: ActivityRecord{521d60b u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t15} time:1908810
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8977): MountEmulatedStorage()
E/Zygote  ( 8977): v2
I/libpersona( 8977): KNOX_SDCARD checking this for 10104
I/libpersona( 8977): KNOX_SDCARD not a persona
I/ActivityManager(  840): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8977 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  840): Killing 8272:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty for 1800s
W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/RCPManagerService(  840): PackageReceiver onReceive()
I/HarmonyEASService(  840): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  840): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/BackupManagerService(  840): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  840): Receieved: android.intent.action.PACKAGE_REMOVED
I/SELinux ( 8977): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
V/EnterpriseBillingPolicy(  840): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  840): uID is 10200
V/EnterpriseBillingPolicy(  840): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  840): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  840): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  840): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  840): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  840): getBillingProfileForVpnEngine - start - com.test.thalitest
I/SELinux ( 8977): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
V/EnterpriseBillingPolicyStorage(  840): getBillingProfileForVpnEngine - end - null
E/SELinux ( 8977): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TaskPersister(  840): removeObsoleteFile: deleting file=17_task.xml
W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TaskPersister(  840): removeObsoleteFile: deleting file=17_task_thumbnail.png
W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/libprocessgroup(  840): failed to open /acct/uid_1000/pid_8272/cgroup.procs: No such file or directory
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/TimaKeyStoreProvider( 8977): TimaSignature is unavailable
D/ActivityThread( 8977): Added TimaKeyStore provider
W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager(  840): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  840): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  840): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 8977): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
D/ResourcesManager(  840): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
D/ResourcesManager(  840): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
D/SSRM:m  (  840): SIOP:: AP = 270, PST = 261, CUR = 300
D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/elm:14451( 8977): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14451( 8977): ELMEngine.ELMEngine( context ).
D/elm:14451( 8977): MDMBridge.setEnterpriseBridge()
D/elm:14451( 8977): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8194): onReceive()
D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8194): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8194): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
D/elm:14451( 8977): ElmAgentService : onCreate()
D/elm:14451( 8977): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8977): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8977): MDMBridge.getInstance()
D/elm:14451( 8977): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14451( 8977): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 8993): MountEmulatedStorage()
E/Zygote  ( 8993): v2
I/libpersona( 8993): KNOX_SDCARD checking this for 1000
I/libpersona( 8993): KNOX_SDCARD not a persona
I/art     (  840): Explicit concurrent mark sweep GC freed 19929(978KB) AllocSpace objects, 3(1328KB) LOS objects, 30% free, 35MB/51MB, paused 2.896ms total 370.019ms
I/ActivityManager(  840): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8993 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 8993): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8993): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8993): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/elm:14451( 8977): ElmAgentService : onDestroy().
I/ActivityManager(  840): Killing 4819:com.google.android.gms.wearable/u0a12 (adj 15): empty for 1800s
W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/TimaKeyStoreProvider( 8993): TimaSignature is unavailable
D/ActivityThread( 8993): Added TimaKeyStore provider
W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/ResourcesManager( 8993): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  840): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
I/PCWCLIENTTRACE_LOG( 8993): DEFAULT_LOGON : true
W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PCWCLIENTTRACE_LOG( 8993): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 8993): new DMDBOpenHelper instance
W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  840): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources(  840): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager(  840): clearDefaults: com.test.thalitest
I/CrashAnrDetector(  840): onPackageRemoved : com.test.thalitest
I/PCWCLIENTTRACE_PushUtil( 8993): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 8993): sales region : global
I/PCWCLIENTTRACE_PushUtil( 8993): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 8993): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 9009): MountEmulatedStorage()
E/Zygote  ( 9009): v2
I/libpersona( 9009): KNOX_SDCARD checking this for 10034
I/libpersona( 9009): KNOX_SDCARD not a persona
I/ActivityManager(  840): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=9009 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager(  840): Killing 8173:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1800s
I/SELinux ( 9009): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  840): failed to open /acct/uid_10012/pid_4819/cgroup.procs: No such file or directory
D/PackageManager(  840): delete codoeFile: 
I/SELinux ( 9009): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 9009): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PackageManager(  840): result of delete: 1{440820900}
D/AndroidRuntime( 8928): Shutting down VM
D/TimaKeyStoreProvider( 9009): TimaSignature is unavailable
D/ActivityThread( 9009): Added TimaKeyStore provider
W/libprocessgroup(  840): failed to open /acct/uid_10035/pid_8173/cgroup.procs: No such file or directory
D/ResourcesManager( 9009): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
I/FeatureConfig( 9009): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
D/ResourcesManager( 9009): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/ResourcesManager( 9009): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ResourcesManager( 9009): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
W/ResourcesManager( 9009): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ResourcesManager( 9009): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/ResourcesManager( 9009): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ResourcesManager( 9009): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/ResourcesManager( 9009): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager( 9009): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 9009): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
W/ResourcesManager( 9009): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ResourcesManager( 9009): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
W/ResourcesManager( 9009): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager( 9009): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/ResourcesManager( 9009): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ResourcesManager( 9009): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/ResourcesManager( 9009): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ResourcesManager( 9009): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/ResourcesManager( 9009): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager( 9009): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/ResourcesManager( 9009): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 9009): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
W/ResourcesManager( 9009): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/ResourcesManager( 9009): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 9009): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/ResourcesManager( 9009): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ResourcesManager( 9009): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/ResourcesManager( 9009): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 9009): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
I/EventHub(  840): Removing device '/dev/input/event4' due to inotify event
I/ActivityManager(  840): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=9032 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
E/Zygote  ( 9032): MountEmulatedStorage()
E/Zygote  ( 9032): v2
I/libpersona( 9032): KNOX_SDCARD checking this for 10035
I/libpersona( 9032): KNOX_SDCARD not a persona
I/EventHub(  840): Removing device '/dev/input/event5' due to inotify event
I/SELinux ( 9032): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
E/SELinux ( 9032): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/EventHub(  840): Removing device '/dev/input/event6' due to inotify event
E/SMD     (  282): DCD ON
I/EventHub(  840): Removing device '/dev/input/event7' due to inotify event
D/TimaKeyStoreProvider( 9032): TimaSignature is unavailable
D/ActivityThread( 9032): Added TimaKeyStore provider
I/EventHub(  840): Removing device '/dev/input/event8' due to inotify event
D/ResourcesManager( 9032): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
W/ContextImpl( 9032): Unable to create files subdir /data/data/com.sec.android.app.shealth/cache
E/ActivityThread( 9032): Unable to setupGraphicsSupport due to missing cache directory
W/        ( 9032): Zip: inflate read failed (15881 vs 32768)
F/libc    ( 9032): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7429da62 in tid 9032 (oid.app.shealth)
E/audit_log( 2123): File locking failed. error= Bad file number
E/audit_log( 2123): File locking failed. error= Bad file number

```
