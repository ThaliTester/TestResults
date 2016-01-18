#### Test 563583788793eb6_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
--------- beginning of system
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
D/[SAMSUNG SMARCART NATIVE]( 7457): initialize...
D/[SAMSUNG SMARCART NATIVE]( 7457): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
I/CSTORAGE( 7457): ================================================
I/CSTORAGE( 7457):  CSTORAGE_SKM_LIB v1.0.8
I/CSTORAGE( 7457): ================================================
I/TZ_CCM_C_GetFunctionList: ( 7457): TZ_CCM_C_GetFunctionList was called
D/[SAMSUNG SMARCART NATIVE]( 7457): FINISHED: initialize rv:0
D/UMC:SecurityUtils( 7457): Loaded server certificates: 0
D/UMC:SecurityUtils( 7457): Loaded server certificates: 0
D/UMC:SecurityUtils( 7457): timaVersion on the device: 3.0
V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UMC:CloudMDMSecurity( 7457): New Flow
D/TimaService(  890): TIMA3: in ccmRegisterForDefaultCertificate
D/TimaService(  890): TIMA: in getTimaVersion
I/        (  890): CCM JNI: In ccm_register_for_default_cert
I/        (  890): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: (  890): DEBUG_CONTAINER_PROBLEM Enter TZ_CCM_C_Initialize_TLC!
I/TZ_CCM_C_Initialize: (  890): pInitArgs 0x92c7e814 has not called C_Init before.
I/TZ_CCM_C_Initialize: (  890): &ctx = 0x9fbb6c1c
I/TLC_TZ_CCM: (  890): creating new ccm context...
I/TLC_TZ_CCM: (  890): initializing ccm context...
I/TLC_TZ_CCM: (  890): root = /firmware/image, root_strlen = 15
I/TLC_TZ_CCM: (  890): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  890): input max_sendmsg_size = 19420
I/TZ: client_server_communication(  890): input max_recvmsg_size = 19420
I/TZ: client_server_communication(  890): root = /firmware/image, root_len = 15
I/TZ: client_server_communication(  890): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  890): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication(  890): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication(  890): Client_Server_Open was called
I/TZ: client_server_communication(  890): IClientServer::IClientServer()
I/TZ: client_server_communication(  890): BpClientServer::BpClientServer()
I/TZ: client_server_communication(  890): IClientServer::~IClientServer()
I/TZ_CCM_SERVER( 1090): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 1090): OPENSWCONN
I/TZ_CCM_SERVER( 1090): creating new ccm context...
I/TZ_CCM_SERVER( 1090): initializing ccm context...
I/TZ_CCM_SERVER( 1090): root = /firmware/image, root_strlen = 15
I/TZ_CCM_SERVER( 1090): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1090): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1090): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1090): aligned max_sendmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1090): aligned max_recvmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1090): max_message_size = 38912 = 0x9800
D/QSEECOMAPI: ( 1090): QSEECom_get_handle sb_length = 0x9800
D/QSEECOMAPI: ( 1090): App is not loaded in QSEE
D/QSEECOMAPI: ( 1090): Loaded image: APP id = 3
I/TZ: qc_tlc_communication( 1090): TIMA: path = /firmware/image, fname = tz_ccm, tzapp is loaded
I/TZ: client_server_communication(  890): OpenSWConn(CCM) is successful
I/TZ: client_server_communication(  890): Client_Server_Open succeeded, serverName = CCM
I/TZ_CCM_C_Initialize: (  890): ctx = 0x9edfa360, comm = 0x94696220, sendmsg = 0x9c7ed000, recvmsg = 0x9c7f1c00
I/TZ_init: (  890): TZ_init: sending initialization request...
I/TZ: client_server_communication(  890): Cmd id = 2, len = 19456
I/TZ: client_server_communication(  890): Calling Communicate()
I/TZ_CCM_SERVER( 1090): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1090): COMM
E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
I/TZ_init: (  890): TZ_init: successful initialization
I/TLC_TZ_COMMON: key_db_init: (  890): Exercising TZ_DB_INIT in TLC
I/TZ: client_server_communication(  890): Cmd id = 17, len = 19456
I/TZ: client_server_communication(  890): Calling Communicate()
I/TZ_CCM_SERVER( 1090): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1090): COMM
I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/TZ_COMMON: tlc_key_db_util: (  890): DB Operation suceeded
I/TLC_TZ_CCM: register for default cert: (  890): Exercising TZ_CCM_register_default_TLC
I/TZ: client_server_communication(  890): Cmd id = 25, len = 19456
I/TZ: client_server_communication(  890): Calling Communicate()
I/TZ_CCM_SERVER( 1090): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1090): COMM
I/TLC_TZ_CCM: register for default cert: (  890): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: (  890): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
I/TZ_CCM_C_Finalize: (  890): DEBUG_CONTAINER_PROBLEM Exercising TZ_CCM_C_Finalize_TLC
I/TZ: client_server_communication(  890): Cmd id = 41, len = 19456
I/TZ: client_server_communication(  890): Calling Communicate()
V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/TZ_CCM_SERVER( 1090): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1090): COMM
I/TZ: client_server_communication(  890): Client_Server_Close was called
I/TZ_CCM_SERVER( 1090): BnCCM::onTransact(1) 16
I/TZ_CCM_SERVER( 1090): CLOSESWCONN
D/QSEECOMAPI: ( 1090): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1090): QSEECom_shutdown_app, app_id = 3
I/TZ: client_server_communication(  890): Client_Server_Close succeeded
D/UMC:CloudMDMSecurity( 7457): ccmRegisterForDefaultCertificate: 0
D/UMC:CloudMDMSecurity( 7457): TIMA service call for password change success!!
D/UMC:AdminManager( 7457): init - start
D/Finsky  ( 6546): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6546): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6546): [1] 5.onFinished: Scheduling replication attempt 2.
D/UMC:AdminManager( 7457): loadAdmins
D/UMC:AdminManager( 7457): startPolicyHandlers
I/UMC:TestPolicyHandler( 7457): Setup is called in testpolicyhandler
D/UMC:AdminManager( 7457): init - end
V/UMC:AlarmHandler( 7457): Enter loadList
D/GSLBManager( 7457): migrateStoredUrlFromOldPref
D/GSLBManager( 7457): migrateStoredUrlFromOldPref : Migration Not Needed
D/UMC:UMCAdmin( 7457): deactivateUMCAdminIfNotRequired : -1
E/UMC:Utils( 7457): Admin not found in package com.samsung.knoxpb.mdm
D/UMC:UMCAdmin( 7457): deactivateUMCAdmin : -1
D/UMC:UMCAdmin( 7457): isContainer : 0
W/LicenseLogService(  890): log() failed
D/EnterpriseDeviceManagerService(  890): isManagedProfileUser(): userId = 0
E/UMC:UMCAdmin( 7457): No active admin owned by uid 10179
D/UMC:UMCAdmin( 7457): isContainer : 0
D/UMC:UMCAdmin( 7457): deactivateUMCAdmin - UMC App Admin deactivated
V/UMC:AlarmHandler( 7457): onReceive :Intent { flg=0x14 cmp=com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler (has extras) }
D/QuickStartReceiver( 7457): Msg Id : 2
D/QuickStartReceiver( 7457): model : SM-G900F
D/QuickStartReceiver( 7457): id : 100
I/ActivityManager(  890): Killing 6732:com.sec.pcw.device/1000 (adj 15): bgCount ##41
E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_6732/cgroup.procs: No such file or directory
E/SMD     (  288): DCD ON
D/AndroidRuntime( 7490): 
D/AndroidRuntime( 7490): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7490): CheckJNI is OFF
D/AndroidRuntime( 7490): setted country_code = Germany
D/AndroidRuntime( 7490): setted countryiso_code = DE
D/AndroidRuntime( 7490): setted sales_code = DBT
D/AndroidRuntime( 7490): readGMSProperty: start
D/AndroidRuntime( 7490): readGMSProperty: already setted!!
D/AndroidRuntime( 7490): readGMSProperty: end
D/AndroidRuntime( 7490): addProductProperty: start
E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
E/AffinityControl( 7490): AffinityControl: registerfunction enter
D/AndroidRuntime( 7490): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  890): inState():  stateMachine is null !!
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  890): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  890): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  890): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 890  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  890): mDVFSHelper.acquire()
D/FocusedStackFrame(  890): Set to : 0
D/Launcher.HomeView( 1484): onPause
D/Launcher( 1484): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/AndroidRuntime( 7490): Shutting down VM
E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
V/TaskCloserActivity( 7230): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/SurfaceFlinger(  248): id=14 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
E/Zygote  ( 7520): MountEmulatedStorage()
E/Zygote  ( 7520): v2
I/libpersona( 7520): KNOX_SDCARD checking this for 10200
I/libpersona( 7520): KNOX_SDCARD not a persona
I/ActivityManager(  890): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7520 uid=10200 gids={50200, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
I/SELinux ( 7520): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/SELinux ( 7520): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7520): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/StatusBarManagerService(  890): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/MicrophoneInputStream( 1554): mic_close gfk@29018fa5
V/AudioPolicyManager(  293): stopInput() input 29
V/AudioPolicyManager(  293): releaseInput() 29
V/AudioPolicyManager(  293): closeInput(29)
I/HotwordRecognitionRnr( 1554): Hotword detection finished
I/HotwordRecognitionRnr( 1554): Stopping hotword detection.
V/audio_hw_primary(  293): in_standby: enter
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/TimaKeyStoreProvider( 7520): TimaSignature is unavailable
D/ActivityThread( 7520): Added TimaKeyStore provider
V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  890): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  890): Display changed displayId=0
D/Launcher.HomeView( 1484): onStop
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2137): [237392/6] Surface widget pause on instance = 1
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2137): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/accuweather( 2137): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2137): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2137): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/SurfaceWidgetView( 1484): destroyHardwareResources():535910263
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
V/audio_hw_primary(  293): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  293): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  293): disable_audio_route: reset mixer path: audio-record
D/audio_route(  293): ++++ audio_route_update_mixer ==============
D/audio_route(  293): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  293): Setting mixer control: value: 0
D/audio_route(  293): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  293): disable_audio_route: exit
V/audio_hw_primary(  293): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  293): ++++ audio_route_update_mixer ==============
D/audio_route(  293): Setting mixer control: DEC2 Volume
D/audio_route(  293): Setting mixer control: value: 0
D/audio_route(  293): Setting mixer control: SLIM TX7 MUX, value: 0
D/audio_route(  293): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  293): Setting mixer control: value: 0
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/audio_route(  293): Setting mixer control: DEC2 MUX, value: 0
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/StatusBarManagerService(  890): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/audio_route(  293): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  293): stop_input_stream: exit: status(0)
V/audio_hw_primary(  293): in_standby: exit:  status(0)
V/audio_hw_primary(  293): adev_close_input_stream
V/audio_hw_primary(  293): in_standby: enter
V/audio_hw_primary(  293): in_standby: exit:  status(0)
E/audio_hw_primary(  293): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  293): releaseInput() exit
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/accuweather( 2137): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/accuweather( 2137): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Launcher( 1484): onTrimMemory. Level: 20
D/ResourcesManager( 7520): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/SurfaceWidgetView( 1484): destroyHardwareResources():535910263
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/WebViewFactory( 7520): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7520): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/LibraryLoader( 7520): Loading: webviewchromium
I/LibraryLoader( 7520): Time to load native libraries: 2 ms (timestamps 8275-8277)
I/LibraryLoader( 7520): Expected native library version number "",actual native library version number ""
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
V/WebViewChromiumFactoryProvider( 7520): Binding Chromium to main looper Looper (main, tid 1) {19fc0a66}
I/LibraryLoader( 7520): Expected native library version number "",actual native library version number ""
I/chromium( 7520): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7520): Initializing chromium process, renderers=0
W/art     ( 7520): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/chromium( 7520): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7520): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7520): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/Adreno-EGL( 7520): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7520): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7520): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7520): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7520): Remote Branch: 
I/Adreno-EGL( 7520): Local Patches: 
I/Adreno-EGL( 7520): Reconstruct Branch: 
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/chromium( 7520): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/chromium( 7520): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7520): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7520): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/SystemWebViewEngine( 7520): CordovaWebView is running on device made by: samsung
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/art     ( 7520): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7520): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PowerManagerService(  890): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1172 (0x0)
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/Activity( 7520): performCreate Call secproduct feature valuefalse
D/Activity( 7520): performCreate Call debug elastic valuetrue
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/OpenGLRenderer( 7520): Render dirty regions requested: true
D/ActivityManager(  890): post active user change for 0
D/KnoxTimeoutHandler(  890): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  890): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
I/SurfaceFlinger(  248): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/OpenGLRenderer( 7520): Initialized EGL, version 1.4
I/OpenGLRenderer( 7520): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7520): Enabling debug mode 0
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/InputMethodManagerService(  890): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/SurfaceFlinger(  248): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
I/SurfaceFlinger(  248): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/Timeline( 7520): Timeline: Activity_idle id: android.os.BinderProxy@42f7e31 time:98600
W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager(  890): Displayed com.test.thalitest/.MainActivity: +612ms
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
D/JsMessageQueue( 7520): Set native->JS mode to OnlineEventsBridgeMode
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/jxcore_app_log( 7520): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258323328
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/SurfaceFlinger(  248): id=14 Removed Starting com.test.thalitest (7/8)
I/SurfaceFlinger(  248): id=14 Removed Starting com.test.thalitest (-2/8)
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/CustomFrequencyManagerService(  890): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 890  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  890): mDVFSHelper.release()
I/Timeline(  890): Timeline: Activity_windows_visible id: ActivityRecord{27c1a391 u0 com.test.thalitest/.MainActivity t17} time:98863
D/CustomFrequencyManagerService(  890): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 890  pkgName : ACTIVITY_RESUME_BOOSTER@10
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/chromium( 7520): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/Adreno-ES20( 7520): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7520): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
I/chromium( 7520): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7520): 
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  890): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 890  tag : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  890): SIOP:: AP = 380, PST = 436, CUR = 300
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/SMD     (  288): DCD ON
,W/jxcore-log( 7520): Initializing JXcore engine
,W/jxcore-log( 7520): JXcore engine is ready
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/auditd  ( 2173): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  890): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  890): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7588): MountEmulatedStorage()
,E/Zygote  ( 7588): v2
I/libpersona( 7588): KNOX_SDCARD checking this for 1000
I/libpersona( 7588): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7588 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/jxcore-log( 7520): Starting JXcore engine
,I/SELinux ( 7588): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7588): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7588): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7588): TimaSignature is unavailable
,D/ActivityThread( 7588): Added TimaKeyStore provider
,D/ResourcesManager( 7588): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/SecurityLogAgent( 7588):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7588):  SeDenialReceiver : File path = null
,I/ActivityManager(  890): Killing 6417:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,W/jxcore-log( 7520): Platform android
W/jxcore-log( 7520): 
W/jxcore-log( 7520): Process ARCH arm
W/jxcore-log( 7520): 
,W/libprocessgroup(  890): failed to open /acct/uid_10034/pid_6417/cgroup.procs: No such file or directory
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7520): JXcore Cordova bridge is ready!
I/jxcore-log( 7520): 
,W/jxcore-log( 7520): JXcore engine is started
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7520): Toggling radios to true
I/jxcore-log( 7520): 
,D/BluetoothAdapter( 7520): enable()
,D/BluetoothAdapter( 7520): enable(): BT is already enabled..!
,D/WifiService(  890): New client listening to asynchronous messages
,I/WifiManager( 7520): packageName : com.test.thalitest
,D/SecContentProvider(  890): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  890): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  890): mCursor = null
,D/WifiService(  890): setWifiEnabled: true pid=7520, uid=10200
E/WifiService(  890): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  890): Permission Denial: getCurrentUser() from pid=7520, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  890): Failed getting userId using ActivityManagerNative
W/WifiService(  890): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7520, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  890): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  890): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  890): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  890): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  890): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  890): name = wifi_on
I/WifiService(  890): disconnect: pid=7520, uid=10200
,I/wpa_supplicant( 1284): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7520): Radios toggled
I/jxcore-log( 7520): 
,I/jxcore-log( 7520): My device name is: samsung-SM-G900F
I/jxcore-log( 7520): 
,I/wpa_supplicant( 1284): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1284): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1284): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1284): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  890): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1284): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1284): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1284): Disconnected - do not scan
I/wpa_supplicant( 1284): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  890): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
,E/WifiStateMachine(  890): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  890): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  890): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  890): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  890): InactiveState{ what=143375 }
D/WifiP2pService(  890): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  281): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1674): Read error: ssl=0xaed2ee00: I/O error during system call, Connection timed out
,E/WifiStateMachine(  890): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  890): updateNetworkInfo()
,D/ConnectivityService(  890): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  890): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,I/WifiTrafficPoller(  890): evaluateTrafficStatsPolling
,V/NativeCrypto( 1674): SSL shutdown failed: ssl=0xaed2ee00: I/O error during system call, Broken pipe
,I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): DefaultState{ when=-3ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): Validated
,E/WifiConfigStore(  890): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  890): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1284): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1284): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1284): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1284): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1284): First Scan Start
,I/wpa_supplicant( 1284): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine(  890): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  890): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
E/WifiStateMachine(  890): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  890): InactiveState{ what=143375 }
D/WifiP2pService(  890): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/Hs20UtilService( 1307): Starting #6
I/Hs20UtilService( 1307): Message received 5007
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1307): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
,D/CommandListener(  281): Clearing all IP addresses on wlan0
D/ConnectivityService(  890): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  890): calling update connectivity
,D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  890): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine(  890): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/Nat464Xlat(  890): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/EntConnectivity(  890): Not allowed due to - mEnabled false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): Disconnected - quitting
D/WifiStateMachine(  890): updateConfiguredNetworkExpiration - currTime: 1453134222192
D/WifiStateMachine(  890): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,E/WifiStateMachine(  890): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524292
D/ConnectivityService(  890): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/WifiTrafficPoller(  890): evaluateTrafficStatsPolling
D/TelephonyNetworkFactory( 1474): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  890): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/WifiNetworkAgent(  890): NetworkAgent: NetworkAgent channel lost
,D/CSLegacyTypeTracker(  890): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  890): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  890): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  890): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  890): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  890): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  890): mCursor = null
,D/ConnectivityService(  890): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  890): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,V/NetworkStats(  890): updateIfacesLocked()
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
V/NetworkStats(  890): performPollLocked(flags=0x1)
,D/SmartBondingService(  890): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
,D/NetworkStatsFactory(  890): UpdateStatsForKnox
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): updateDataNetType()
E/ConnectivityService(  890): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
,E/ConnectivityService(  890): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/SmartBondingService(  890): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  890): currentTimeMillis() cache hit
,V/NetworkStats(  890): performPollLocked() took 7ms
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
V/NetworkStats(  890): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/Hs20UtilService( 1307): Starting #7
,D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
,I/Hs20UtilService( 1307): Message received 5007
D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  890): mCursor = null
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1307): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
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
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  890): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  890): updateDataUsageMap
,D/Tethering(  890): MasterInitialState.processMessage what=3
,D/SmartBondingService(  890): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 2137): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/SmartBondingService(  890): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
I/CLocInfoService(  890): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  890): CLoinfo wifi false
D/SmartBondingService(  890): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7109): [#DCM#] [DCM_Performance] onReceive completed in time  1220 microsec. 
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
I/NetworkMonitor( 5366): type=WIFI subType= reason=null isConnected=false
,E/Zygote  ( 7656): MountEmulatedStorage()
I/libpersona( 7656): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7656): v2
I/libpersona( 7656): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7656 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/SLocation(  890): No Active Data Connection
,I/SystemBroadcastReceiver( 7109): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7109): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
,I/DCMController( 7109): [#DCM#] setIsConnectedForExtractors 
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3829): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/SELinux ( 7656): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SELinux ( 7656): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7656): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3829): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/TimaKeyStoreProvider( 7656): TimaSignature is unavailable
,D/ActivityThread( 7656): Added TimaKeyStore provider
,D/ResourcesManager( 7656): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG( 7656): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 7656): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7656): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 7656): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7656): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7656): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7656): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7656): noConnectivity : true
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7683): MountEmulatedStorage()
,E/Zygote  ( 7683): v2
I/libpersona( 7683): KNOX_SDCARD checking this for 10002
I/libpersona( 7683): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7683 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 4787:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,I/SELinux ( 7683): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7683): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7683): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7683): TimaSignature is unavailable
,D/ActivityThread( 7683): Added TimaKeyStore provider
,D/ResourcesManager( 7683): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,W/libprocessgroup(  890): failed to open /acct/uid_10035/pid_4787/cgroup.procs: No such file or directory
,I/ActivityManager(  890): Killing 6747:com.policydm/1000 (adj 15): bgCount ##41
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7700): MountEmulatedStorage()
I/libpersona( 7700): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7700): v2
I/libpersona( 7700): KNOX_SDCARD not a persona
D/PowerManagerService(  890): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
D/PowerManagerService(  890): [s] DisplayPowerCallbacks : onStateChanged()
,I/ActivityManager(  890): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7700 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7700): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7700): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7700): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7700): TimaSignature is unavailable
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
D/lights  (  890): lcd : 1 +
,D/ActivityThread( 7700): Added TimaKeyStore provider
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
D/lights  (  890): lcd : 1 -
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/ResourcesManager( 7700): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_6747/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 7700): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7700): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7700): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7700): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7700): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7700): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7719): MountEmulatedStorage()
,E/Zygote  ( 7719): v2
I/libpersona( 7719): KNOX_SDCARD checking this for 10011
I/libpersona( 7719): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7719 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant( 1284): nl80211: Received scan results (5 BSSes)
,I/wpa_supplicant( 1284): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 1284): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1284): wlan0: State: SCANNING -> ASSOCIATING
E/WifiStateMachine(  890): [1,453,134,223,254 ms] noteScanEnd no scan source
,I/wpa_supplicant( 1284): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,I/SELinux ( 7719): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/CLocInfoService(  890): External Intent Received android.net.wifi.SCAN_RESULTS
E/WifiStateMachine(  890): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@c7b6d76 sup_state=SCANNING debouncing=false
I/SELinux ( 7719): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7719): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
E/WifiStateMachine(  890): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  890): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  890): setDetailed state send new extra info0x
D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  890): mCursor = null
,D/TimaKeyStoreProvider( 7719): TimaSignature is unavailable
,D/ActivityThread( 7719): Added TimaKeyStore provider
,D/ResourcesManager( 7719): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager(  890): Killing 5278:com.sec.spp.push/u0a38 (adj 15): bgCount ##41
,I/wpa_supplicant( 1284): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1284): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1284): Associated with C0.AA.48
,E/WifiStateMachine(  890): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  890): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  890): mCursor = null
,I/FOTA_Client( 7719): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7719): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/wpa_supplicant( 1284): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1284): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  890): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  890): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  890): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  890): mCursor = null
,I/wpa_supplicant( 1284): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1284): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1284): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  890): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  890): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 1284): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1284): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1284): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1284): Blacklist: Clear (temp) 
I/wpa_supplicant( 1284): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  890): Network connection established
,D/WifiNative-HAL(  890): callSECApiVoid - ID [50]
,E/WifiStateMachine(  890): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/FOTA_Client( 7719): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
E/WifiStateMachine(  890): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  890): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  890): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  890): Got NetworkAgent Messenger
E/WifiStateMachine(  890): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  890): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService(  890): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiConfigStore(  890): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  890): NetworkAgent connected
E/ConnectivityService(  890): updateNetworkInfo()
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/FOTA_Client( 7719): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7719): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  890): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  890): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  890): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  890): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  281): Setting iface cfg
,E/WifiStateMachine(  890): Start Dhcp Watchdog 2
,D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  890): mCursor = null
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/Zygote  ( 7736): MountEmulatedStorage()
I/libpersona( 7736): KNOX_SDCARD checking this for 10019
E/Zygote  ( 7736): v2
I/libpersona( 7736): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7736 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6035:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,E/WifiStateMachine(  890): calculateWifiScore() report new score 60
I/WifiStateMachine(  890): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  890): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,D/ConnectivityService(  890): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,E/WifiStateMachine(  890): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  890): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  890): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/SELinux ( 7736): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  890): failed to open /acct/uid_10038/pid_5278/cgroup.procs: No such file or directory
,I/SELinux ( 7736): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7736): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7736): TimaSignature is unavailable
,D/ActivityThread( 7736): Added TimaKeyStore provider
,W/libprocessgroup(  890): failed to open /acct/uid_10042/pid_6035/cgroup.procs: No such file or directory
,D/ResourcesManager( 7736): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7736): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7736): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453134223469
,I/KLMS-2.4.503: ( 7736): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7736): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7736): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  890): Killing 6767:com.osp.app.signin/u0a45 (adj 15): bgCount ##41
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  890): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  890): do suspend false
,D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  890): mCursor = null
,D/WifiP2pService(  890): InactiveState{ what=143375 }
,D/WifiP2pService(  890): P2pEnabledState{ what=143375 }
,E/Zygote  ( 7751): MountEmulatedStorage()
E/Zygote  ( 7751): v2
I/libpersona( 7751): KNOX_SDCARD checking this for 10037
I/libpersona( 7751): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7751 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/art     (  324): Explicit concurrent mark sweep GC freed 8723(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 278us total 16.410ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 328us total 7.872ms
,I/SELinux ( 7751): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7751): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7751): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 11.802ms
,D/TimaKeyStoreProvider( 7751): TimaSignature is unavailable
,D/ActivityThread( 7751): Added TimaKeyStore provider
,D/ResourcesManager( 7751): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,I/SO_AGENT( 7751): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  890): failed to open /acct/uid_10045/pid_6767/cgroup.procs: No such file or directory
,E/Zygote  ( 7766): MountEmulatedStorage()
E/Zygote  ( 7766): v2
I/libpersona( 7766): KNOX_SDCARD checking this for 1000
I/libpersona( 7766): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7766 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6791:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,I/SELinux ( 7766): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7766): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7766): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7766): TimaSignature is unavailable
,D/ActivityThread( 7766): Added TimaKeyStore provider
,D/ResourcesManager( 7766): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,W/libprocessgroup(  890): failed to open /acct/uid_10051/pid_6791/cgroup.procs: No such file or directory
,E/dhcpcd  ( 7781): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7781): version 5.5.6 starting
,E/dhcpcd  ( 7781): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 7781): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7781): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7781): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7781): bssid match
I/dhcpcd  ( 7781): wlan0: rebinding lease of 192.168.1.135
,E/Zygote  ( 7797): MountEmulatedStorage()
I/libpersona( 7797): KNOX_SDCARD checking this for 10038
E/Zygote  ( 7797): v2
I/libpersona( 7797): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7797 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6808:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,I/SELinux ( 7797): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7797): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7797): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7797): TimaSignature is unavailable
,D/ActivityThread( 7797): Added TimaKeyStore provider
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/libprocessgroup(  890): failed to open /acct/uid_10058/pid_6808/cgroup.procs: No such file or directory
,D/ResourcesManager( 7797): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService( 7797): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 7797): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7797): PushLog.txt file is not deleted.
D/SPPClientService( 7797): PushLog.txt file is not deleted.
D/SPPClientService( 7797): ============PushLog. stop!
,E/SPPClientService( 7797): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7814): MountEmulatedStorage()
,E/Zygote  ( 7814): v2
I/libpersona( 7814): KNOX_SDCARD checking this for 10045
I/libpersona( 7814): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7814 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6242:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,I/SELinux ( 7814): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7814): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7814): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,E/SPPClientService( 7797): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider( 7814): TimaSignature is unavailable
,D/ActivityThread( 7814): Added TimaKeyStore provider
,D/ResourcesManager( 7814): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_6242/cgroup.procs: No such file or directory
,I/SA      ( 7814): [SSP] onCreated
,I/SA      ( 7814): [TPM] There is no property file
,I/SA      ( 7814): [SCU] isHaveSA() - false
,I/SA      ( 7814): [TPM] getModelProperty : null
I/SA      ( 7814): [TPM] getCSCProperty : null
,I/SA      ( 7814): [DM] init START
,I/SA      ( 7814): [DM] This device is not a Vodafone
,W/ResourceType( 7814): Failure getting entry for 0x7f06000f (t=5 e=15) (error -75)
,W/ResourceType( 7814): Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
W/ResourceType( 7814): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 7814): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 7814): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 7814): Failure getting entry for 0x7f060001 (t=5 e=1) (error -75)
,W/ResourceType( 7814): Failure getting entry for 0x7f060013 (t=5 e=19) (error -75)
,W/ResourceType( 7814): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7814): Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
W/ResourceType( 7814): Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,W/ResourceType( 7814): Failure getting entry for 0x7f060024 (t=5 e=36) (error -75)
W/ResourceType( 7814): Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,W/ResourceType( 7814): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
W/ResourceType( 7814): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7814): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 7814): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 7814): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 7814): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 7814): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 7814): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,I/SA      ( 7814): [SCU] isHaveSA() - false
,I/SA      ( 7814): support phone number id : false
I/SA      ( 7814): [DM] init END
,I/SA      ( 7814): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7814): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 7814): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7814): [SLFUCHKMGR] constructor called
,I/SA      ( 7814): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7814): [OR] == isSIMCardReady false ==
I/SA      ( 7814): [SCU] == networkStateCheck == false
,I/SA      ( 7814): [OR] onReceive END
,I/ActivityManager(  890): Killing 6482:com.sec.chaton/u0a86 (adj 15): bgCount ##41
,E/SMD     (  288): DCD ON
,D/accuweather( 7312): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7312): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7312): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7312): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
D/accuweather( 7312): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 7312): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1333): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/accuweather( 7312): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
D/daemonapp( 1333): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7312): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1333): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7312): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7312): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  890): failed to open /acct/uid_10086/pid_6482/cgroup.procs: No such file or directory
,E/Zygote  ( 7836): MountEmulatedStorage()
E/Zygote  ( 7836): v2
I/libpersona( 7836): KNOX_SDCARD checking this for 1000
I/libpersona( 7836): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7836 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7836): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7836): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7836): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7836): TimaSignature is unavailable
,D/ActivityThread( 7836): Added TimaKeyStore provider
,D/ResourcesManager( 7836): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7836): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7836): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7836): premStatus:2
,I/KnoxUsageLogPro( 7836): isEulaShown : false
I/KnoxUsageLogPro( 7836): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7851): MountEmulatedStorage()
E/Zygote  ( 7851): v2
I/libpersona( 7851): KNOX_SDCARD checking this for 10086
I/libpersona( 7851): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.NetStateReceiver: pid=7851 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6830:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,I/SELinux ( 7851): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7851): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7851): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7851): TimaSignature is unavailable
,D/ActivityThread( 7851): Added TimaKeyStore provider
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/ResourcesManager( 7851): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7851): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  890): failed to open /acct/uid_10098/pid_6830/cgroup.procs: No such file or directory
,E/Watchdog(  890): !@Sync 3
,D/PushModule( 7851): [PushClientApplication] (main) PushClientApplication.onCreate()
,I/PushModule( 7851): [PushClientApplication] (main) PushModule version: 0.9.01.12
,D/PushModule( 7851): [PushClientApplication] (main) Discovered public push client. disable in app push client.
,D/ChatON  ( 7851): [1][isApplicationInstalled] com.android.mms was installed
,W/ContextImpl( 7851): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
,W/ActivityManager(  890): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,D/ChatON  ( 7851): [1][a] ChatONV isn't installed.
D/ChatON  ( 7851): [1][a] ChatONVPlugIn.isAvailable()
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7873): MountEmulatedStorage()
,E/Zygote  ( 7873): v2
I/libpersona( 7873): KNOX_SDCARD checking this for 10088
I/libpersona( 7873): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7873 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6888:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,I/SELinux ( 7873): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7873): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7873): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/TimaKeyStoreProvider( 7873): TimaSignature is unavailable
,D/ActivityThread( 7873): Added TimaKeyStore provider
,D/ResourcesManager( 7873): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  890): failed to open /acct/uid_10033/pid_6888/cgroup.procs: No such file or directory
,I/ActivityManager(  890): Killing 6857:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,D/Headlines( 5512): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5512): getCountryCode(): countryCode = DE
,D/Headlines( 5512): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5512): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5512): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/Headlines( 5512): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5512): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,E/Zygote  ( 7889): MountEmulatedStorage()
E/Zygote  ( 7889): v2
I/libpersona( 7889): KNOX_SDCARD checking this for 10128
I/libpersona( 7889): KNOX_SDCARD not a persona
,D/HeadlinesCardManager( 5512): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5512): requestUpdateNewsWelcomeCard !!! no welcome card
,I/ActivityManager(  890): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7889 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,I/SELinux ( 7889): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7889): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7889): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7889): TimaSignature is unavailable
,D/ActivityThread( 7889): Added TimaKeyStore provider
,D/ResourcesManager( 7889): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/libprocessgroup(  890): failed to open /acct/uid_10099/pid_6857/cgroup.procs: No such file or directory
,E/Vold    (  247): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7889): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  247): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7889): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  247): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7889): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/Vold    (  247): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7889): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/dhcpcd  ( 7781): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,I/dhcpcd  ( 7781): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  890): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  890): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  890): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/WebViewFactory( 7889): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7889): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7889): Loading: webviewchromium
,I/LibraryLoader( 7889): Time to load native libraries: 5 ms (timestamps 4412-4417)
I/LibraryLoader( 7889): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7889): Binding Chromium to main looper Looper (main, tid 1) {807d714}
,I/LibraryLoader( 7889): Expected native library version number "",actual native library version number ""
,I/chromium( 7889): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7889): Initializing chromium process, renderers=0
,W/art     ( 7889): Attempt to remove local handle scope entry from IRT, ignoring
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,W/chromium( 7889): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7889): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7889): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7889): Requires BLUETOOTH permission
,I/Adreno-EGL( 7889): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7889): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7889): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7889): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7889): Remote Branch: 
I/Adreno-EGL( 7889): Local Patches: 
I/Adreno-EGL( 7889): Reconstruct Branch: 
,I/NSApplication( 7889): Starting up...
,E/WifiStateMachine(  890): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  890): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  890): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  890): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  890): InactiveState{ what=143375 }
,D/WifiP2pService(  890): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  890): WifiStateMachine DHCP successful
,E/WifiStateMachine(  890): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  890): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,D/ConnectivityService(  890): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  890): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  890): Not connected state, yet.
E/WifiStateMachine(  890): VerifyingLinkState enter
,D/WifiStateMachine(  890): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
,D/WifiStateMachine(  890): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  890): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  890): callSECApiInt - ID [210]
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/WifiStateMachine(  890): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService(  890): updateNetworkInfo()
,D/ConnectivityService(  890): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  890): Adding iface wlan0 to network 503
,E/Zygote  ( 7972): MountEmulatedStorage()
,E/Zygote  ( 7972): v2
I/libpersona( 7972): KNOX_SDCARD checking this for 10138
I/libpersona( 7972): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7972 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6927:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  890): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  890): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  890): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  890): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  890): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  890): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  890): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  890): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  890): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  890): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  890): updateSourceRoutes : add src route for:192.168.1.135
V/        (  281): QcRouteController
,I/SELinux ( 7972): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7972): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7972): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/WifiStateMachine(  890): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine(  890): Now, connected state.
E/WifiStateMachine(  890): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
E/WifiStateMachine(  890): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/WifiTrafficPoller(  890): evaluateTrafficStatsPolling
,V/        (  281): QcRouteController
,I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  890): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine(  890): ConnectedState Enter  mScreenOn=true scanperiod=20000
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/WifiTrafficPoller(  890): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  890): mBoosterFLAG : 0
I/WifiTrafficPoller(  890): current booster mode : FullMode
,V/        (  281): QcRouteController
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/WifiNative-HAL(  890): callSECApiVoid - ID [212]
,I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
,D/TimaKeyStoreProvider( 7972): TimaSignature is unavailable
,D/ActivityThread( 7972): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
I/WifiStateMachine(  890): REQUEST_POWER_SAVE_ON
,V/        (  281): QcRouteController
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,V/        (  281): QcRouteController
,D/ResourcesManager( 7972): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7972): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/        (  281): QcRouteController
W/ResourcesManager( 7972): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7972): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,V/        (  281): QcRouteController
,W/libprocessgroup(  890): failed to open /acct/uid_10003/pid_6927/cgroup.procs: No such file or directory
,V/        (  281): QcRouteController
,D/ConnectivityService(  890): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
,V/        (  281): QcRouteController
,D/QuickConnect( 7972): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,V/        (  281): QcRouteController
I/QuickConnect( 7972): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7972): PeriphStartReceiver.onReceive - no need to start
,W/NetworkManagementService(  890): route cmd failed: 
W/NetworkManagementService(  890): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '68 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 68 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  890): '
W/NetworkManagementService(  890): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  890): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  890): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  890): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  890): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  890): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  890): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  890): 	at com.android.server.ConnectivityService.updateNetworkInfo(ConnectivityService.java:5997)
W/NetworkManagementService(  890): 	at com.android.server.ConnectivityService.access$1900(ConnectivityService.java:230)
W/NetworkManagementService(  890): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2337)
W/NetworkManagementService(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  890): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  890): Setting Dns servers for network 503 to [/192.168.1.1]
,E/Zygote  ( 8005): MountEmulatedStorage()
,E/Zygote  ( 8005): v2
I/libpersona( 8005): KNOX_SDCARD checking this for 10163
I/libpersona( 8005): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=8005 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6942:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,D/Nat464Xlat(  890): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  890): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  890): updateNetworkInfo()
D/ConnectivityService(  890): calling update connectivity
E/ConnectivityService(  890): updateNetworkInfo()
D/ConnectivityService(  890): ignoring duplicate network state non-change
D/ConnectivityService(  890): ignoring duplicate network state non-change
D/ConnectivityService(  890): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  890): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890): calling update connectivity
,D/ConnectivityService(  890): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  890):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  890):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890): currentScore = 0, newScore = 60
D/ConnectivityService(  890):    accepting network in place of null
D/ConnectivityService(  890): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  890): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  890): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  890): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): DefaultState{ when=-5ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): Validated
,D/ConnectivityService(  890): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,V/NetworkStats(  890): updateIfacesLocked()
,V/NetworkStats(  890): performPollLocked(flags=0x1)
D/SmartBondingService(  890): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  890): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
,D/ConnectivityService(  890): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  890): UpdateStatsForKnox
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/EntConnectivity(  890): Not allowed due to - mEnabled false
,D/ConnectivityService(  890): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890): calling update connectivity
,V/NetworkStats(  890): performPollLocked() took 6ms
,D/NtpTrustedTime(  890): currentTimeMillis() cache hit
,D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  890): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  890): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  890):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  890): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  890): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890): calling update connectivity
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  890): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  890): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/SELinux ( 8005): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/TelephonyNetworkFactory( 1474): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/SELinux ( 8005): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8005): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524290
,D/SmartBondingService(  890): getNetworkEnabled : wifi : true mobile : true
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
V/NetworkStats(  890): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/TimaKeyStoreProvider( 8005): TimaSignature is unavailable
,D/ActivityThread( 8005): Added TimaKeyStore provider
,W/libprocessgroup(  890): failed to open /acct/uid_10020/pid_6942/cgroup.procs: No such file or directory
,D/ResourcesManager( 8005): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8005): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8005): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8005): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8005): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,E/Zygote  ( 8030): MountEmulatedStorage()
E/Zygote  ( 8030): v2
I/libpersona( 8030): KNOX_SDCARD checking this for 10078
I/libpersona( 8030): KNOX_SDCARD not a persona
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,I/ActivityManager(  890): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8030 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,I/SELinux ( 8030): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8030): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SELinux ( 8030): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,D/SecurityLogAgent( 7588): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7588): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7588): StateMachine : Current State = 1
V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7588): StateMachine : Changed Current State = 1
,D/TimaKeyStoreProvider( 8030): TimaSignature is unavailable
,D/ActivityThread( 8030): Added TimaKeyStore provider
,I/ActivityManager(  890): Killing 6953:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,I/ActivityManager(  890): Killing 6978:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,D/com.peel.receiver.ConnectivityActionReceiver( 1820): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 1820): 
D/com.peel.receiver.ConnectivityActionReceiver( 1820): 
D/com.peel.receiver.ConnectivityActionReceiver( 1820): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 1820): 
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 1820): 
D/com.peel.receiver.ConnectivityActionReceiver( 1820): 
D/com.peel.receiver.ConnectivityActionReceiver( 1820):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 1820): 
D/com.peel.receiver.ConnectivityActionReceiver( 1820): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 1820): 
D/com.peel.receiver.ConnectivityActionReceiver( 1820): 
D/com.peel.receiver.ConnectivityActionReceiver( 1820): last run: 1453102420700 -- System.currentTimeMillis()-last_run: 31804881
D/com.peel.receiver.ConnectivityActionReceiver( 1820): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 1820): ... skip last_72_check
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 8005): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,E/Zygote  ( 8046): MountEmulatedStorage()
E/Zygote  ( 8046): v2
I/libpersona( 8046): KNOX_SDCARD checking this for 10178
I/libpersona( 8046): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8046 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  324): Explicit concurrent mark sweep GC freed 8736(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 283us total 11.900ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 8.138ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 8.430ms
,I/SELinux ( 8046): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8046): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8046): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8046): TimaSignature is unavailable
,D/ActivityThread( 8046): Added TimaKeyStore provider
,W/libprocessgroup(  890): failed to open /acct/uid_10112/pid_6978/cgroup.procs: No such file or directory
,W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_6953/cgroup.procs: No such file or directory
,I/art     (  890): Explicit concurrent mark sweep GC freed 75877(4MB) AllocSpace objects, 13(338KB) LOS objects, 30% free, 36MB/52MB, paused 1.763ms total 98.738ms
,D/ResourcesManager( 8030): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ResourcesManager( 8046): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/BadgeProvider( 8030): onCreate
,D/BadgeProvider( 8030): DatabaseHelper
,W/ActivityManager(  890): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager(  890): Killing 6995:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BadgeProvider( 8030): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BadgeProvider( 8030): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8030): sendNotify, [notify] : null
D/BadgeProvider( 8030): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8030): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 8030): update, [UpdateCount] : 1
,D/Launcher.Model( 1484): reloadBadges entered.
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2469): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup(  890): failed to open /acct/uid_10118/pid_6995/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2469): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  890): MasterInitialState.processMessage what=3
,D/SmartBondingService(  890): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  890): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  890): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  890): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  890): CLocinfo wifi true 
D/SmartBondingService(  890): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  890): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2224): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2224): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5366): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3829): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3829): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
I/SystemBroadcastReceiver( 7109): [#DCM#] [DCM_Performance] onReceive completed in time  188 microsec. 
,I/SystemBroadcastReceiver( 7109): [#DCM#] Calling notifyListeners. 
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DCMController( 7109): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7109): [#DCM#] setIsConnectedForExtractors 
,D/accuweather( 2137): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DatabaseRebuilderTask( 7109): [#DCM#] postDBrebuildIntent rebuildLocation =  true
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7090): notifyNetworkActivated
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FrameworkService( 7109): [#DCM#] onCreate FrameworkService 
,I/FrameworkService( 7109): [#DCM#] onCreate FrameworkService end 
,I/DCMConfig( 7109): [#DCM#] getSuccessState = true
,I/FrameworkService( 7109): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
I/IntentHandler( 7109): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,I/SystemUtils( 7109): [#DCM#] LM: false,AM:653615104
,I/DCMThreadPoolExecutor( 7109): [#DCM#] Task being added DatabaseRebuilderTask
,I/DCMThreadPoolExecutor( 7109): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@2d50b3c6 is submitted
,I/FrameworkService( 7109): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 24207 mirosec. 
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  890): mCursor = null
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,W/ContextImpl( 7090): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  890): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/DatabaseRebuilderTask( 7109): [#DCM#] createLuceneReader done 
,I/DatabaseRebuilderTask( 7109): [#DCM#] resyncLocation   
I/DatabaseRebuilderTask( 7109): [#DCM#] resyncLocation: querying only for documents with deleted = 0 
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,I/DatabaseRebuilderTask( 7109): [#DCM#] topDocs hits = 0
I/DatabaseRebuilderTask( 7109): [#DCM#] No of Location data to be added:  0
,I/DatabaseRebuilderTask( 7109): [#DCM#] releaseLuceneReader done 
I/DatabaseRebuilderTask( 7109): [#DCM#] Starting media manager do operation 
I/SystemUtils( 7109): [#DCM#] setHeavySharedPref set as  false
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,I/IntentHandler( 7109): [#DCM#] Stopping service with ids up to  1
,W/Kids    ( 2469): [AccountUtils] Account not ready
W/Kids    ( 2469): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2469): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2469): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2469): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2469): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2469): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2469): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2469): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2469): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2469): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2469): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2469): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DCMThreadPoolExecutor( 7109): [#DCM#] afterExecute FutureTask
I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
I/DCMController( 7109): [#DCM#] task finished =  com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@2d50b3c6
D/PanelView( 1172): There is/are notification(s) 
,D/hcjo    ( 7090): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7090): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7090): exit::IDLE
D/InitializeManagerStateMachine( 7090): entry::NETWORK_CHECK
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7090): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7090): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7090): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7090): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7090): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7090): entry::SUCCESS
D/hcjo    ( 7090): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 1307): Starting #8
,I/Hs20UtilService( 1307): Message received 5007
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,D/hcjo    ( 7090): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7090): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7090): exit::SUCCESS
D/InitializeManagerStateMachine( 7090): entry::IDLE
,I/Hs20UtilService( 1307): Starting #9
,I/Hs20UtilService( 1307): Message received 5007
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1307): Starting #10
,I/Hs20UtilService( 1307): Message received 5007
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1307): Starting #11
,I/Hs20UtilService( 1307): Message received 5007
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  890): callSECApi what=220
D/WifiStateMachine(  890): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,I/PCWCLIENTTRACE_PushUtil( 7656): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7656): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7656): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7656): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  248): id=16 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/DIAGMON_AGENT( 7700): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7700): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService(  890): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=890
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  890): [s] DisplayPowerCallbacks : onStateChanged()
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/lights  (  890): lcd : 8 +
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/lights  (  890): lcd : 8 -
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/FOTA_Client( 7719): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7719): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7719): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7719): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7719): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/KLMS-2.4.503: ( 7736): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7736): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453134226186
,I/KLMS-2.4.503: ( 7736): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7736): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7736): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7736): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7736): StateImplV2(): networkChangeListener().END
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SO_AGENT( 7751): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/SPPClientService( 7797): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 7814): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7814): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7814): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7814): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7814): [OR] == isSIMCardReady false ==
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
I/SA      ( 7814): [SCU] == networkStateCheck == true
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/SA      ( 7814): [DM] getCountryCodeFromCSC : DE
I/SA      ( 7814): isChinaCountryCode : false
I/SA      ( 7814): [SCU] is ChinestModel Data Restricted   : false
,I/SA      ( 7814): [OR] == networkStateCheck true ==
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
I/SA      ( 7814): [OR] GetMyCountryZoneTask
,I/SA      ( 7814): [OR] onReceive END
,I/SA      ( 7814): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7814): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7814): [SSP] query invoked
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/accuweather( 7312): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7312): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/SA      ( 7814): [TPMU] GetMccFromDB : null
,I/KnoxUsageLogPro( 7836): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7836): premStatus:2
,I/SA      ( 7814): [SCU] getMccFromPreferece mcc = 260
,I/KnoxUsageLogPro( 7836): isEulaShown : false
I/KnoxUsageLogPro( 7836): KnoxUsageReceiver onReceive : not Processible, just return
I/SA      ( 7814): [TPM] isNoProxy(default) : true
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  890): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/Headlines( 5512): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5512): getCountryCode(): countryCode = DE
,D/Headlines( 5512): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5512): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5512): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5512): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5512): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5512): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5512): requestUpdateNewsWelcomeCard !!! no welcome card
,E/File    ( 7814): fail readDirectory() errno=2
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7972): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7972): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7972): PeriphStartReceiver.onReceive - no need to start
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7588): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7588): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7588): StateMachine : Current State = 1
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7588): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 1820): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 1820): 
D/com.peel.receiver.ConnectivityActionReceiver( 1820): 
D/com.peel.receiver.ConnectivityActionReceiver( 1820): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 1820): 
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 1820): 
D/com.peel.receiver.ConnectivityActionReceiver( 1820): 
D/com.peel.receiver.ConnectivityActionReceiver( 1820):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 1820): 
D/com.peel.receiver.ConnectivityActionReceiver( 1820): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 1820): 
D/com.peel.receiver.ConnectivityActionReceiver( 1820): 
D/com.peel.receiver.ConnectivityActionReceiver( 1820): last run: 1453102420700 -- System.currentTimeMillis()-last_run: 31805648
D/com.peel.receiver.ConnectivityActionReceiver( 1820): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 1820): ... skip last_72_check
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/jxcore-log( 7520): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7520): 
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ChimeraCfgMgr( 2469): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/ChimeraCfgMgr( 2469): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7090): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7090): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7090): exit::IDLE
D/InitializeManagerStateMachine( 7090): entry::NETWORK_CHECK
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7090): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7090): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7090): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7090): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7090): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7090): entry::SUCCESS
D/hcjo    ( 7090): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7090): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7090): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7090): exit::SUCCESS
D/InitializeManagerStateMachine( 7090): entry::IDLE
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2469): [AccountUtils] Account not ready
W/Kids    ( 2469): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2469): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2469): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2469): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2469): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2469): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2469): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2469): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2469): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2469): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2469): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2469): 	at java.lang.Thread.run(Thread.java:818)
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/SA      ( 7814): [RC New] Execute method=[GET] start
,I/SA      ( 7814): [RC New] Security=[true]
,I/System.out( 7814): Thread-1291(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7814): Thread-1291(ApacheHTTPLog):isShipBuild true
,I/System.out( 7814): Thread-1291(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7520): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7520): 
,I/jxcore-log( 7520): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7520): 
,E/SMD     (  288): DCD ON
,I/jxcore-log( 7520): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7520): 
,I/jxcore-log( 7520): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7520): 
,I/jxcore-log( 7520): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7520): 
,I/jxcore-log( 7520): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7520): 
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,W/ProcessCpuTracker(  890): Skipping unknown process pid 7663
,W/ProcessCpuTracker(  890): Skipping unknown process pid 7664
,W/ProcessCpuTracker(  890): Skipping unknown process pid 7675
,W/ProcessCpuTracker(  890): Skipping unknown process pid 7680
,W/ProcessCpuTracker(  890): Skipping unknown process pid 8088
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/SA      ( 7814): [RC New] [v2liruge] api execute + 628
,I/SA      ( 7814): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 7814): AsyncTask #1 calls detatch()
,I/SA      ( 7814): [ODM] saveOpenData( GEO_IP, PL )
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/SA      ( 7814): [OCP] update openData : PL
,I/SA      ( 7814): [TPMU] getNetworkMcc : 
,I/SA      ( 7814): [SCU] saveMccToPreferece Start
,I/SA      ( 7814): [SCU] RegionMCC : 260
I/SA      ( 7814): [SSP] query invoked
,I/SA      ( 7814): [TPMU] GetMccFromDB : null
,I/SA      ( 7814): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7814): [SCU] saveMccToPreferece End
,I/SA      ( 7814): [RC New] executeRequest [v2liruge] end. 733
,I/SA      ( 7814): [RC New] Execute end
,I/SA      ( 7814): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7814): [OR] GetMyCountryZoneTask Success
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7520): Test app app.js loaded
I/jxcore-log( 7520): 
,I/chromium( 7520): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7520): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7520): BLE advertisement is supported
I/jxcore-log( 7520): 
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7781): wlan0: sending IPv6 Router Solicitation
,D/PackageManager(  890): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager(  890): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  890): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8091): MountEmulatedStorage()
E/Zygote  ( 8091): v2
I/libpersona( 8091): KNOX_SDCARD checking this for 10034
I/libpersona( 8091): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8091 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/SELinux ( 8091): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8091): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8091): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 1484): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,D/RegisteredServicesCache( 1464): empty dynamic service
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 1484): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1484): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1484): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/TimaKeyStoreProvider( 8091): TimaSignature is unavailable
,D/ActivityThread( 8091): Added TimaKeyStore provider
,D/ResourcesManager( 1484): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager( 8091): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Books/Books.apk
,W/ResourcesManager( 1484): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1484): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/FeatureConfig( 8091): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService(  890): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  890): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  890): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  890): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 8091): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8091): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8091): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8091): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8091): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 8091): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 8091): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 8091): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8091): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 8091): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8091): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 8091): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 8091): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8091): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8091): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8091): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 8091): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 8091): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8091): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8091): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8091): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8091): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 8091): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8091): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 8091): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8091): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8091): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8091): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8091): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8091): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 8091): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8091): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8091): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8091): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8091): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8091): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 8091): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 8091): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 8091): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 8091): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 8091): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 8091): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8091): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8091): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 8091): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 8091): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/Atfwd_Sendcmd(  344): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  344): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8120): MountEmulatedStorage()
,E/Zygote  ( 8120): v2
I/libpersona( 8120): KNOX_SDCARD checking this for 10035
I/libpersona( 8120): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=8120 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 7012:com.samsung.helphub/1000 (adj 15): bgCount ##41
,I/SELinux ( 8120): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8120): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8120): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_7012/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8120): TimaSignature is unavailable
,D/ActivityThread( 8120): Added TimaKeyStore provider
,D/ResourcesManager( 8120): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): checkState()
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): checkState() : APP TYPE = Full
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
V/AlarmManager(  890): waitForAlarm result :8
,E/Zygote  ( 8142): MountEmulatedStorage()
E/Zygote  ( 8142): v2
I/libpersona( 8142): KNOX_SDCARD checking this for 10017
I/libpersona( 8142): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=8142 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,I/SELinux ( 8142): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8142): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8142): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8142): TimaSignature is unavailable
,D/ActivityThread( 8142): Added TimaKeyStore provider
,D/ResourcesManager( 8142): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1674): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_google_search.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/BluetoothManager( 8120): getConnectedDevices
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/-----SIC-----( 8120): ------------------skip uv
,D/-----SIC-----( 8120): ------------------skip SPO2
,W/Search.LoginHelper( 1554): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,D/-----SIC-----( 8120): ------------------skip TGH
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,I/SecureStorage( 8142): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  357): [INFO]: SPID(0x00000005)Credentials: uid 10017, gid 10017, pid 8142
I/SecureStorage(  357): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,E/Vold    (  247): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8120): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,E/Vold    (  247): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8120): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,V/MediaPlayer( 8120): decode(33, 19359868, 4230)
,V/MediaPlayerService(  293): decode(32, 19359868, 4230)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(32, 19359868, 4230)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf8094c0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
,V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xaf8094c0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf8094c0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf8094c0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf8094c0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
,V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): First fillBuffer call!!
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf8094c0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf8094c0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthServiceInstalled() : HealthService is Installed.
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf8094c0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x74, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
,V/AwesomePlayer(  293): reset_l()
,V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,V/MediaPlayer( 8120): decode(32, 19213040, 15440)
,V/MediaPlayerService(  293): decode(32, 19213040, 15440)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(32, 19213040, 15440)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef190b0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xaef190b0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef190b0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef190b0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(2)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef190b0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
,I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/ActivityManager(  890): Killing 7049:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,I/WifiStateMachine(  890): REQUEST_POWER_SAVE_ON
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef190b0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef190b0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef190b0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x75, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,V/MediaPlayer( 8120): decode(36, 19257568, 9226)
V/MediaPlayerService(  293): decode(32, 19257568, 9226)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(32, 19257568, 9226)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb08543d0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
,V/AwesomePlayer(  293): onPrepareAsyncEvent
,D/AdaptiveEventManager( 1172): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1172): M updateContainers()
D/AdaptiveEventContainerSmall( 1172): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1172): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1172): pedoEvent == null
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb08543d0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb08543d0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb08543d0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  293): Audio channels(2)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb08543d0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/AlarmManager(  890): waitForAlarm result :4
D/AdaptiveEventManager( 1172): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
V/MediaPlayerService(  293): wait for playback complete
D/AdaptiveEventManager( 1172): M updateContainers()
D/AdaptiveEventContainerSmall( 1172): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1172): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1172): pedoEvent == null
,I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,E/WifiStateMachine(  890): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb08543d0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb08543d0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb08543d0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x76, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/MediaPlayer( 8120): decode(37, 19364180, 4890)
V/MediaPlayerService(  293): decode(32, 19364180, 4890)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
,V/AwesomePlayer(  293): reset_l()
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(32, 19364180, 4890)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef191f0, 8, 0, 0)
,V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
,V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,E/DatabaseUtils(  890): Writing exception to parcel
E/DatabaseUtils(  890): java.lang.NullPointerException: key == null
E/DatabaseUtils(  890): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils(  890): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils(  890): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils(  890): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/DatabaseUtils(  890): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils(  890): 	at android.os.Binder.execTransact(Binder.java:446)
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
,V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
,V/AwesomePlayer(  293): onPrepareAsyncEvent
,I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
,V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,E/Zygote  ( 8198): MountEmulatedStorage()
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/libpersona( 8198): KNOX_SDCARD checking this for 10075
E/Zygote  ( 8198): v2
I/libpersona( 8198): KNOX_SDCARD not a persona
I/ActivityManager(  890): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=8198 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xaef191f0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef191f0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef191f0, 1, 0, 0)
V/AudioCache(  293): prepared
D/PowerManagerService(  890): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  890): [PWL] On : 78436 (30001 ms ago)
,I/PowerManagerService(  890): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
I/PowerManagerService(  890): [PWL]  SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=890, ws=WorkSource{10059}) (elapsedTime=2870)
,V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
I/UpdateIcingCorporaServi( 1554): Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
,V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef191f0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
,I/SELinux ( 8198): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
I/SELinux ( 8198): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8198): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef191f0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef191f0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  293): notify(0xaef191f0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x77, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
,I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/ActivityManager(  890): Killing 7070:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): bgCount ##41
,I/AudioPlayer(  293): reset out
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
,V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4260, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
V/MediaPlayer( 8120): decode(38, 19290344, 17329)
,V/MediaPlayerService(  293): decode(32, 19290344, 17329)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
,V/AwesomePlayer(  293): setDefault
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
V/AwesomePlayer(  293): reset_l()
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
,V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
,V/StagefrightPlayer(  293): setDataSource(32, 19290344, 17329)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809380, 8, 0, 0)
V/AudioCache(  293): ignored
I/MotionRecognitionService(  890): Plugged
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/MotionRecognitionService(  890): setPowerConnected  = true
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
,V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xaf809380, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809380, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809380, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(2)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809380, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
V/MediaPlayerService(  293): wait for playback complete
D/TimaKeyStoreProvider( 8198): TimaSignature is unavailable
,D/ActivityThread( 8198): Added TimaKeyStore provider
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
,V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809380, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
,V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809380, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809380, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x78, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/MediaPlayer( 8120): decode(39, 19190536, 6644)
,V/MediaPlayerService(  293): decode(32, 19190536, 6644)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(32, 19190536, 6644)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809100, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
,V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xaf809100, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809100, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809100, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809100, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/MediaPlayerService(  293): wait for playback complete
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809100, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809100, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809100, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x79, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
W/libprocessgroup(  890): failed to open /acct/uid_10166/pid_7049/cgroup.procs: No such file or directory
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
,I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
D/ResourcesManager( 8198): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,V/MediaPlayer( 8120): decode(40, 19266876, 23389)
,V/MediaPlayerService(  293): decode(32, 19266876, 23389)
V/MediaPlayerService(  293): player type = 3
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(32, 19266876, 23389)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf8094c0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xaf8094c0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf8094c0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf8094c0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(2)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf8094c0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
V/MediaPlayerService(  293): wait for playback complete
,D/FileShare-Server( 8198): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,I/UpdateIcingCorporaServi( 1554): UpdateCorporaTask done [took 121 ms] updated apps [took 121 ms] 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,W/libprocessgroup(  890): failed to open /acct/uid_10170/pid_7070/cgroup.procs: No such file or directory
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
,V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf8094c0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf8094c0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf8094c0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x7a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
V/StagefrightPlayer(  293): ~StagefrightPlayer
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
V/StagefrightPlayer(  293): reset
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
V/AwesomePlayer(  293): reset_l()
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/MediaPlayer( 8120): decode(41, 19156232, 8154)
V/MediaPlayerService(  293): decode(32, 19156232, 8154)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(32, 19156232, 8154)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef190b0, 8, 0, 0)
V/AudioCache(  293): ignored
,V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
,I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
,V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache(  293): notify(0xaef190b0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
V/AudioCache(  293): notify(0xaef190b0, 5, 0, 0)
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
V/AudioCache(  293): ignored
,V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef190b0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef190b0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,E/Zygote  ( 8232): MountEmulatedStorage()
E/Zygote  ( 8232): v2
I/libpersona( 8232): KNOX_SDCARD checking this for 1000
I/libpersona( 8232): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=8232 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,V/MediaPlayerService(  293): wait for playback complete
,I/ActivityManager(  890): Killing 6184:com.google.android.gm/u0a114 (adj 15): bgCount ##41
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
,V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef190b0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache(  293): notify(0xaef190b0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
,V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  293): notify(0xaef190b0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x7b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
,I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
,I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
,V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,V/MediaPlayer( 8120): decode(42, 19129712, 4804)
,V/MediaPlayerService(  293): decode(32, 19129712, 4804)
I/SELinux ( 8232): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,V/MediaPlayerService(  293): player type = 3
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
I/SELinux ( 8232): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
E/SELinux ( 8232): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
,V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(32, 19129712, 4804)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb08543d0, 8, 0, 0)
V/AudioCache(  293): ignored
,V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,D/Utils   (  293): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb08543d0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb08543d0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb08543d0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb08543d0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): First fillBuffer call!!
,I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb08543d0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb08543d0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb08543d0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,V/MediaPlayer( 8120): decode(43, 19099164, 9400)
V/MediaPlayerService(  293): decode(32, 19099164, 9400)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
D/TimaKeyStoreProvider( 8232): TimaSignature is unavailable
,D/ActivityThread( 8232): Added TimaKeyStore provider
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(32, 19099164, 9400)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef191f0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xaef191f0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef191f0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef191f0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,V/MediaPlayer( 8120): decode(49, 19172584, 4112)
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,V/MediaPlayerService(  293): decode(35, 19172584, 4112)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/AudioPlayer(  293): Audio channels(1)
V/AwesomePlayer(  293): mSecCapture clear
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
V/AwesomePlayer(  293): mSecMediaClock clear
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(35, 19172584, 4112)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809380, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(38) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef191f0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
,I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 811298076, value : 198833648
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 811298076, value : 198833648
,V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/ResourcesManager( 8232): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xaf809380, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809380, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809380, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809380, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
,V/MediaPlayerService(  293): wait for playback complete
,I/AudioPlayer(  293): First fillBuffer call!!
I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809380, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809380, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809380, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x7e, OMX_CommandStateSet, OMX_StateIdle)
V/AwesomePlayer(  293): postAudioEOS delayUs (0)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef191f0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef191f0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
V/AudioCache(  293): notify(0xaef191f0, 8, 0, 0)
V/AudioCache(  293): ignored
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
V/AwesomePlayer(  293): mAudioTrackVector clear
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --,
I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/MediaPlayer( 8120): decode(44, 19307764, 52024)
V/MediaPlayerService(  293): decode(32, 19307764, 52024)
V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(32, 19307764, 52024)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809100, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xaf809100, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809100, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809100, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  293): Audio channels(2)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(48000, 2, 0x0, 1, 0)
V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809100, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
V/MediaPlayerService(  293): wait for playback complete
W/libprocessgroup(  890): failed to open /acct/uid_10114/pid_6184/cgroup.procs: No such file or directory
D/ShortcutReceiver( 8232):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
,V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809100, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809100, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  293): addBatteryData
,V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
,V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809100, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x7f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
,I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/AudioPlayer(  293): reset out
,D/PackageBroadcastService( 2469): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/MediaPlayer( 8120): decode(45, 19172584, 4112)
,V/MediaPlayerService(  293): decode(32, 19172584, 4112)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(32, 19172584, 4112)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf8094c0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
,V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xaf8094c0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf8094c0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf8094c0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf8094c0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf8094c0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf8094c0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthServiceInstalled() : HealthService is Installed.
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf8094c0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/MediaPlayer( 8120): decode(46, 19235660, 21825)
V/MediaPlayerService(  293): decode(32, 19235660, 21825)
V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(32, 19235660, 21825)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef190b0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
,V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xaef190b0, 200, 973, 0)
,V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef190b0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef190b0, 1, 0, 0)
,V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
,I/PeopleContactsSync( 2469): CP2 sync disabled
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(2)
,I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef190b0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
,I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,V/MediaPlayerService(  293): wait for playback complete
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,I/ActivityManager(  890): Killing 7151:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##41
V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef190b0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef190b0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaef190b0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/MediaPlayer( 8120): decode(47, 19134596, 21552)
V/MediaPlayerService(  293): decode(32, 19134596, 21552)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(32, 19134596, 21552)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb08543d0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb08543d0, 200, 973, 0)
V/AudioCache(  293): ignored
,V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb08543d0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb08543d0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
,V/AwesomePlayer(  293): play
,V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(2)
,I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb08543d0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
,I/AudioPlayer(  293): First fillBuffer call!!
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
,V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb08543d0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache(  293): notify(0xb08543d0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb08543d0, 8, 0, 0)
,V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
,I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
,I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
,V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,V/AwesomePlayer(  293): reset_l()
,V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,V/MediaPlayer( 8120): decode(48, 19228560, 7017)
,V/MediaPlayerService(  293): decode(32, 19228560, 7017)
V/MediaPlayerService(  293): player type = 3
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
,V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(32, 19228560, 7017)
V/AwesomePlayer(  293): reset_l()
,V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809380, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
,V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
,V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xaf809380, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809380, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809380, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
,V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(2)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809380, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
,I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,W/libprocessgroup(  890): failed to open /acct/uid_10044/pid_7151/cgroup.procs: No such file or directory
V/AwesomePlayer(  293): onCheckAudioStatus
,V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809380, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache(  293): notify(0xaf809380, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): addBatteryData
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xaf809380, 8, 0, 0)
,V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
,I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
,V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/SecureStorage(  357): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
I/SecureStorage(  357): [INFO]: SPID(0x00000005)PID: 8142, TID: 8154
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PowerManagerService(  890): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 890) eventTime = 109043
,D/PowerManagerService(  890): [s] UserActivityState : 4 -> 1
D/PowerManagerService(  890): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=890 (0x0)
D/PowerManagerService(  890): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=890, ws=WorkSource{10059}) (elapsedTime=3477)
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/GCM     ( 1674): Connected
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1674): Message class com.google.f.a.a.p
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SecureStorage( 8142): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 8142): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
I/SecSQLiteOpenHelper( 8120): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper( 8120): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper( 8120): Open platform.db in secure mode
,D/SecSQLiteDatabase( 8120): Android Version: 5.0
D/SecSQLiteDatabase( 8120): Load library secsqlite.so for Android 5.0
,I/GAV4    ( 7889): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SecSQLiteDatabase( 8120): openSecureDatabase...
,I/SecSQLiteDatabase( 8120): private openSecureDatabase...
,I/SecSQLiteConnectionPool( 8120): OpenSecure
I/SecSQLiteConnectionPool( 8120): OpenSecure with password
I/SecSQLiteConnectionPool( 8120): openSecureConnectionLocked
,I/SecSQLiteDatabase( 8120): ...private openSecureDatabase
,I/SecSQLiteDatabase( 8120): ...openSecureDatabase
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/SecSQLiteOpenHelper( 8120): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper( 8120): ...getDatabaseLocked(b,b,pwd)
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthServiceInstalled() : HealthService is Installed.
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 8120): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
D/LockPatternUtilsCache( 1172): value : false
,W/System.err( 8120): java.lang.NumberFormatException: Invalid int: "null"
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,W/System.err( 8120): 	at java.lang.Integer.invalidInt(Integer.java:138)
W/System.err( 8120): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err( 8120): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err( 8120): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:449)
W/System.err( 8120): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1173)
W/System.err( 8120): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8120): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 8120): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/SSRM:m  (  890): SIOP:: AP = 430, PST = 436, CUR = 300
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/SMD     (  288): DCD ON
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SurfaceFlinger(  248): id=16 Removed Toast (8/8)
,I/SurfaceFlinger(  248): id=16 Removed Toast (-2/8)
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7656): mConnectivityHandler : connected
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7656): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 7656): ================================================
I/CSTORAGE( 7656):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 7656): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7656): [GetString-S]
E/art     ( 7656): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 7656): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7656): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7656): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7656): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7656): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7656): [ensureRegistration] - No Samsung account
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7781): wlan0: sending IPv6 Router Solicitation
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/SMD     (  288): DCD ON
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/GAV3    ( 8120): Thread[GAThread,5,main]: No campaign data found.
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,I/dhcpcd  ( 7781): wlan0: sending IPv6 Router Solicitation
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
I/dhcpcd  ( 7781): wlan0: no IPv6 Routers available
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/PreloadUpdateManagerStateMachine( 7090): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7090): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7090): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7090): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,E/SMD     (  288): DCD ON
,D/hcjo    ( 7090): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7090): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7090): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7090): entry::IDLE
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020471/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,V/BitmapFactory( 1172): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_signal_out.png
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,D/PreloadUpdateManagerStateMachine( 7090): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7090): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7090): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7090): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7090): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7090): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7090): entry::IDLE
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/FactoryTest( 6651): Not factory mode
,D/FactoryTest( 6651): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6651): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6651): still no open session command from host, so toast
,W/ContextImpl( 6651): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6651): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
I/Timeline( 6651): Timeline: Activity_launch_request id:com.android.settings time:116614
,E/PersonaManagerService(  890): inState():  stateMachine is null !!
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  890): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  890): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 890  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  890): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/MTPRx   ( 6651): started activity for popup
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SQLiteSecureOpenHelper( 3577): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3577): getDatabaseLocked(b,b,pwd)...
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/ResourcesManager( 6651): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6651): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6651): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6651): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6651): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6651): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6651): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6651): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6651): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/InputMethodManagerService(  890): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,E/ActivityManager(  890): Invalid thumbnail dimensions: 576x576
,W/InputMethodManagerService(  890): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@39912132 attribute=null, token = android.os.BinderProxy@2c943e71
,I/SQLiteSecureOpenHelper( 3577): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3577): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6651): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6651): dev.kiessupport is : TRUE
,D/Activity( 6651): performCreate Call secproduct feature valuefalse
D/Activity( 6651): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ActivityManager(  890): post active user change for 0
D/KnoxTimeoutHandler(  890): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  890): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/Timeline( 7520): Timeline: Activity_idle id: android.os.BinderProxy@42f7e31 time:116855
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,V/AlarmManager(  890): waitForAlarm result :4
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6546): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6546): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6546): [1] 5.onFinished: Scheduling replication attempt 3.
,I/art     (  890): Explicit concurrent mark sweep GC freed 62986(3MB) AllocSpace objects, 9(2MB) LOS objects, 30% free, 36MB/52MB, paused 1.290ms total 91.679ms
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/SMD     (  288): DCD ON
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  890): SIOP:: AP = 400, PST = 429, CUR = 300
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  890): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/CustomFrequencyManagerService(  890): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 890  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  890): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  890): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 890  pkgName : ACTIVITY_RESUME_BOOSTER@10
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/StatusBar.NetworkController( 1172): applyOpen
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  890): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 890  tag : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/SMD     (  288): DCD ON
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/SMD     (  288): DCD ON
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/SMD     (  288): DCD ON
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 2
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  890): SIOP:: AP = 360, PST = 416, CUR = 300
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/SMD     (  288): DCD ON
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  890): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  890): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  890): lcd : 2 +
,D/lights  (  890): lcd : 2 -
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
D/lights  (  890): lcd : 1 +
,D/lights  (  890): lcd : 1 -
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/SMD     (  288): DCD ON
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/Watchdog(  890): !@Sync 4
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560,
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1,
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/SMD     (  288): DCD ON
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,V/AlarmManager(  890): waitForAlarm result :4
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6546): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6546): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6546): [1] 5.onFinished: Scheduling replication attempt 4.
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen,
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560,
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  890): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  890): Nap time (uid 1000)...
,I/PowerManagerService(  890): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  890): Going to sleep due to screen timeout (uid 1000)...
,D/PowerManagerService(  890): [PWL] sb acquire: PowerManagerService.Broadcasts
D/InputManager-JNI(  890): setDeviceInteractive: 0
D/PowerManagerService(  890): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService(  890): handleSandman : startDream(),
,E/PowerManagerService(  890): handleSandman : startDreaming, but isDreaming false,
,I/PowerManagerService(  890): Sleeping (uid 1000)...,
,D/PowerManagerService(  890): [s] UserActivityState : 4 -> 0,
,I/SurfaceFlinger(  248): id=17 createSurf (1080x1920),2 flag=404, ColorFade,
,D/PowerManagerService(  890): [input device light] setInputDeviceLightOn is called : 0,
,D/InputManager-JNI(  890): sysfs_write +: /sys/class/input/event1/device/enabled: 0,
,D/PowerManagerService(  890): [input device light] handleInputDeviceLightOff,
,D/InputManager-JNI(  890): sysfs_write +: /sys/class/input/event2/device/enabled: 0,
D/InputManager-JNI(  890): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/InputManager-JNI(  890): sysfs_write -: /sys/class/input/event2/device/enabled: 0
D/SContextService(  890): 	.unregisterCallback : 1, client=
,D/SContextService(  890): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@fd1654e, Service = Auto Rotation, used = 1
,W/CAE     (  890): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  890): stop(ContextProvider.java:149)
,V/CAE     (  890): clear(AutoRotationRunner.java:182)
,V/CAE     (  890): disable(AutoRotationRunner.java:171)
,I/CAE     (  890): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  890): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  302): sendContextData: -78, 7, 0, 0
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/CAE     (  890): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  890): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  890): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  890): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  890): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  890): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  890): removeSContextService() : service = Auto Rotation
D/SContextService(  890): ===== SContext Service List =====
D/SContextManager(  890):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@292c4656, service=Auto Rotation
,D/DisplayPowerController(  890): ColorFade: onAnimationStart
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 0
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 0
,I/SQLiteSecureOpenHelper( 3577): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3577): getDatabaseLocked(b,b,pwd)...
I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,D/KeyguardViewMediator( 1172): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1172): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1172): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1172): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/KeyguardViewMediator( 1172): timeout : 5000
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/lights  (  890): lcd : 0 +
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 0
,D/lights  (  890): lcd : 0 -
,D/KeyguardViewMediator( 1172): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 1172): handleNotifyScreenOff
,D/LightsService(  890): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 890) 
,D/LightsService(  890): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  890): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  890): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  890): unregisterListener ::   
D/BatteryService(  890): turn on LED for fully charged
,D/lights  (  890): led_pattern : 5 +
,D/lights  (  890): led_pattern : 5 -
,D/LightsService(  890): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  890): handleMessage(CaPowerManager.java:182) - AP_SLEEP
I/CAE     (  890): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
,I/CAE     (  890): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
,D/SensorHubManager(  890): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  302): sendContextData: -76, 13, -46, 0
,I/CAE     (  890): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 16, 24, 19,
D/SensorHubManager(  890): SendSensorHubData: send data = -63, 14, 16, 24, 19
D/Sensorhubs(  302): sendContextData: -63, 14, 16, 24, 19
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 0
,E/MotionRecognitionService(  890):  handler : SCREEN_OFF end 
,D/WifiStateMachine(  890): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  890): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  890): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  890): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  890): do suspend true
,D/NotificationService(  890): ACTION_SCREEN_OFF
D/LightsService(  890): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 890) 
D/LightsService(  890): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/LightsService(  890): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  890): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  890): unregisterListener ::   
,D/LightsService(  890): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  293): adev_set_parameters: enter: screen_state=off
V/voice   (  293): voice_set_parameters: enter: screen_state=off
,V/voice   (  293): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  293): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  293): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  293): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  293): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  890): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  890): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  890): Bridge Server is not available
,D/VolumePanel( 1172): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1172): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1172): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1172): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  890): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  890): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1464): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1172):      ACTION_SCREEN_OFF is finished!!!! 
,D/DisplayPowerState(  890): !@ ColorFade entry
D/DisplayPowerController(  890): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  890): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  890): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
,I/AutomaticBrightnessController(  890): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/AutomaticBrightnessController(  890): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/StatusBar( 1172): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1172): dismissHelpPopup 
E/LightSensor(  890): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,D/SensorManager(  890): unregisterListener ::   
,E/Sensors (  890): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/accuweather( 2137): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2137): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2137): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/SensorManager(  890): unregisterListener ::   
,D/DisplayPowerController(  890): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  890): getFinalBrightness : 0 -> 0
,D/SurfaceFlinger(  248): Set power mode=0, type=0 flinger=0xb6962000
D/qdhwcomposer(  248): hwc_blank: Blanking display: 0
I/DisplayManagerService(  890): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  890): Display changed displayId=0
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/StatusBar.NetworkController( 1172): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/SystemBroadcastReceiver( 7109): [#DCM#] [DCM_Performance] onReceive completed in time  1965 microsec. 
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SystemBroadcastReceiver( 7109): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7109): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 7109): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/SSRM:m  (  890): SIOP:: AP = 340, PST = 401, CUR = 300
,D/X       (  890): broadcastSiopLevelIntent:: currentSiopLevel = -1
,D/ContentApp( 1220):  LEVEL : -1
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/SystemBroadcastReceiver( 7109): [#DCM#] [DCM_Performance] onReceive completed in time  3301 microsec. 
,I/SystemBroadcastReceiver( 7109): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7109): [#DCM#] onReceive action = EVENT_SIOP
,E/Zygote  ( 8368): MountEmulatedStorage()
E/Zygote  ( 8368): v2
I/libpersona( 8368): KNOX_SDCARD checking this for 10054
I/libpersona( 8368): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=8368 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,W/ActivityManager(  890): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  890): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,I/SELinux ( 8368): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8368): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8368): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PowerManagerService(  890): [PWL] sb release: PowerManagerService.Broadcasts
,D/TimaKeyStoreProvider( 8368): TimaSignature is unavailable
,D/ActivityThread( 8368): Added TimaKeyStore provider
,D/ResourcesManager( 8368): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8368): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8368): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8368): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8368): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8368): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/SMD     (  288): DCD ON
,I/rmt_storage(  277): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
,I/rmt_storage(  277): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  277): wakelock acquired: 1, error no: 42
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1229454592)
,I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1229454592) wakelock released: 1, error no: 22
I/rmt_storage(  277): 
,I/rmt_storage(  277): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
,E/TranscodeReceiver( 8368): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 8368): core_num = 4
,W/linker  ( 8368): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/qdhwcomposer(  248): hwc_blank: Done blanking display: 0
I/qdhwcomposer(  248): handle_blank_event: dpy:0 panel power state: 0
,D/SurfaceControl(  890): Excessive delay in setPowerMode(): 255ms
,D/PowerManagerService(  890): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  890): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  890): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
W/linker  ( 8368): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,I/QCOM PowerHAL(  890): Got set_interactive hint
,I/PowerManagerService(  890): [PWL] Off : 0s ago
I/PowerManagerService(  890): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  890): [PWL]     mDisplayReady : false
D/DisplayPowerController(  890): getFinalBrightness : 0 -> 0
D/PowerManagerService(  890): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  890): [PWL] sb release: PowerManagerService.Display
,D/videowall-Global( 8368): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
D/videowall-Global( 8368): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 8368):  SIOP_LEVEL: -1
,I/ActivityManager(  890): Killing 5044:com.android.defcontainer/u0a5 (adj 15): bgCount ##41
,W/libprocessgroup(  890): failed to open /acct/uid_10005/pid_5044/cgroup.procs: No such file or directory
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager(  890): waitForAlarm result :4
,D/KeyguardViewMediator( 1172): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/KeyguardViewMediator( 1172): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService(  890): [PWL] Off : 5s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 330, PST = 388, CUR = 300
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): stay LED for fully charged
D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6519): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6519): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6519): 	at kfv.a(PG:65)
E/HttpOperation( 6519): 	at kff.u(PG:385)
E/HttpOperation( 6519): 	at kfb.a(PG:29)
E/HttpOperation( 6519): 	at kff.l(PG:132)
E/HttpOperation( 6519): 	at dsf.a(PG:807)
E/HttpOperation( 6519): 	at fhk.a(PG:1126)
E/HttpOperation( 6519): 	at fhk.a(PG:908)
E/HttpOperation( 6519): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6519): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6519): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6519): 	at ihi.a(PG:22)
E/HttpOperation( 6519): 	at kft.a(PG:91)
E/HttpOperation( 6519): 	at kfv.a(PG:62)
E/HttpOperation( 6519): 	... 8 more
E/HttpOperation( 6519): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6519): 	at gde.c(Unknown Source)
E/HttpOperation( 6519): 	at gde.b(Unknown Source)
E/HttpOperation( 6519): 	at ihi.a(PG:19)
E/HttpOperation( 6519): 	... 10 more
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6519): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6519): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6519): 	at kfv.a(PG:65)
E/HttpOperation( 6519): 	at kff.u(PG:385)
E/HttpOperation( 6519): 	at kfb.a(PG:29)
E/HttpOperation( 6519): 	at kff.l(PG:132)
E/HttpOperation( 6519): 	at ieo.a(PG:43)
E/HttpOperation( 6519): 	at iep.a(PG:93)
E/HttpOperation( 6519): 	at fhn.a(PG:59)
E/HttpOperation( 6519): 	at lex.a(PG:85)
E/HttpOperation( 6519): 	at lex.b(PG:132)
E/HttpOperation( 6519): 	at fhk.a(PG:1146)
E/HttpOperation( 6519): 	at fhk.a(PG:908)
E/HttpOperation( 6519): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6519): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6519): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6519): 	at ihi.a(PG:22)
E/HttpOperation( 6519): 	at kft.a(PG:91)
E/HttpOperation( 6519): 	at kfv.a(PG:62)
E/HttpOperation( 6519): 	... 12 more
E/HttpOperation( 6519): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6519): 	at gde.c(Unknown Source)
E/HttpOperation( 6519): 	at gde.b(Unknown Source)
E/HttpOperation( 6519): 	at ihi.a(PG:19)
E/HttpOperation( 6519): 	... 14 more
,E/ExperimentLoader( 6519): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6519): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6519): 	at kfv.a(PG:65)
E/ExperimentLoader( 6519): 	at kff.u(PG:385)
E/ExperimentLoader( 6519): 	at kfb.a(PG:29)
E/ExperimentLoader( 6519): 	at kff.l(PG:132)
E/ExperimentLoader( 6519): 	at ieo.a(PG:43)
E/ExperimentLoader( 6519): 	at iep.a(PG:93)
E/ExperimentLoader( 6519): 	at fhn.a(PG:59)
E/ExperimentLoader( 6519): 	at lex.a(PG:85)
E/ExperimentLoader( 6519): 	at lex.b(PG:132)
E/ExperimentLoader( 6519): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6519): 	at fhk.a(PG:908)
E/ExperimentLoader( 6519): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6519): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6519): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6519): 	at ihi.a(PG:22)
E/ExperimentLoader( 6519): 	at kft.a(PG:91)
E/ExperimentLoader( 6519): 	at kfv.a(PG:62)
E/ExperimentLoader( 6519): 	... 12 more
E/ExperimentLoader( 6519): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6519): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6519): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6519): 	at ihi.a(PG:19)
E/ExperimentLoader( 6519): 	... 14 more
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,I/art     ( 1674): Explicit concurrent mark sweep GC freed 38048(2MB) AllocSpace objects, 26(2MB) LOS objects, 39% free, 17MB/29MB, paused 1.619ms total 90.282ms
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1674): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6519): [getaccountstatus] Unexpected exception
E/HttpOperation( 6519): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6519): 	at kfv.a(PG:65)
E/HttpOperation( 6519): 	at kff.u(PG:385)
E/HttpOperation( 6519): 	at kfb.a(PG:29)
E/HttpOperation( 6519): 	at ixd.a(PG:248)
E/HttpOperation( 6519): 	at ixd.b(PG:206)
E/HttpOperation( 6519): 	at ixd.a(PG:175)
E/HttpOperation( 6519): 	at fig.a(PG:78)
E/HttpOperation( 6519): 	at lex.a(PG:85)
E/HttpOperation( 6519): 	at lex.b(PG:132)
E/HttpOperation( 6519): 	at fhk.a(PG:1146)
E/HttpOperation( 6519): 	at fhk.a(PG:908)
E/HttpOperation( 6519): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6519): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6519): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6519): 	at ihi.a(PG:22)
E/HttpOperation( 6519): 	at kft.a(PG:91)
E/HttpOperation( 6519): 	at kfv.a(PG:62)
E/HttpOperation( 6519): 	... 12 more
E/HttpOperation( 6519): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6519): 	at gde.c(Unknown Source)
E/HttpOperation( 6519): 	at gde.b(Unknown Source)
E/HttpOperation( 6519): 	at ihi.a(PG:19)
E/HttpOperation( 6519): 	... 14 more
E/EsSyncAdapterService( 6519): Sync failure
E/EsSyncAdapterService( 6519): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6519): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6519): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6519): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6519): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6519): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6519): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6519): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6519): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6519): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6519): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6519): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6519): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6519): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6519): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6519): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6519): 	... 10 more
E/EsSyncAdapterService( 6519): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6519): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6519): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6519): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6519): 	... 12 more
E/EsSyncAdapterService( 6519): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6519): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6519): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6519): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6519): 	... 14 more
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 149783, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  288): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 15s ago
,E/SMD     (  288): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 330, PST = 379, CUR = 300
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/BatteryService(  890): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD ON
,E/Watchdog(  890): !@Sync 5
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 320, PST = 369, CUR = 300
,I/PowerManagerService(  890): [PWL] Off : 30s ago
,V/AlarmManager(  890): waitForAlarm result :4
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): stay LED for fully charged
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1674): Vacuum at: now=1453134291980 tag=VacuumService
,I/GoogleURLConnFactory( 1674): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,E/Uploader( 1674): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1674): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1674): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1674): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1674): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1674): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1674): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1674): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1674): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1674): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/System.out( 1674): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1674): (HTTPLog)-Static: isShipBuild true
I/System.out( 1674): (HTTPLog)-Thread-201-789318714: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1674): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1674, getuid(): 10012
,I/qtaguid ( 1674): Tagging socket 62 with tag 120100000000{4609,0} uid -1, pid: 1674, getuid(): 10012
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1674): No account for auth token provided
,I/qtaguid ( 1674): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1674, getuid(): 10012
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6546): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6546): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6546): [1] 5.onFinished: Scheduling replication attempt 5.
,W/Uploader( 1674): No account for auth token provided
,I/qtaguid ( 1674): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1674, getuid(): 10012
,W/Uploader( 1674): No account for auth token provided
,I/qtaguid ( 1674): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1674, getuid(): 10012
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Uploader( 1674):  no longer exists, so no auth token.
,I/qtaguid ( 1674): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1674, getuid(): 10012
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON,
,V/AlarmManager(  890): waitForAlarm result :8
,V/AlarmManager(  890): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:m  (  890): SIOP:: AP = 320, PST = 360, CUR = 300
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7403): Starting books sync, d
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1674): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7403): Authentication error
E/BooksAccountManager( 7403): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7403): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7403): null auth token
,I/qtaguid ( 7403): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7403, getuid(): 10082
,I/qtaguid ( 7403): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7403, getuid(): 10082
,I/qtaguid ( 7403): Untagging socket 34
,W/ApiaryClient( 7403): Error response from books API: {
W/ApiaryClient( 7403):  "error": {
W/ApiaryClient( 7403):   "errors": [
W/ApiaryClient( 7403):    {
W/ApiaryClient( 7403):     "domain": "global",
W/ApiaryClient( 7403):     "reason": "required",
W/ApiaryClient( 7403):     "message": "Login Required",
W/ApiaryClient( 7403):     "locationType": "header",
W/ApiaryClient( 7403):     "location": "Authorization"
W/ApiaryClient( 7403):    }
W/ApiaryClient( 7403):   ],
W/ApiaryClient( 7403):   "code": 401,
W/ApiaryClient( 7403):   "message": "Login Required"
W/ApiaryClient( 7403):  }
W/ApiaryClient( 7403): }
,W/ApiaryClient( 7403): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7403): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5881027395208503979&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7403): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
E/SMD     (  288): DCD ON
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7403): Authentication error
E/BooksAccountManager( 7403): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7403): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7403): null auth token
,I/qtaguid ( 7403): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7403, getuid(): 10082
,I/qtaguid ( 7403): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7403, getuid(): 10082
,I/qtaguid ( 7403): Untagging socket 34
,W/ApiaryClient( 7403): Error response from books API: {
W/ApiaryClient( 7403):  "error": {
W/ApiaryClient( 7403):   "errors": [
W/ApiaryClient( 7403):    {
W/ApiaryClient( 7403):     "domain": "global",
W/ApiaryClient( 7403):     "reason": "required",
W/ApiaryClient( 7403):     "message": "Login Required",
W/ApiaryClient( 7403):     "locationType": "header",
W/ApiaryClient( 7403):     "location": "Authorization"
W/ApiaryClient( 7403):    }
W/ApiaryClient( 7403):   ],
W/ApiaryClient( 7403):   "code": 401,
W/ApiaryClient( 7403):   "message": "Login Required"
W/ApiaryClient( 7403):  }
W/ApiaryClient( 7403): }
,W/ApiaryClient( 7403): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7403): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5881027395208503979&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7403): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7403): Authentication error
E/BooksAccountManager( 7403): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7403): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7403): null auth token
,I/qtaguid ( 7403): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7403, getuid(): 10082,
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/qtaguid ( 7403): Untagging socket 34
,W/ApiaryClient( 7403): Error response from books API: {
W/ApiaryClient( 7403):  "error": {
W/ApiaryClient( 7403):   "errors": [
W/ApiaryClient( 7403):    {
W/ApiaryClient( 7403):     "domain": "global",
W/ApiaryClient( 7403):     "reason": "required",
W/ApiaryClient( 7403):     "message": "Login Required",
W/ApiaryClient( 7403):     "locationType": "header",
W/ApiaryClient( 7403):     "location": "Authorization"
W/ApiaryClient( 7403):    }
W/ApiaryClient( 7403):   ],
W/ApiaryClient( 7403):   "code": 401,
W/ApiaryClient( 7403):   "message": "Login Required"
W/ApiaryClient( 7403):  }
W/ApiaryClient( 7403): }
,W/ApiaryClient( 7403): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7403): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5881027395208503979&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7403): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/BooksSync( 7403): Soft error
E/BooksSync( 7403): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7403): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5881027395208503979&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7403): Headers suppressed
E/BooksSync( 7403): 
E/BooksSync( 7403): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7403): Sync error
E/BooksSync( 7403): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7403): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5881027395208503979&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7403): Headers suppressed
E/BooksSync( 7403): 
E/BooksSync( 7403): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7403): Finished books sync
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 155801, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  890): Explicit concurrent mark sweep GC freed 63023(3MB) AllocSpace objects, 32(967KB) LOS objects, 30% free, 36MB/52MB, paused 3.303ms total 151.282ms
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/SMD     (  288): DCD ON
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
E/HttpOperation( 6519): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6519): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6519): 	at kfv.a(PG:65)
E/HttpOperation( 6519): 	at kff.u(PG:385)
E/HttpOperation( 6519): 	at kfb.a(PG:29)
E/HttpOperation( 6519): 	at kff.l(PG:132)
E/HttpOperation( 6519): 	at dsf.a(PG:807)
E/HttpOperation( 6519): 	at fhk.a(PG:1126)
E/HttpOperation( 6519): 	at fhk.a(PG:908)
E/HttpOperation( 6519): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6519): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6519): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6519): 	at ihi.a(PG:22)
E/HttpOperation( 6519): 	at kft.a(PG:91)
E/HttpOperation( 6519): 	at kfv.a(PG:62)
E/HttpOperation( 6519): 	... 8 more
E/HttpOperation( 6519): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6519): 	at gde.c(Unknown Source)
E/HttpOperation( 6519): 	at gde.b(Unknown Source)
E/HttpOperation( 6519): 	at ihi.a(PG:19)
E/HttpOperation( 6519): 	... 10 more
D/PanelView( 1172): There is/are notification(s) 
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6519): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6519): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6519): 	at kfv.a(PG:65)
E/HttpOperation( 6519): 	at kff.u(PG:385)
E/HttpOperation( 6519): 	at kfb.a(PG:29)
E/HttpOperation( 6519): 	at kff.l(PG:132)
E/HttpOperation( 6519): 	at ieo.a(PG:43)
E/HttpOperation( 6519): 	at iep.a(PG:93)
E/HttpOperation( 6519): 	at fhn.a(PG:59)
E/HttpOperation( 6519): 	at lex.a(PG:85)
E/HttpOperation( 6519): 	at lex.b(PG:132)
E/HttpOperation( 6519): 	at fhk.a(PG:1146)
E/HttpOperation( 6519): 	at fhk.a(PG:908)
E/HttpOperation( 6519): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6519): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6519): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6519): 	at ihi.a(PG:22)
E/HttpOperation( 6519): 	at kft.a(PG:91)
E/HttpOperation( 6519): 	at kfv.a(PG:62)
E/HttpOperation( 6519): 	... 12 more
E/HttpOperation( 6519): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6519): 	at gde.c(Unknown Source)
E/HttpOperation( 6519): 	at gde.b(Unknown Source)
E/HttpOperation( 6519): 	at ihi.a(PG:19)
E/HttpOperation( 6519): 	... 14 more
,E/ExperimentLoader( 6519): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6519): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6519): 	at kfv.a(PG:65)
E/ExperimentLoader( 6519): 	at kff.u(PG:385)
E/ExperimentLoader( 6519): 	at kfb.a(PG:29)
E/ExperimentLoader( 6519): 	at kff.l(PG:132)
E/ExperimentLoader( 6519): 	at ieo.a(PG:43)
E/ExperimentLoader( 6519): 	at iep.a(PG:93)
E/ExperimentLoader( 6519): 	at fhn.a(PG:59)
E/ExperimentLoader( 6519): 	at lex.a(PG:85)
E/ExperimentLoader( 6519): 	at lex.b(PG:132)
E/ExperimentLoader( 6519): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6519): 	at fhk.a(PG:908)
E/ExperimentLoader( 6519): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6519): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6519): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6519): 	at ihi.a(PG:22)
E/ExperimentLoader( 6519): 	at kft.a(PG:91)
E/ExperimentLoader( 6519): 	at kfv.a(PG:62)
E/ExperimentLoader( 6519): 	... 12 more
E/ExperimentLoader( 6519): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6519): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6519): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6519): 	at ihi.a(PG:19)
E/ExperimentLoader( 6519): 	... 14 more
D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6519): [getaccountstatus] Unexpected exception
E/HttpOperation( 6519): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6519): 	at kfv.a(PG:65)
E/HttpOperation( 6519): 	at kff.u(PG:385)
E/HttpOperation( 6519): 	at kfb.a(PG:29)
E/HttpOperation( 6519): 	at ixd.a(PG:248)
E/HttpOperation( 6519): 	at ixd.b(PG:206)
E/HttpOperation( 6519): 	at ixd.a(PG:175)
E/HttpOperation( 6519): 	at fig.a(PG:78)
E/HttpOperation( 6519): 	at lex.a(PG:85)
E/HttpOperation( 6519): 	at lex.b(PG:132)
E/HttpOperation( 6519): 	at fhk.a(PG:1146)
E/HttpOperation( 6519): 	at fhk.a(PG:908)
E/HttpOperation( 6519): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6519): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6519): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6519): 	at ihi.a(PG:22)
E/HttpOperation( 6519): 	at kft.a(PG:91)
E/HttpOperation( 6519): 	at kfv.a(PG:62)
E/HttpOperation( 6519): 	... 12 more
E/HttpOperation( 6519): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6519): 	at gde.c(Unknown Source)
E/HttpOperation( 6519): 	at gde.b(Unknown Source)
E/HttpOperation( 6519): 	at ihi.a(PG:19)
E/HttpOperation( 6519): 	... 14 more
,E/EsSyncAdapterService( 6519): Sync failure
E/EsSyncAdapterService( 6519): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6519): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6519): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6519): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6519): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6519): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6519): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6519): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6519): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6519): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6519): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6519): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6519): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6519): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6519): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6519): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6519): 	... 10 more
E/EsSyncAdapterService( 6519): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6519): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6519): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6519): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6519): 	... 12 more
E/EsSyncAdapterService( 6519): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6519): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6519): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6519): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6519): 	... 14 more
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 183121, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:m  (  890): SIOP:: AP = 320, PST = 353, CUR = 300
,I/PowerManagerService(  890): [PWL] Off : 50s ago
,E/SMD     (  288): DCD ON
,V/AlarmManager(  890): waitForAlarm result :4
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): stay LED for fully charged
D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6546): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6546): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6546): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  288): DCD ON
,E/Watchdog(  890): !@Sync 6
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 310, PST = 346, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 310, PST = 334, CUR = 300
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  344): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  344): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 75s ago
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 310, PST = 325, CUR = 300
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,E/Watchdog(  890): !@Sync 7
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 310, PST = 320, CUR = 300
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD ON
,V/AlarmManager(  890): waitForAlarm result :8
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 316, CUR = 300
,V/AlarmManager(  890): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7403): Starting books sync, d
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7403): Authentication error
E/BooksAccountManager( 7403): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7403): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7403): null auth token
,I/qtaguid ( 7403): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7403, getuid(): 10082
,I/qtaguid ( 7403): Untagging socket 34
,W/ApiaryClient( 7403): Error response from books API: {
W/ApiaryClient( 7403):  "error": {
W/ApiaryClient( 7403):   "errors": [
W/ApiaryClient( 7403):    {
W/ApiaryClient( 7403):     "domain": "global",
W/ApiaryClient( 7403):     "reason": "required",
W/ApiaryClient( 7403):     "message": "Login Required",
W/ApiaryClient( 7403):     "locationType": "header",
W/ApiaryClient( 7403):     "location": "Authorization"
W/ApiaryClient( 7403):    }
W/ApiaryClient( 7403):   ],
W/ApiaryClient( 7403):   "code": 401,
W/ApiaryClient( 7403):   "message": "Login Required"
W/ApiaryClient( 7403):  }
W/ApiaryClient( 7403): }
,W/ApiaryClient( 7403): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7403): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7582505208264628421&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7403): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  288): DCD ON
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7403): Authentication error
E/BooksAccountManager( 7403): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7403): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7403): null auth token
,I/qtaguid ( 7403): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7403, getuid(): 10082
,I/qtaguid ( 7403): Untagging socket 34
,W/ApiaryClient( 7403): Error response from books API: {
W/ApiaryClient( 7403):  "error": {
W/ApiaryClient( 7403):   "errors": [
W/ApiaryClient( 7403):    {
W/ApiaryClient( 7403):     "domain": "global",
W/ApiaryClient( 7403):     "reason": "required",
W/ApiaryClient( 7403):     "message": "Login Required",
W/ApiaryClient( 7403):     "locationType": "header",
W/ApiaryClient( 7403):     "location": "Authorization"
W/ApiaryClient( 7403):    }
W/ApiaryClient( 7403):   ],
W/ApiaryClient( 7403):   "code": 401,
W/ApiaryClient( 7403):   "message": "Login Required"
W/ApiaryClient( 7403):  }
W/ApiaryClient( 7403): }
,W/ApiaryClient( 7403): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7403): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7582505208264628421&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7403): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7403): Authentication error
E/BooksAccountManager( 7403): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7403): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7403): null auth token
,I/qtaguid ( 7403): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7403, getuid(): 10082
,I/qtaguid ( 7403): Untagging socket 34,
,W/ApiaryClient( 7403): Error response from books API: {
W/ApiaryClient( 7403):  "error": {
W/ApiaryClient( 7403):   "errors": [
W/ApiaryClient( 7403):    {
W/ApiaryClient( 7403):     "domain": "global",
W/ApiaryClient( 7403):     "reason": "required",
W/ApiaryClient( 7403):     "message": "Login Required",
W/ApiaryClient( 7403):     "locationType": "header",
W/ApiaryClient( 7403):     "location": "Authorization"
W/ApiaryClient( 7403):    }
W/ApiaryClient( 7403):   ],
W/ApiaryClient( 7403):   "code": 401,
W/ApiaryClient( 7403):   "message": "Login Required"
W/ApiaryClient( 7403):  }
W/ApiaryClient( 7403): }
,W/ApiaryClient( 7403): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7403): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7582505208264628421&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7403): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7403): Soft error
E/BooksSync( 7403): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7403): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7582505208264628421&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7403): Headers suppressed
E/BooksSync( 7403): 
E/BooksSync( 7403): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7403): Sync error
E/BooksSync( 7403): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7403): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7582505208264628421&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7403): Headers suppressed
E/BooksSync( 7403): 
E/BooksSync( 7403): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7403): Finished books sync
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 214241, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  890): mCursor = null
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 105s ago
,E/SMD     (  288): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 313, CUR = 300
,E/SMD     (  288): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD ON
,E/Watchdog(  890): !@Sync 8
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 310, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 308, CUR = 300
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1674): Explicit concurrent mark sweep GC freed 48223(2MB) AllocSpace objects, 48(3MB) LOS objects, 40% free, 18MB/30MB, paused 895us total 94.672ms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1674): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6519): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6519): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6519): 	at kfv.a(PG:65)
E/HttpOperation( 6519): 	at kff.u(PG:385)
E/HttpOperation( 6519): 	at kfb.a(PG:29)
E/HttpOperation( 6519): 	at kff.l(PG:132)
E/HttpOperation( 6519): 	at dsf.a(PG:807)
E/HttpOperation( 6519): 	at fhk.a(PG:1126)
E/HttpOperation( 6519): 	at fhk.a(PG:908)
E/HttpOperation( 6519): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6519): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6519): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6519): 	at ihi.a(PG:22)
E/HttpOperation( 6519): 	at kft.a(PG:91)
E/HttpOperation( 6519): 	at kfv.a(PG:62)
E/HttpOperation( 6519): 	... 8 more
E/HttpOperation( 6519): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6519): 	at gde.c(Unknown Source)
E/HttpOperation( 6519): 	at gde.b(Unknown Source)
E/HttpOperation( 6519): 	at ihi.a(PG:19)
E/HttpOperation( 6519): 	... 10 more
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6519): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6519): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6519): 	at kfv.a(PG:65)
E/HttpOperation( 6519): 	at kff.u(PG:385)
E/HttpOperation( 6519): 	at kfb.a(PG:29)
E/HttpOperation( 6519): 	at kff.l(PG:132)
E/HttpOperation( 6519): 	at ieo.a(PG:43)
E/HttpOperation( 6519): 	at iep.a(PG:93)
E/HttpOperation( 6519): 	at fhn.a(PG:59)
E/HttpOperation( 6519): 	at lex.a(PG:85)
E/HttpOperation( 6519): 	at lex.b(PG:132)
E/HttpOperation( 6519): 	at fhk.a(PG:1146)
E/HttpOperation( 6519): 	at fhk.a(PG:908)
E/HttpOperation( 6519): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6519): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6519): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6519): 	at ihi.a(PG:22)
E/HttpOperation( 6519): 	at kft.a(PG:91)
E/HttpOperation( 6519): 	at kfv.a(PG:62)
E/HttpOperation( 6519): 	... 12 more
E/HttpOperation( 6519): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6519): 	at gde.c(Unknown Source)
E/HttpOperation( 6519): 	at gde.b(Unknown Source)
E/HttpOperation( 6519): 	at ihi.a(PG:19)
E/HttpOperation( 6519): 	... 14 more
,E/ExperimentLoader( 6519): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6519): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6519): 	at kfv.a(PG:65)
E/ExperimentLoader( 6519): 	at kff.u(PG:385)
E/ExperimentLoader( 6519): 	at kfb.a(PG:29)
E/ExperimentLoader( 6519): 	at kff.l(PG:132)
E/ExperimentLoader( 6519): 	at ieo.a(PG:43)
E/ExperimentLoader( 6519): 	at iep.a(PG:93)
E/ExperimentLoader( 6519): 	at fhn.a(PG:59)
E/ExperimentLoader( 6519): 	at lex.a(PG:85)
E/ExperimentLoader( 6519): 	at lex.b(PG:132)
E/ExperimentLoader( 6519): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6519): 	at fhk.a(PG:908)
E/ExperimentLoader( 6519): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6519): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6519): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6519): 	at ihi.a(PG:22)
E/ExperimentLoader( 6519): 	at kft.a(PG:91)
E/ExperimentLoader( 6519): 	at kfv.a(PG:62)
E/ExperimentLoader( 6519): 	... 12 more
E/ExperimentLoader( 6519): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6519): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6519): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6519): 	at ihi.a(PG:19)
E/ExperimentLoader( 6519): 	... 14 more
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6519): [getaccountstatus] Unexpected exception
E/HttpOperation( 6519): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6519): 	at kfv.a(PG:65)
E/HttpOperation( 6519): 	at kff.u(PG:385)
E/HttpOperation( 6519): 	at kfb.a(PG:29)
E/HttpOperation( 6519): 	at ixd.a(PG:248)
E/HttpOperation( 6519): 	at ixd.b(PG:206)
E/HttpOperation( 6519): 	at ixd.a(PG:175)
E/HttpOperation( 6519): 	at fig.a(PG:78)
E/HttpOperation( 6519): 	at lex.a(PG:85)
E/HttpOperation( 6519): 	at lex.b(PG:132)
E/HttpOperation( 6519): 	at fhk.a(PG:1146)
E/HttpOperation( 6519): 	at fhk.a(PG:908)
E/HttpOperation( 6519): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6519): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6519): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6519): 	at ihi.a(PG:22)
E/HttpOperation( 6519): 	at kft.a(PG:91)
E/HttpOperation( 6519): 	at kfv.a(PG:62)
E/HttpOperation( 6519): 	... 12 more
E/HttpOperation( 6519): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6519): 	at gde.c(Unknown Source)
E/HttpOperation( 6519): 	at gde.b(Unknown Source)
E/HttpOperation( 6519): 	at ihi.a(PG:19)
E/HttpOperation( 6519): 	... 14 more
E/EsSyncAdapterService( 6519): Sync failure
E/EsSyncAdapterService( 6519): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6519): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6519): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6519): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6519): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6519): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6519): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6519): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6519): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6519): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6519): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6519): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6519): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6519): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6519): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6519): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6519): 	... 10 more
E/EsSyncAdapterService( 6519): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6519): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6519): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6519): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6519): 	... 12 more
E/EsSyncAdapterService( 6519): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6519): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6519): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6519): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6519): 	... 14 more
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 249911, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2853): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/art     (  890): Explicit concurrent mark sweep GC freed 43680(2MB) AllocSpace objects, 40(1225KB) LOS objects, 30% free, 36MB/52MB, paused 1.782ms total 137.003ms
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  288): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 140s ago
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 306, CUR = 300
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  890): !@Sync 9
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 304, CUR = 300
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD ON
,V/AlarmManager(  890): waitForAlarm result :8
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 303, CUR = 300
,V/AlarmManager(  890): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  890): stay LED for fully charged
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 302, CUR = 300
,E/SMD     (  288): DCD ON
,D/TimaService(  890): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  890): TimaServiceHandler.handleMessage what =1
,D/TimaService(  890): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  890): initializing...
,I/TLC_TIMA_PKM_initialize(  890): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  890): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  890): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  890): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  890): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  890): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  890): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  890): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  890): App is not loaded in QSEE
,D/QSEECOMAPI: (  890): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  890): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  890): Trustlet response is completed
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,E/Watchdog(  890): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  890): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  890): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  890): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  890): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 180s ago
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 301, CUR = 300
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,I/Atfwd_Sendcmd(  344): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  344): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 300, CUR = 300
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7403): Starting books sync, d
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1674): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7403): Authentication error
E/BooksAccountManager( 7403): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7403): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7403): null auth token
,I/qtaguid ( 7403): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7403, getuid(): 10082
,I/qtaguid ( 7403): Untagging socket 34
,W/ApiaryClient( 7403): Error response from books API: {
W/ApiaryClient( 7403):  "error": {
W/ApiaryClient( 7403):   "errors": [
W/ApiaryClient( 7403):    {
W/ApiaryClient( 7403):     "domain": "global",
W/ApiaryClient( 7403):     "reason": "required",
W/ApiaryClient( 7403):     "message": "Login Required",
W/ApiaryClient( 7403):     "locationType": "header",
W/ApiaryClient( 7403):     "location": "Authorization"
W/ApiaryClient( 7403):    }
W/ApiaryClient( 7403):   ],
W/ApiaryClient( 7403):   "code": 401,
W/ApiaryClient( 7403):   "message": "Login Required"
W/ApiaryClient( 7403):  }
W/ApiaryClient( 7403): }
,W/ApiaryClient( 7403): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7403): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6128042382434411227&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7403): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7403): Authentication error
E/BooksAccountManager( 7403): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7403): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7403): null auth token
,I/qtaguid ( 7403): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7403, getuid(): 10082
,I/qtaguid ( 7403): Untagging socket 34
,W/ApiaryClient( 7403): Error response from books API: {
W/ApiaryClient( 7403):  "error": {
W/ApiaryClient( 7403):   "errors": [
W/ApiaryClient( 7403):    {
W/ApiaryClient( 7403):     "domain": "global",
W/ApiaryClient( 7403):     "reason": "required",
W/ApiaryClient( 7403):     "message": "Login Required",
W/ApiaryClient( 7403):     "locationType": "header",
W/ApiaryClient( 7403):     "location": "Authorization"
W/ApiaryClient( 7403):    }
W/ApiaryClient( 7403):   ],
W/ApiaryClient( 7403):   "code": 401,
W/ApiaryClient( 7403):   "message": "Login Required"
W/ApiaryClient( 7403):  }
W/ApiaryClient( 7403): }
,W/ApiaryClient( 7403): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7403): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6128042382434411227&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7403): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  890): waitForAlarm result :4
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Zygote  ( 8601): MountEmulatedStorage()
,E/Zygote  ( 8601): v2
I/libpersona( 8601): KNOX_SDCARD checking this for 10081
,I/libpersona( 8601): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8601 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SELinux ( 8601): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8601): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8601): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7403): Authentication error
E/BooksAccountManager( 7403): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7403): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7403): null auth token
,I/qtaguid ( 7403): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7403, getuid(): 10082
,D/TimaKeyStoreProvider( 8601): TimaSignature is unavailable
,D/ActivityThread( 8601): Added TimaKeyStore provider
,D/ResourcesManager( 8601): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/qtaguid ( 7403): Untagging socket 34
,W/ApiaryClient( 7403): Error response from books API: {
W/ApiaryClient( 7403):  "error": {
W/ApiaryClient( 7403):   "errors": [
W/ApiaryClient( 7403):    {
W/ApiaryClient( 7403):     "domain": "global",
W/ApiaryClient( 7403):     "reason": "required",
W/ApiaryClient( 7403):     "message": "Login Required",
W/ApiaryClient( 7403):     "locationType": "header",
W/ApiaryClient( 7403):     "location": "Authorization"
W/ApiaryClient( 7403):    }
W/ApiaryClient( 7403):   ],
W/ApiaryClient( 7403):   "code": 401,
W/ApiaryClient( 7403):   "message": "Login Required"
W/ApiaryClient( 7403):  }
W/ApiaryClient( 7403): }
,W/ApiaryClient( 7403): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7403): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6128042382434411227&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7403): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7403): Soft error
E/BooksSync( 7403): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7403): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6128042382434411227&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7403): Headers suppressed
E/BooksSync( 7403): 
E/BooksSync( 7403): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7403): Sync error
E/BooksSync( 7403): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7403): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6128042382434411227&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7403): Headers suppressed
E/BooksSync( 7403): 
E/BooksSync( 7403): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7403): Finished books sync
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,I/ActivityManager(  890): Killing 5666:com.android.mms/u0a50 (adj 15): bgCount ##41
,D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 304584, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2853): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 2853): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  890): mCursor = null
,D/CountryDetector(  890): No listener is left
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  890): failed to open /acct/uid_10050/pid_5666/cgroup.procs: No such file or directory
,E/SMD     (  288): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  288): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/jxcore-log( 7520): --= Surplus to requirements =--
I/jxcore-log( 7520): 
,I/jxcore-log( 7520): ****TEST TOOK:  ms ****
I/jxcore-log( 7520): 
I/jxcore-log( 7520): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7520): 
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,D/AndroidRuntime( 8665): 
D/AndroidRuntime( 8665): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8665): CheckJNI is OFF
,D/AndroidRuntime( 8665): setted country_code = Germany
D/AndroidRuntime( 8665): setted countryiso_code = DE
,D/AndroidRuntime( 8665): setted sales_code = DBT
D/AndroidRuntime( 8665): readGMSProperty: start
,D/AndroidRuntime( 8665): readGMSProperty: already setted!!
D/AndroidRuntime( 8665): readGMSProperty: end
D/AndroidRuntime( 8665): addProductProperty: start
,E/AffinityControl( 8665): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8665): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  890): START PACKAGE DELETE: observer{341034407}
D/PackageManager(  890): pkg{<packageName>}
D/PackageManager(  890): user{0}
D/PackageManager(  890): caller{2000}
D/PackageManager(  890): flags{3}
D/PersonaManagerService(  890): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  890): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  890): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  890): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  890): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  890): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  890): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  890): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  890): getApplicationUninstallationEnabled
D/ApplicationPolicy(  890): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  890): !@killApplicatoin: 10200, uninstall pkg
,I/ActivityManager(  890): Force stopping com.test.thalitest appid=10200 user=-1: uninstall pkg
,I/ActivityManager(  890): Killing 7520:com.test.thalitest/u0a200 (adj 0): stop com.test.thalitest
,I/ActivityManager(  890):   Force finishing activity ActivityRecord{27c1a391 u0 com.test.thalitest/.MainActivity t17}
,D/FocusedStackFrame(  890): Set to : 0
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/SurfaceFlinger(  248): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
,I/SurfaceFlinger(  248): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiService(  890): Client connection lost with reason: 4
,I/ActivityManager(  890): Force stopping com.test.thalitest appid=10200 user=0: pkg removed
,I/art     ( 1554): Explicit concurrent mark sweep GC freed 20104(1290KB) AllocSpace objects, 1(39KB) LOS objects, 39% free, 16MB/27MB, paused 631us total 32.390ms
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,E/SamsungIME( 1859): mOCRHelper is null
,I/InputReader(  890): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 2250): Ignoring removeGeofence because network location is disabled.
,I/art     ( 4664): Explicit concurrent mark sweep GC freed 32376(1785KB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 14MB/24MB, paused 400us total 56.167ms
,I/KLMS-2.4.503: ( 7736): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7736): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1453134463481
,I/KLMS-2.4.503: ( 7736): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.503: ( 7736): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 1
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/art     (  890): Explicit concurrent mark sweep GC freed 32016(2MB) AllocSpace objects, 29(659KB) LOS objects, 30% free, 36MB/52MB, paused 1.488ms total 145.147ms
,D/ResourcesManager(  890): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/art     (  890): WaitForGcToComplete blocked for 135.049ms for cause Explicit
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/RegisteredServicesCache( 1464): empty dynamic service
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,E/Zygote  ( 8694): MountEmulatedStorage()
I/libpersona( 8694): KNOX_SDCARD checking this for 10104
E/Zygote  ( 8694): v2
I/libpersona( 8694): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8694 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,I/SELinux ( 8694): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,I/SELinux ( 8694): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8694): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/EnterpriseDeviceManagerService(  890): Package has changed for user 0
D/EnterpriseDeviceManagerService(  890): Admin package name: com.google.android.gms
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/TimaKeyStoreProvider( 8694): TimaSignature is unavailable
,D/ActivityThread( 8694): Added TimaKeyStore provider
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ResourcesManager( 8694): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/SurfaceWidgetView( 1484): destroyHardwareResources():535910263
,V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  890): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/Launcher( 1484): onRestart, Launcher: 829809600
,D/Launcher( 1484): onStart, Launcher: 829809600
D/Launcher.HomeView( 1484): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2137): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2137): [237392/6] SurfaceWidget drawing first frame
,D/RCPManagerService(  890): PackageReceiver onReceive()
,I/HarmonyEASService(  890): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  890): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/elm:14451( 8694): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 8694): ELMEngine.ELMEngine( context ).
,D/elm:14451( 8694): MDMBridge.setEnterpriseBridge()
D/BackupManagerService(  890): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  890): Receieved: android.intent.action.PACKAGE_REMOVED
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
V/EnterpriseBillingPolicy(  890): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  890): uID is 10200
,V/EnterpriseBillingPolicy(  890): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  890): getProfileForApplication - enter
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,V/EnterpriseBillingPolicyStorage(  890): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  890): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  890): packageModificationReceiver - onreceive - might be a vpn vendor package 
,V/EnterpriseBillingPolicyStorage(  890): getBillingProfileForVpnEngine - start - com.test.thalitest
I/SurfaceFlinger(  248): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
V/EnterpriseBillingPolicyStorage(  890): getBillingProfileForVpnEngine - end - null
,D/StatusBarManagerService(  890): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/elm:14451( 8694): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/StatusBarManagerService(  890): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/elm:14451( 8694): ElmAgentService : onCreate()
,D/elm:14451( 8694): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14451( 8694): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8694): MDMBridge.getInstance()
D/elm:14451( 8694): MDMBridge.getAllLicenseInfoFromSDK()
,D/TaskPersister(  890): removeObsoleteFile: deleting file=17_task.xml
D/TaskPersister(  890): removeObsoleteFile: deleting file=17_task_thumbnail.png
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:14451( 8694): MDMBridge.getAllLicenseInfoFromSDK()
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 8142): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8142): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 8142): onReceive() : package name is not s health. Return !!!
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/InputMethodManagerService(  890): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  890): Got RemoteException sending setActive(false) notification to pid 7520 uid 10200
,D/elm:14451( 8694): ElmAgentService : onDestroy().
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/PCWCLIENTTRACE_PushUtil( 7656): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7656): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7656): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7656): [onReceive] - android.intent.action.PACKAGE_REMOVED
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,I/art     (  890): Explicit concurrent mark sweep GC freed 10331(505KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 4.758ms total 229.411ms
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/Zygote  ( 8717): MountEmulatedStorage()
I/libpersona( 8717): KNOX_SDCARD checking this for 10038
E/Zygote  ( 8717): v2
I/libpersona( 8717): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8717 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Timeline(  890): Timeline: Activity_windows_visible id: ActivityRecord{551bcfc u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t15} time:343310
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/SELinux ( 8717): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SELinux ( 8717): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/ActivityManager(  890): Killing 7318:com.sec.android.widgetapp.digitalclock/u0a94 (adj 15): bgCount ##41
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/SELinux ( 8717): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/PackageManager(  890): delete codoeFile: 
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PackageManager(  890): result of delete: 1{341034407}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/AndroidRuntime( 8665): Shutting down VM
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/TimaKeyStoreProvider( 8717): TimaSignature is unavailable
,D/ActivityThread( 8717): Added TimaKeyStore provider
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 8717): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  890): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  890): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  890): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,W/libprocessgroup(  890): failed to open /acct/uid_10094/pid_7318/cgroup.procs: No such file or directory
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SPPClientService( 8717): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 8717): [PushClientApplication] Push log off : This is Ship build version
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/SPPClientService( 8717): PushLog.txt file is not deleted.
D/SPPClientService( 8717): PushLog.txt file is not deleted.
D/SPPClientService( 8717): ============PushLog. stop!
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 8091): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8091): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8091): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8091): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,E/Zygote  ( 8733): MountEmulatedStorage()
E/Zygote  ( 8733): v2
I/libpersona( 8733): KNOX_SDCARD checking this for 10042
I/libpersona( 8733): KNOX_SDCARD not a persona
,W/ResourcesManager( 8091): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/ActivityManager(  890): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8733 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
W/ResourcesManager( 8091): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8091): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/ActivityManager(  890): Killing 7342:com.sec.android.widgetapp.dualclockdigital/u0a103 (adj 15): bgCount ##41
D/UsbSettingsManager(  890): clearDefaults: com.test.thalitest
I/CrashAnrDetector(  890): onPackageRemoved : com.test.thalitest
I/SELinux ( 8733): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ResourcesManager( 8091): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
I/SELinux ( 8733): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8733): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 8091): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ResourcesManager( 8091): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/libprocessgroup(  890): failed to open /acct/uid_10103/pid_7342/cgroup.procs: No such file or directory
D/ResourcesManager( 8091): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
D/TimaKeyStoreProvider( 8733): TimaSignature is unavailable
D/ActivityThread( 8733): Added TimaKeyStore provider
W/ResourcesManager( 8091): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 8091): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
W/ResourcesManager( 8091): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ResourcesManager( 8733): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
W/ResourcesManager( 8733): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8733): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ResourcesManager( 8091): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
W/ResourcesManager( 8091): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager( 8091): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/ResourcesManager( 8091): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4311, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  890): stay LED for fully charged
D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
D/ResourcesManager( 8091): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
W/ResourcesManager( 8091): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
W/ResourcesManager( 8091): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/HeadsetStateMachine( 3247): Disconnected process message: 10
W/ResourcesManager( 8091): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ResourcesManager( 8091): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/ResourcesManager( 8091): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager( 8091): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
W/ResourcesManager( 8091): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 8091): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
W/ResourcesManager( 8091): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/ResourcesManager( 8091): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 8091): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/ResourcesManager( 8091): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8091): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 8091): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SMD     (  288): DCD ON
,W/System.err( 8733): java.lang.NoSuchMethodException: getImeiInCDMAGSMPhone []
,W/System.err( 8733): 	at java.lang.Class.getMethod(Class.java:665)
W/System.err( 8733): 	at com.sec.pcw.util.c.c(SourceFile:295)
W/System.err( 8733): 	at com.sec.pcw.service.account.a.b(SourceFile:250)
W/System.err( 8733): 	at com.sec.pcw.service.account.a.a(SourceFile:52)
W/System.err( 8733): 	at com.mfluent.asp.datamodel.Device.r(SourceFile:359)
W/System.err( 8733): 	at com.mfluent.asp.datamodel.Device.<init>(SourceFile:248)
W/System.err( 8733): 	at com.mfluent.asp.datamodel.t.a(SourceFile:136)
W/System.err( 8733): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:484)
W/System.err( 8733): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
W/System.err( 8733): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
W/System.err( 8733): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
W/System.err( 8733): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
W/System.err( 8733): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
W/System.err( 8733): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 8733): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 8733): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8733): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 8733): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 8733): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 8733): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 8733): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 8733): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/SL_DEBUG( 8733): isLoggable:: isProductShip = 1
,I/SL_DEBUG( 8733): isLoggable:: SL_DEBUG_EXIST = false
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Vold    (  247): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8733): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,E/Vold    (  247): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8733): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,V/Transcoder( 8733): Transcoder(0xaf0058d0)::constructor
V/Transcoder( 8733): addObitRecipient
,V/TMI-JNI ( 8733): Mobile Transcoder JNI version 1.6.0/20131120/4.4
,I/SA      ( 7814): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
I/SA      ( 7814): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10200 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,F/libc    ( 8733): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa19f5a00 in tid 8733 (sdk.samsunglink)
,F/libc    ( 1804): Fatal signal 7 (SIGBUS), code 2, fault addr 0x78145344 in tid 1804 (d.process.acore)
,F/libc    ( 1804): Failed while talking to debuggerd: Broken pipe
F/libc    ( 8733): Failed while talking to debuggerd: Broken pipe
,E/audit_log( 2173): File locking failed. error= Bad file number
E/audit_log( 2173): File locking failed. error= Bad file number
E/audit_log( 2173): File locking failed. error= Bad file number
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/SharedPreferencesImpl( 5990): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml
,E/Zygote  ( 8762): MountEmulatedStorage()
,E/Zygote  ( 8762): v2
I/libpersona( 8762): KNOX_SDCARD checking this for 10050
I/libpersona( 8762): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageReceiver: pid=8762 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,E/Watchdog(  890): !@Sync 11
,I/EventHub(  890): Removing device '/dev/input/event4' due to inotify event
,I/SELinux ( 8762): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,E/SELinux ( 8762): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/Zygote  (  324): Process 8733 exited due to signal (7)
,I/art     (  324): Explicit concurrent mark sweep GC freed 8705(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 390us total 24.103ms
,I/ActivityManager(  890): Process com.samsung.android.sdk.samsunglink (pid 8733)(adj 0) has died(236,480)
,F/libc    (  890): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa0d99810 in tid 1342 (Binder_6)
,F/libc    (  890): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2173): File locking failed. error= Bad file number
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 302us total 10.205ms
,I/Zygote  (  324): Process 1804 exited due to signal (7)
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 247us total 9.247ms
,E/installd(  297): eof
E/installd(  297): failed to read size
I/installd(  297): closing connection
,I/ServiceManager(  246): service 'wallpaper' died
I/ServiceManager(  246): service 'audio' died
I/ServiceManager(  246): service 'DockObserver' died
I/ServiceManager(  246): service 'usb' died
I/ServiceManager(  246): service 'serial' died
I/ServiceManager(  246): service 'uimode' died
I/ServiceManager(  246): service 'jobscheduler' died
I/ServiceManager(  246): service 'enterprise_policy' died
I/ServiceManager(  246): service 'statusbar' died
I/ServiceManager(  246): service 'clipboard' died
I/ServiceManager(  246): service 'clipboardEx' died
I/ServiceManager(  246): service 'network_management' died
I/ServiceManager(  246): service 'ABTPersistenceService' died
I/ServiceManager(  246): service 'textservices' died
I/ServiceManager(  246): service 'network_score' died
I/ServiceManager(  246): service 'netstats' died
I/ServiceManager(  246): service 'netpolicy' died
I/ServiceManager(  246): service 'wifi' died
I/ServiceManager(  246): service 'msapwifi' died
I/ServiceManager(  246): service 'wifiscanner' died
I/ServiceManager(  246): service 'rttmanager' died
I/ServiceManager(  246): service 'connectivity' died
I/ServiceManager(  246): service 'sb_service' died
I/ServiceManager(  246): service 'clinfo' died
I/ServiceManager(  246): service 'servicediscovery' died
I/ServiceManager(  246): service 'updatelock' died
I/ServiceManager(  246): service 'notification' died
I/ServiceManager(  246): service 'devicestoragemonitor' died
I/ServiceManager(  246): service 'location' died
I/ServiceManager(  246): service 'country_detector' died
I/ServiceManager(  246): service 'sec_location' died
I/ServiceManager(  246): service 'search' died
I/ServiceManager(  246): service 'dropbox' died
I/ServiceManager(  246): service 'wifip2p' died
W/Sensors ( 5990): sensorservice died [0xaf17b540]
W/Sensors ( 1307): sensorservice died [0x9d4212c0]
I/ServiceManager(  246): service 'backup' died
I/ServiceManager(  246): service 'appwidget' died
I/ServiceManager(  246): service 'voiceinteraction' died
I/ServiceManager(  246): service 'SecExternalDisplayService' died
I/ServiceManager(  246): service 'diskstats' died
I/ServiceManager(  246): service 'spengestureservice' died
I/ServiceManager(  246): service 'quickconnect' died
I/ServiceManager(  246): service 'samplingprofiler' died
I/ServiceManager(  246): service 'commontime_management' died
I/ServiceManager(  246): service 'dreams' died
I/ServiceManager(  246): service 'print' died
I/ServiceManager(  246): service 'restrictions' died
I/ServiceManager(  246): service 'media_session' died
I/ServiceManager(  246): service 'media_router' died
I/ServiceManager(  246): service 'trust' died
I/ServiceManager(  246): service 'fingerprint' died
I/ServiceManager(  246): service 'launcherapps' died
I/ServiceManager(  246): service 'voip' died
I/ServiceManager(  246): service 'media_projection' died
I/ServiceManager(  246): service 'imms' died
I/ServiceManager(  246): service 'sec_analytics' died
I/ServiceManager(  246): service 'context_aware' died
I/ServiceManager(  246): service 'scontext' died
I/ServiceManager(  246): service 'barbeam' died
I/ServiceManager(  246): service 'multiwindow_facade' died
I/ServiceManager(  246): service 'window' died
I/ServiceManager(  246): service 'input' died
I/ServiceManager(  246): service 'tactileassist' died
I/ServiceManager(  246): service 'bluetooth_manager' died
I/ServiceManager(  246): service 'bluetooth_secure_mode_manager' died
I/ServiceManager(  246): service 'rcp' died
I/ServiceManager(  246): service 'input_method' died
I/ServiceManager(  246): service 'accessibility' died
I/ServiceManager(  246): service 'motion_recognition' died
I/ServiceManager(  246): service 'cover' died
I/ServiceManager(  246): service 'mount' died
I/ServiceManager(  246): service 'lock_settings' died
I/ServiceManager(  246): service 'device_policy' died
I/ServiceManager(  246): service 'harmony_eas_service' died
W/Sensors ( 1474): sensorservice died [0xaf17d380]
I/ServiceManager(  246): service 'sdp' died
I/ServiceMan,ager(  246): service 'log_manager_service' died
I/ServiceManager(  246): service 'batterystats' died
I/ServiceManager(  246): service 'appops' died
I/ServiceManager(  246): service 'power' died
I/ServiceManager(  246): service 'display' died
I/ServiceManager(  246): service 'SEAMService' died
I/ServiceManager(  246): service 'persona' died
I/ServiceManager(  246): service 'account' died
I/ServiceManager(  246): service 'content' died
I/ServiceManager(  246): service 'DirEncryptService' died
I/ServiceManager(  246): service 'ReactiveService' died
I/ServiceManager(  246): service 'battery' died
I/ServiceManager(  246): service 'usagestats' died
I/ServiceManager(  246): service 'webviewupdate' died
I/ServiceManager(  246): service 'scheduling_policy' died
I/ServiceManager(  246): service 'telephony.registry' died
I/ServiceManager(  246): service 'entropy' died
I/ServiceManager(  246): service 'persona_policy' died
I/ServiceManager(  246): service 'sedenial' died
I/ServiceManager(  246): service 'vibrator' died
I/ServiceManager(  246): service 'tw_toolbox' died
I/ServiceManager(  246): service 'tima' died
I/ServiceManager(  246): service 'cepproxyks' died
I/ServiceManager(  246): service 'enterprise_license_policy' died
I/ServiceManager(  246): service 'CustomFrequencyManagerService' died
I/ServiceManager(  246): service 'samsung.smartfaceservice' died
I/ServiceManager(  246): service 'consumer_ir' died
I/ServiceManager(  246): service 'alarm' died
I/ServiceManager(  246): service 'application_policy' died
I/ServiceManager(  246): service 'wifi_policy' died
I/ServiceManager(  246): service 'phone_restriction_policy' died
I/ServiceManager(  246): service 'remoteinjection' died
I/ServiceManager(  246): service 'mum_container_policy' died
I/ServiceManager(  246): service 'enterprise_billing_policy' died
I/ServiceManager(  246): service 'knox_timakeystore_policy' died
I/ServiceManager(  246): service 'package' died
I/ServiceManager(  246): service 'cpuinfo' died
I/ServiceManager(  246): service 'activity' died
I/ServiceManager(  246): service 'hardware' died
I/ServiceManager(  246): service 'procstats' died
I/ServiceManager(  246): service 'permission' died
I/ServiceManager(  246): service 'edmnativehelper' died
I/ServiceManager(  246): service 'user' died
I/ServiceManager(  246): service 'gfxinfo' died
I/ServiceManager(  246): service 'dbinfo' died
I/ServiceManager(  246): service 'meminfo' died
I/ServiceManager(  246): service 'sensorservice' died
I/ServiceManager(  246): service 'mdm.remotedesktop' died
D/SurfaceFlinger(  248): Set power mode=2, type=0 flinger=0xb6962000
D/qdhwcomposer(  248): hwc_blank: Unblanking display: 0
W/Sensors ( 2250): sensorservice died [0xaf177040]
I/SurfaceFlinger(  248): restart the boot-animation @ binderDied
W/Sensors ( 1172): sensorservice died [0xaf17f080]
I/SurfaceFlinger(  248): id=2 Removed FocusedStackFrame (4/8)
I/SurfaceFlinger(  248): id=3 Removed DimLayer (0/7)
I/SurfaceFlinger(  248): id=4 Removed DimLayer (0/6)
I/SurfaceFlinger(  248): id=5 Removed DimLayer (0/5)
I/SurfaceFlinger(  248): id=6 Removed DimLayer (2/4)
I/SurfaceFlinger(  248): id=2 Removed FocusedStackFrame (-2/4)
I/SurfaceFlinger(  248): id=3 Removed DimLayer (-2/4)
I/SurfaceFlinger(  248): id=4 Removed DimLayer (-2/4)
I/SurfaceFlinger(  248): id=5 Removed DimLayer (-2/4)
I/SurfaceFlinger(  248): id=6 Removed DimLayer (-2/4)
I/SurfaceFlinger(  248): id=18 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (1/3)
I/SurfaceFlinger(  248): id=17 Removed ColorFade (2/2)
I/SurfaceFlinger(  248): id=7 Removed com.android.systemui.ImageWallpaper (0/1)
I/SurfaceFlinger(  248): id=7 Removed com.android.systemui.ImageWallpaper (-2/1)
I/SurfaceFlinger(  248): id=18 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/1)
I/SurfaceFlinger(  248): id=9 Removed StatusBar (0/0)
I/SurfaceFlinger(  248): id=9 Removed StatusBar (-2/0)
I/SurfaceFlinger(  248): id=17 Removed ColorFade (-2/0)
E/WifiManager( 2250): Channel connection lost
E/WifiManager( 1172): Channel connection lost
E/WifiManager( 1554): Channel connection lost
E/WifiManager( 1474): Channel connection lost
E/WifiManager( 1307): Channel connection lost
W/Sensors ( 2282): sensorservice died [0xaf1bdbc0]
F/libc    ( 8762): Fatal signal 7 (SIGBUS), code 2, fault addr 0x759a5bd8 in tid 8762 (com.android.mms)
F/libc    ( 8762): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2173): File locking failed. error= Bad file number
W/Sensors ( 1484): sensorservice died [0xaf1633c0]
W/Sensors ( 1453): sensorservice died [0xaf1bdbc0]
W/AudioFlinger(  293): power manager service died !!!
F/libc    ( 4664): Fatal signal 7 (SIGBUS), code 2, fault addr 0x73f67950 in tid 4692 (AppProvider)
F/libc    ( 4664): Unable to open connection to debuggerd: Connection refused
W/AudioFlinger(  293): power manager service died !!!
E/audit_log( 2173): File locking failed. error= Bad file number
,I/Zygote  (  324): Process 8762 exited due to signal (7)
I/Zygote  (  324): Process 4664 exited due to signal (7)
,I/qdhwcomposer(  248): handle_blank_event: dpy:0 panel power state: 1
,E/qdexternal(  248): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  248): hwc_blank: Done unblanking display: 0
,I/SurfaceFlinger(  248): Disp[0] Orientation 0=>0
,E/qdoverlay(  248): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  248): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  248): hwc_set_primary: display commit fail for 0 dpy!
,I/lowmemorykiller(  245): ActivityManager disconnected
I/lowmemorykiller(  245): Closing Activity Manager data connection
,I/qdhwcomposer(  248): handle_blank_event: dpy:0 panel power state: 0

```
