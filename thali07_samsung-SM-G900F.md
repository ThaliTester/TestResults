#### Test 564496607226f84_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
,E/SMD     (  289): DCD ON
--------- beginning of system
V/AlarmManager(  893): waitForAlarm result :4
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7444): MountEmulatedStorage()
E/Zygote  ( 7444): v2
I/libpersona( 7444): KNOX_SDCARD checking this for 10179
I/libpersona( 7444): KNOX_SDCARD not a persona
I/ActivityManager(  893): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler: pid=7444 uid=10179 gids={50179, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
I/SELinux ( 7444): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7444): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7444): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7444): TimaSignature is unavailable
D/ActivityThread( 7444): Added TimaKeyStore provider
D/ResourcesManager( 7444): creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
W/ResourcesManager( 7444): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/UMC:Core( 7444): onCreate(): 
D/AndroidRuntime( 7442): 
D/AndroidRuntime( 7442): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7442): CheckJNI is OFF
D/AndroidRuntime( 7442): setted country_code = Germany
D/AndroidRuntime( 7442): setted countryiso_code = DE
D/AndroidRuntime( 7442): setted sales_code = DBT
D/AndroidRuntime( 7442): readGMSProperty: start
D/AndroidRuntime( 7442): readGMSProperty: already setted!!
D/AndroidRuntime( 7442): readGMSProperty: end
D/AndroidRuntime( 7442): addProductProperty: start
D/USER_AGENT( 7444): UMC/1.1.39 (SM-G900F) SAFE-5.3 KNOX-2.3
D/[SAMSUNG SMARCART NATIVE]( 7444): initialize...
D/[SAMSUNG SMARCART NATIVE]( 7444): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
I/CSTORAGE( 7444): ================================================
I/CSTORAGE( 7444):  CSTORAGE_SKM_LIB v1.0.8
I/CSTORAGE( 7444): ================================================
I/TZ_CCM_C_GetFunctionList: ( 7444): TZ_CCM_C_GetFunctionList was called
D/[SAMSUNG SMARCART NATIVE]( 7444): FINISHED: initialize rv:0
D/UMC:SecurityUtils( 7444): Loaded server certificates: 0
D/UMC:SecurityUtils( 7444): Loaded server certificates: 0
D/UMC:SecurityUtils( 7444): timaVersion on the device: 3.0
D/UMC:CloudMDMSecurity( 7444): New Flow
D/TimaService(  893): TIMA3: in ccmRegisterForDefaultCertificate
D/TimaService(  893): TIMA: in getTimaVersion
I/        (  893): CCM JNI: In ccm_register_for_default_cert
I/        (  893): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: (  893): DEBUG_CONTAINER_PROBLEM Enter TZ_CCM_C_Initialize_TLC!
I/TZ_CCM_C_Initialize: (  893): pInitArgs 0x96e20814 has not called C_Init before.
I/TZ_CCM_C_Initialize: (  893): &ctx = 0x9f9e5c1c
I/TLC_TZ_CCM: (  893): creating new ccm context...
I/TLC_TZ_CCM: (  893): initializing ccm context...
I/TLC_TZ_CCM: (  893): root = /firmware/image, root_strlen = 15
I/TLC_TZ_CCM: (  893): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  893): input max_sendmsg_size = 19420
I/TZ: client_server_communication(  893): input max_recvmsg_size = 19420
I/TZ: client_server_communication(  893): root = /firmware/image, root_len = 15
I/TZ: client_server_communication(  893): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  893): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication(  893): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication(  893): Client_Server_Open was called
V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/TZ: client_server_communication(  893): IClientServer::IClientServer()
I/TZ: client_server_communication(  893): BpClientServer::BpClientServer()
I/TZ: client_server_communication(  893): IClientServer::~IClientServer()
I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 1078): OPENSWCONN
I/TZ_CCM_SERVER( 1078): creating new ccm context...
I/TZ_CCM_SERVER( 1078): initializing ccm context...
I/TZ_CCM_SERVER( 1078): root = /firmware/image, root_strlen = 15
I/TZ_CCM_SERVER( 1078): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1078): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1078): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1078): aligned max_sendmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1078): aligned max_recvmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1078): max_message_size = 38912 = 0x9800
D/QSEECOMAPI: ( 1078): QSEECom_get_handle sb_length = 0x9800
D/QSEECOMAPI: ( 1078): App is not loaded in QSEE
I/GLSUser ( 1817): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1817): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1817): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1817): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/QSEECOMAPI: ( 1078): Loaded image: APP id = 2
E/AffinityControl( 7442): AffinityControl: registerfunction enter
V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/TZ: qc_tlc_communication( 1078): TIMA: path = /firmware/image, fname = tz_ccm, tzapp is loaded
I/TZ: client_server_communication(  893): OpenSWConn(CCM) is successful
I/TZ: client_server_communication(  893): Client_Server_Open succeeded, serverName = CCM
I/TZ_CCM_C_Initialize: (  893): ctx = 0x932d6770, comm = 0x93eda640, sendmsg = 0x8ed10000, recvmsg = 0x8ed14c00
I/TZ_init: (  893): TZ_init: sending initialization request...
I/TZ: client_server_communication(  893): Cmd id = 2, len = 19456
I/TZ: client_server_communication(  893): Calling Communicate()
I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1078): COMM
I/TZ_init: (  893): TZ_init: successful initialization
I/TLC_TZ_COMMON: key_db_init: (  893): Exercising TZ_DB_INIT in TLC
I/TZ: client_server_communication(  893): Cmd id = 17, len = 19456
I/TZ: client_server_communication(  893): Calling Communicate()
I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1078): COMM
D/Finsky  ( 6615): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6615): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6615): [1] 5.onFinished: Scheduling replication attempt 2.
D/AndroidRuntime( 7442): Calling main entry com.android.commands.am.Am
I/TZ_COMMON: tlc_key_db_util: (  893): DB Operation suceeded
I/TLC_TZ_CCM: register for default cert: (  893): Exercising TZ_CCM_register_default_TLC
I/TZ: client_server_communication(  893): Cmd id = 25, len = 19456
I/TZ: client_server_communication(  893): Calling Communicate()
I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1078): COMM
I/TLC_TZ_CCM: register for default cert: (  893): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: (  893): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
I/TZ_CCM_C_Finalize: (  893): DEBUG_CONTAINER_PROBLEM Exercising TZ_CCM_C_Finalize_TLC
I/TZ: client_server_communication(  893): Cmd id = 41, len = 19456
I/TZ: client_server_communication(  893): Calling Communicate()
I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1078): COMM
I/TZ: client_server_communication(  893): Client_Server_Close was called
I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(1) 16
I/TZ_CCM_SERVER( 1078): CLOSESWCONN
D/QSEECOMAPI: ( 1078): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1078): QSEECom_shutdown_app, app_id = 2
I/TZ: client_server_communication(  893): Client_Server_Close succeeded
D/UMC:CloudMDMSecurity( 7444): ccmRegisterForDefaultCertificate: 0
D/UMC:CloudMDMSecurity( 7444): TIMA service call for password change success!!
E/PersonaManagerService(  893): inState():  stateMachine is null !!
D/UMC:AdminManager( 7444): init - start
V/ApplicationPolicy(  893): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  893): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  893): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/UMC:AdminManager( 7444): loadAdmins
W/ActivityManager(  893): mDVFSHelper.acquire()
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7489): MountEmulatedStorage()
E/Zygote  ( 7489): v2
I/libpersona( 7489): KNOX_SDCARD checking this for 10200
I/libpersona( 7489): KNOX_SDCARD not a persona
I/ActivityManager(  893): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7489 uid=10200 gids={50200, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/UMC:AdminManager( 7444): startPolicyHandlers
I/UMC:TestPolicyHandler( 7444): Setup is called in testpolicyhandler
D/UMC:AdminManager( 7444): init - end
V/UMC:AlarmHandler( 7444): Enter loadList
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
I/SELinux ( 7489): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/AndroidRuntime( 7442): Shutting down VM
I/SELinux ( 7489): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7489): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/GSLBManager( 7444): migrateStoredUrlFromOldPref
D/GSLBManager( 7444): migrateStoredUrlFromOldPref : Migration Not Needed
D/UMC:UMCAdmin( 7444): deactivateUMCAdminIfNotRequired : -1
E/UMC:Utils( 7444): Admin not found in package com.samsung.knoxpb.mdm
D/UMC:UMCAdmin( 7444): deactivateUMCAdmin : -1
D/UMC:UMCAdmin( 7444): isContainer : 0
W/LicenseLogService(  893): log() failed
D/EnterpriseDeviceManagerService(  893): isManagedProfileUser(): userId = 0
E/UMC:UMCAdmin( 7444): No active admin owned by uid 10179
D/UMC:UMCAdmin( 7444): isContainer : 0
D/UMC:UMCAdmin( 7444): deactivateUMCAdmin - UMC App Admin deactivated
V/UMC:AlarmHandler( 7444): onReceive :Intent { flg=0x14 cmp=com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler (has extras) }
D/TimaKeyStoreProvider( 7489): TimaSignature is unavailable
D/ActivityThread( 7489): Added TimaKeyStore provider
D/QuickStartReceiver( 7444): Msg Id : 2
D/QuickStartReceiver( 7444): model : SM-G900F
D/QuickStartReceiver( 7444): id : 100
I/ActivityManager(  893): Killing 6712:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
V/ActivityManager(  893): Display changed displayId=0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (5/8)
I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/8)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager( 7489): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SQLiteSecureOpenHelper( 3549): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3549): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/libprocessgroup(  893): failed to open /acct/uid_1000/pid_6712/cgroup.procs: No such file or directory
D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  893): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/BatteryService(  893): stay LED for fully charged
D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  893): Plugged
I/MotionRecognitionService(  893): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/WebViewFactory( 7489): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7489): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7489): Loading: webviewchromium
,I/LibraryLoader( 7489): Time to load native libraries: 3 ms (timestamps 8816-8819)
,I/LibraryLoader( 7489): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7489): Binding Chromium to main looper Looper (main, tid 1) {3e2d457f}
,I/LibraryLoader( 7489): Expected native library version number "",actual native library version number ""
I/chromium( 7489): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7489): Initializing chromium process, renderers=0
,W/art     ( 7489): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7489): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7489): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7489): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,I/Adreno-EGL( 7489): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7489): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7489): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7489): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7489): Remote Branch: 
I/Adreno-EGL( 7489): Local Patches: 
I/Adreno-EGL( 7489): Reconstruct Branch: 
,W/chromium( 7489): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7489): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7489): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7489): onDetachedFromWindow called when already detached. Ignoring
,W/ActivityManager(  893): Activity pause timeout for ActivityRecord{276d1384 u0 com.test.thalitest/.MainActivity t18}
,D/SystemWebViewEngine( 7489): CordovaWebView is running on device made by: samsung
,W/art     ( 7489): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7489): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 7489): performCreate Call secproduct feature valuefalse
D/Activity( 7489): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 7489): Render dirty regions requested: true
,D/ActivityManager(  893): post active user change for 0
D/KnoxTimeoutHandler(  893): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  893): handleActiveUserChange for user 0
,I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/StatusBarManagerService(  893): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/StatusBarManagerService(  893): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/OpenGLRenderer( 7489): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7489): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7489): Enabling debug mode 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/SSRM:m  (  893): SIOP:: AP = 360, PST = 420, CUR = 300
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/InputMethodManagerService(  893): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/ActivityManager(  893): mDVFSHelper.release()
,I/Timeline(  893): Timeline: Activity_windows_visible id: ActivityRecord{276d1384 u0 com.test.thalitest/.MainActivity t18} time:99407
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,W/IInputConnectionWrapper( 7489): showStatusIcon on inactive InputConnection
,I/Timeline( 7489): Timeline: Activity_idle id: android.os.BinderProxy@3ed7f34e time:99418
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/chromium( 7489): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7489): 
,D/JsMessageQueue( 7489): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7489): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1359594880
,I/chromium( 7489): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/SMD     (  289): DCD ON
,I/art     ( 7489): Background partial concurrent mark sweep GC freed 13105(1593KB) AllocSpace objects, 6(1298KB) LOS objects, 43% free, 20MB/36MB, paused 1.366ms total 103.733ms
,W/jxcore-log( 7489): Initializing JXcore engine
,W/jxcore-log( 7489): JXcore engine is ready
,E/SMD     (  289): DCD ON
,E/auditd  ( 2173): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  893): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  893): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,W/jxcore-log( 7489): Starting JXcore engine
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7595): MountEmulatedStorage()
,E/Zygote  ( 7595): v2
I/libpersona( 7595): KNOX_SDCARD checking this for 1000
I/libpersona( 7595): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7595 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7595): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7595): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,W/jxcore-log( 7489): Platform android
W/jxcore-log( 7489): 
W/jxcore-log( 7489): Process ARCH arm
W/jxcore-log( 7489): 
,E/SELinux ( 7595): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7595): TimaSignature is unavailable
,D/ActivityThread( 7595): Added TimaKeyStore provider
,E/Watchdog(  893): !@Sync 3
,D/ResourcesManager( 7595): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7595):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7595):  SeDenialReceiver : File path = null
I/ActivityManager(  893): Killing 5961:com.sec.android.widgetapp.activeapplicationwidget/u0a158 (adj 15): bgCount ##41
,W/libprocessgroup(  893): failed to open /acct/uid_10158/pid_5961/cgroup.procs: No such file or directory
,I/PowerManagerService(  893): [PWL] Off : 15s ago
,I/jxcore-log( 7489): JXcore Cordova bridge is ready!
I/jxcore-log( 7489): 
W/jxcore-log( 7489): JXcore engine is started
,I/jxcore-log( 7489): Toggling radios to true
I/jxcore-log( 7489): 
,D/BluetoothAdapter( 7489): enable()
,D/BluetoothAdapter( 7489): enable(): BT is already enabled..!
,D/WifiService(  893): New client listening to asynchronous messages
I/WifiManager( 7489): packageName : com.test.thalitest
,D/SecContentProvider(  893): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  893): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2(  893): mCursor = null
,D/WifiService(  893): setWifiEnabled: true pid=7489, uid=10200
,E/WifiService(  893): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  893): Permission Denial: getCurrentUser() from pid=7489, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  893): Failed getting userId using ActivityManagerNative
W/WifiService(  893): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7489, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  893): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  893): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  893): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  893): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  893): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  893): name = wifi_on
,I/WifiService(  893): disconnect: pid=7489, uid=10200
,I/wpa_supplicant( 1291): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7489): Radios toggled
I/jxcore-log( 7489): 
,I/jxcore-log( 7489): My device name is: samsung-SM-G900F
I/jxcore-log( 7489): 
,I/wpa_supplicant( 1291): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1291): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1291): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1291): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  893): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1291): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1291): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1291): Disconnected - do not scan
I/wpa_supplicant( 1291): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  893): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
,E/WifiStateMachine(  893): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  893): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  893): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  893): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  893): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/native  (  893): do suspend true
,D/WifiP2pService(  893): InactiveState{ what=143375 }
,D/WifiP2pService(  893): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  282): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1817): Read error: ssl=0xa191ee00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1817): SSL shutdown failed: ssl=0xa191ee00: I/O error during system call, Broken pipe
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): EvaluatingState{ when=-2ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): Validated
D/ConnectivityService(  893): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  893): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  893):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  893):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  893): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService(  893): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  893): calling update connectivity
D/ConnectivityService(  893):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  893):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  893): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524290
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  893): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  893): updateNetworkInfo()
,D/ConnectivityService(  893): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/ConnectivityService(  893): updateNetworkInfo()
,D/ConnectivityService(  893): ignoring duplicate network state non-change
,I/WifiTrafficPoller(  893): evaluateTrafficStatsPolling
D/ConnectivityService(  893): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,I/CLocInfoService(  893): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,E/WifiConfigStore(  893): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  893): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1291): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1291): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1291): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1291): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1291): First Scan Start
I/wpa_supplicant( 1291): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine(  893): ConnectModeState: Network connection lost 
E/WifiStateMachine(  893): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
E/WifiStateMachine(  893): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  893): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  893): do suspend true
,D/WifiP2pService(  893): InactiveState{ what=143375 }
,D/WifiP2pService(  893): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/Hs20UtilService( 1300): Starting #6
,I/Hs20UtilService( 1300): Message received 5007
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1300): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1300): MountReceiver.mPrefHandler - 7002
,D/CommandListener(  282): Clearing all IP addresses on wlan0
D/ConnectivityService(  893): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  893): calling update connectivity
D/ConnectivityService(  893):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity(  893): Not allowed due to - mEnabled false
D/ConnectivityService(  893):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  893): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  893): requiresClat: netType=1, connected=false, hasIPv4Address=true
E/WifiStateMachine(  893): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524292
D/WifiStateMachine(  893): updateConfiguredNetworkExpiration - currTime: 1453201994719
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): Disconnected - quitting
D/WifiStateMachine(  893): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,E/WifiStateMachine(  893): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  893): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityService(  893): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  893): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  893): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
I/WifiTrafficPoller(  893): evaluateTrafficStatsPolling
E/WifiStateMachine(  893): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/CSLegacyTypeTracker(  893): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory( 1461): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/CSLegacyTypeTracker(  893): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  893): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  893): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  893): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  893): NetworkAgent: NetworkAgent channel lost
,I/CLocInfoService(  893): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  893): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  893): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  893): setDetailed state send new extra info"NG700"
D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/SecContentProvider2(  893): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  893): mCursor = null
,D/ConnectivityService(  893): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  893): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  893): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  893): getSBEnabled() enabled =false
D/SmartBondingService(  893): getSBEnabled() enabled =false
D/SmartBondingService(  893): getSBEnabled() enabled =false
V/NetworkStats(  893): updateIfacesLocked()
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
V/NetworkStats(  893): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  893): UpdateStatsForKnox
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  893): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1170): updateDataNetType()
D/StatusBar.NetworkController( 1170): NoService, mRoamingIconId = 0
,D/NtpTrustedTime(  893): currentTimeMillis() cache hit
,V/NetworkStats(  893): performPollLocked() took 6ms
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
,D/NtpTrustedTime(  893): currentTimeMillis() cache hit
,D/NtpTrustedTime(  893): currentTimeMillis() cache hit
V/NetworkStats(  893): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
I/Hs20UtilService( 1300): Starting #7
,D/SecContentProvider2(  893): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  893): mCursor = null
,I/Hs20UtilService( 1300): Message received 5007
,D/StatusBar.NetworkController( 1170): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1300): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1300): MountReceiver.mPrefHandler - 7002
,D/NtpTrustedTime(  893): currentTimeMillis() cache hit
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/ConnectivityService(  893): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  893): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  893): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  893): CLoinfo wifi false
,I/ApplicationPolicy(  893): updateDataUsageMap
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  893): MasterInitialState.processMessage what=3
D/SmartBondingService(  893): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  893): getSBEnabled() enabled =false
D/SmartBondingService(  893): getSBEnabled() enabled =false
D/SmartBondingService(  893): getSBEnabled() enabled =false
,D/accuweather( 2107): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/SmartBondingService(  893): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3834): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/SLocation(  893): No Active Data Connection
,I/PCWCLIENTTRACE_PushUtil( 6806): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6806): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6806): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6806): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6806): noConnectivity : true
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5388): type=WIFI subType= reason=null isConnected=false
,I/DBG_DM  ( 3834): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/SystemBroadcastReceiver( 7191): [#DCM#] [DCM_Performance] onReceive completed in time  1155 microsec. 
,I/SystemBroadcastReceiver( 7191): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7191): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
,I/DCMController( 7191): [#DCM#] setIsConnectedForExtractors 
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7671): MountEmulatedStorage()
E/Zygote  ( 7671): v2
I/libpersona( 7671): KNOX_SDCARD checking this for 10002
I/libpersona( 7671): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7671 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7671): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7671): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7671): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7671): TimaSignature is unavailable
,D/ActivityThread( 7671): Added TimaKeyStore provider
,D/ResourcesManager( 7671): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  893): Killing 5944:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7690): MountEmulatedStorage()
E/Zygote  ( 7690): v2
I/libpersona( 7690): KNOX_SDCARD checking this for 1000
I/libpersona( 7690): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7690 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/libprocessgroup(  893): failed to open /acct/uid_1000/pid_5944/cgroup.procs: No such file or directory
,I/SELinux ( 7690): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7690): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7690): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7690): TimaSignature is unavailable
,D/ActivityThread( 7690): Added TimaKeyStore provider
,D/ResourcesManager( 7690): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7690): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7690): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/wpa_supplicant( 1291): nl80211: Received scan results (7 BSSes)
I/wpa_supplicant( 1291): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1291): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1291): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1291): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  893): [1,453,201,995,762 ms] noteScanEnd no scan source
,E/WifiStateMachine(  893): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3f03254f sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  893): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  893): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  893): setDetailed state send new extra info0x
I/CLocInfoService(  893): External Intent Received android.net.wifi.SCAN_RESULTS
,D/SecContentProvider2(  893): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  893): mCursor = null
,I/DIAGMON_AGENT( 7690): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7690): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7690): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7690): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/wpa_supplicant( 1291): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1291): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1291): Associated with C0.AA.48
,E/WifiStateMachine(  893): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  893): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  893): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  893): mCursor = null
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 1291): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1291): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  893): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  893): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  893): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  893): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  893): mCursor = null
,E/Zygote  ( 7709): MountEmulatedStorage()
I/libpersona( 7709): KNOX_SDCARD checking this for 10011
E/Zygote  ( 7709): v2
I/libpersona( 7709): KNOX_SDCARD not a persona
,I/wpa_supplicant( 1291): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1291): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,I/wpa_supplicant( 1291): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1291): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1291): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1291): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1291): Blacklist: Clear (temp) 
I/wpa_supplicant( 1291): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,I/ActivityManager(  893): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7709 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/WifiStateMachine(  893): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  893): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  893): Network connection established
,D/WifiNative-HAL(  893): callSECApiVoid - ID [50]
,E/WifiStateMachine(  893): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  893): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  893): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  893): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  893): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  893): Got NetworkAgent Messenger
D/ConnectivityService(  893): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  893): updateNetworkInfo()
D/ConnectivityService(  893): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  893): NetworkAgent connected
E/WifiStateMachine(  893): L2ConnectedState "NG700" nid=0
,E/WifiConfigStore(  893): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/SELinux ( 7709): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7709): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7709): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  893): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  893): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  893): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  893): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  282): Setting iface cfg
,E/WifiStateMachine(  893): Start Dhcp Watchdog 2
D/SecContentProvider2(  893): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  893): mCursor = null
,E/WifiStateMachine(  893): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  893): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService(  893): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/TimaKeyStoreProvider( 7709): TimaSignature is unavailable
,D/ActivityThread( 7709): Added TimaKeyStore provider
,D/ResourcesManager( 7709): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager(  893): Killing 6255:com.sec.providers.settingsearch/u0a168 (adj 15): bgCount ##41
,I/FOTA_Client( 7709): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7709): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,E/WifiStateMachine(  893): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  893): do suspend false
,D/SecContentProvider2(  893): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  893): mCursor = null
,D/WifiP2pService(  893): InactiveState{ what=143375 }
D/WifiP2pService(  893): P2pEnabledState{ what=143375 }
,I/FOTA_Client( 7709): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7709): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7709): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7730): MountEmulatedStorage()
E/Zygote  ( 7730): v2
I/libpersona( 7730): KNOX_SDCARD checking this for 10019
I/libpersona( 7730): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7730 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 6762:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,I/SELinux ( 7730): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  893): failed to open /acct/uid_10168/pid_6255/cgroup.procs: No such file or directory
,I/SELinux ( 7730): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7730): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7730): TimaSignature is unavailable
,D/ActivityThread( 7730): Added TimaKeyStore provider
,D/ResourcesManager( 7730): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7730): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/libprocessgroup(  893): failed to open /acct/uid_10015/pid_6762/cgroup.procs: No such file or directory
,I/KLMS-2.4.503: ( 7730): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453201996099
,I/KLMS-2.4.503: ( 7730): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7730): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7730): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  893): Killing 6789:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7745): MountEmulatedStorage()
,E/Zygote  ( 7745): v2
I/libpersona( 7745): KNOX_SDCARD checking this for 10037
I/libpersona( 7745): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7745 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7745): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
E/SMD     (  289): DCD ON
I/SELinux ( 7745): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7745): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7745): TimaSignature is unavailable
,D/ActivityThread( 7745): Added TimaKeyStore provider
,D/ResourcesManager( 7745): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7745): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  893): failed to open /acct/uid_10016/pid_6789/cgroup.procs: No such file or directory
,E/dhcpcd  ( 7760): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
E/SPPClientService( 5141): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/dhcpcd  ( 7760): version 5.5.6 starting
,E/dhcpcd  ( 7760): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/SA      ( 6846): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6846): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6846): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6846): [SLFUCHKMGR] constructor called
,I/SA      ( 6846): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6846): [OR] == isSIMCardReady false ==
,I/SA      ( 6846): [SCU] == networkStateCheck == false
I/SA      ( 6846): [OR] onReceive END
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/SPPClientService( 5141): [[SystemStateMonitorService]] No Active Internet
,E/Zygote  ( 7769): MountEmulatedStorage()
,E/Zygote  ( 7769): v2
I/libpersona( 7769): KNOX_SDCARD checking this for 10071
I/libpersona( 7769): KNOX_SDCARD not a persona
I/ActivityManager(  893): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7769 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,I/dhcpcd  ( 7760): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7760): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7760): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7760): bssid match
,I/dhcpcd  ( 7760): wlan0: rebinding lease of 192.168.1.135
,I/SELinux ( 7769): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  893): Killing 6484:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,I/SELinux ( 7769): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7769): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7769): TimaSignature is unavailable
,D/ActivityThread( 7769): Added TimaKeyStore provider
,D/ResourcesManager( 7769): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7769): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7769): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7769): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/comsamsunglog( 7769): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7769): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7769): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7769): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7769): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7769): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7769): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7769): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  893): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  893): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  893): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  893): selectionArgs: false
D/SettingsProvider(  893): selectionArgs: 10071
D/SecContentProvider(  893): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  893): ret = -1
,D/daemonapp( 1331): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/libprocessgroup(  893): failed to open /acct/uid_10034/pid_6484/cgroup.procs: No such file or directory
,D/accuweather( 7769): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7769): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7769): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7769): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
D/accuweather( 7769): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 7769): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1331): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7769): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1331): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7769): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1331): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7769): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7769): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7787): MountEmulatedStorage()
,E/Zygote  ( 7787): v2
I/libpersona( 7787): KNOX_SDCARD checking this for 1000
I/libpersona( 7787): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7787 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 4611:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,I/SELinux ( 7787): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7787): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7787): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7787): TimaSignature is unavailable
,D/ActivityThread( 7787): Added TimaKeyStore provider
,D/ResourcesManager( 7787): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7787): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  893): failed to open /acct/uid_10035/pid_4611/cgroup.procs: No such file or directory
,I/KnoxUsageLogPro( 7787): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7787): premStatus:2
,I/KnoxUsageLogPro( 7787): isEulaShown : false
I/KnoxUsageLogPro( 7787): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7802): MountEmulatedStorage()
,E/Zygote  ( 7802): v2
I/libpersona( 7802): KNOX_SDCARD checking this for 10088
I/libpersona( 7802): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7802 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 6104:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/art     (  337): Explicit concurrent mark sweep GC freed 8753(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 305us total 14.833ms
,I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 238us total 7.785ms
,I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 247us total 7.632ms
,I/SELinux ( 7802): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7802): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7802): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7802): TimaSignature is unavailable
,D/ActivityThread( 7802): Added TimaKeyStore provider
,D/ResourcesManager( 7802): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  893): failed to open /acct/uid_10042/pid_6104/cgroup.procs: No such file or directory
,I/ActivityManager(  893): Killing 5732:com.android.mms/u0a50 (adj 15): bgCount ##41
,D/Headlines( 5535): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5535): getCountryCode(): countryCode = DE
,D/Headlines( 5535): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5535): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5535): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5535): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5535): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5535): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5535): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7821): MountEmulatedStorage()
I/libpersona( 7821): KNOX_SDCARD checking this for 10128
E/Zygote  ( 7821): v2
I/libpersona( 7821): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7821 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7821): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/CountryDetector(  893): No listener is left
,I/SELinux ( 7821): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7821): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7821): TimaSignature is unavailable
,D/ActivityThread( 7821): Added TimaKeyStore provider
,D/ResourcesManager( 7821): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/libprocessgroup(  893): failed to open /acct/uid_10050/pid_5732/cgroup.procs: No such file or directory
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7821): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7821): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7821): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7821): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7821): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7821): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7821): Loading: webviewchromium
,I/LibraryLoader( 7821): Time to load native libraries: 4 ms (timestamps 7412-7416)
,I/LibraryLoader( 7821): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7821): Binding Chromium to main looper Looper (main, tid 1) {38d1c755}
,I/LibraryLoader( 7821): Expected native library version number "",actual native library version number ""
,I/chromium( 7821): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7821): Initializing chromium process, renderers=0
,W/art     ( 7821): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7821): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7821): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7821): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7821): Requires BLUETOOTH permission
,I/Adreno-EGL( 7821): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7821): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7821): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7821): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7821): Remote Branch: 
I/Adreno-EGL( 7821): Local Patches: 
I/Adreno-EGL( 7821): Reconstruct Branch: 
,I/NSApplication( 7821): Starting up...
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7882): MountEmulatedStorage()
E/Zygote  ( 7882): v2
I/libpersona( 7882): KNOX_SDCARD checking this for 10138
I/libpersona( 7882): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7882 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  893): Killing 6867:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,I/SELinux ( 7882): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7882): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7882): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7882): TimaSignature is unavailable
,W/libprocessgroup(  893): failed to open /acct/uid_10051/pid_6867/cgroup.procs: No such file or directory
,D/ActivityThread( 7882): Added TimaKeyStore provider
,D/ResourcesManager( 7882): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7882): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7882): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7882): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,V/AlarmManager(  893): waitForAlarm result :4
,D/QuickConnect( 7882): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7882): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7882): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7897): MountEmulatedStorage()
E/Zygote  ( 7897): v2
I/libpersona( 7897): KNOX_SDCARD checking this for 10163
I/libpersona( 7897): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7897 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 6887:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,I/Atfwd_Sendcmd(  347): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  347): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/SELinux ( 7897): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7897): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7897): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7897): TimaSignature is unavailable
,D/ActivityThread( 7897): Added TimaKeyStore provider
,D/ResourcesManager( 7897): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7897): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7897): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  893): failed to open /acct/uid_10058/pid_6887/cgroup.procs: No such file or directory
,D/RCPManagerService(  893): exchangeData() failure , invalid userId
,D/RCPManagerService(  893): exchangeData() failure , invalid userId
,D/RCPManagerService(  893): exchangeData() failure , invalid userId
,D/RCPManagerService(  893): exchangeData() failure , invalid userId
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/RCPManagerService(  893): exchangeData() failure , invalid userId
,E/Zygote  ( 7920): MountEmulatedStorage()
I/libpersona( 7920): KNOX_SDCARD checking this for 10078
E/Zygote  ( 7920): v2
I/libpersona( 7920): KNOX_SDCARD not a persona
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,I/ActivityManager(  893): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7920 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,I/SELinux ( 7920): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7920): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,E/SELinux ( 7920): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/RCPManagerService(  893): exchangeData() failure , invalid userId
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
D/TimaKeyStoreProvider( 7920): TimaSignature is unavailable
V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,D/ActivityThread( 7920): Added TimaKeyStore provider
V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
D/SecurityLogAgent( 7595): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7595): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7595): StateMachine : Current State = 1
I/ActivityManager(  893): Killing 6270:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,D/ResourcesManager( 7920): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7897): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
D/SecurityLogAgent( 7595): StateMachine : Changed Current State = 1
,I/ActivityManager(  893): Killing 6906:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,D/com.peel.receiver.ConnectivityActionReceiver( 5638): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 5638): 
D/com.peel.receiver.ConnectivityActionReceiver( 5638): 
D/com.peel.receiver.ConnectivityActionReceiver( 5638): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5638): 
,D/com.peel.receiver.ConnectivityActionReceiver( 5638): NO active network... no services...
D/com.peel.receiver.ConnectivityActionReceiver( 5638): 
D/com.peel.receiver.ConnectivityActionReceiver( 5638): 
D/com.peel.receiver.ConnectivityActionReceiver( 5638): last run: 1453190654528 -- System.currentTimeMillis()-last_run: 11343212
D/com.peel.receiver.ConnectivityActionReceiver( 5638): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5638): ... skip last_72_check
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 7920): onCreate
,D/BadgeProvider( 7920): DatabaseHelper
,E/Zygote  ( 7936): MountEmulatedStorage()
I/libpersona( 7936): KNOX_SDCARD checking this for 10178
E/Zygote  ( 7936): v2
I/libpersona( 7936): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7936 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7936): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7936): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7936): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 7920): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7920): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 7920): sendNotify, [notify] : null
D/BadgeProvider( 7920): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7920): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7920): update, [UpdateCount] : 1
,D/Launcher.Model( 1478): reloadBadges entered.
,D/TimaKeyStoreProvider( 7936): TimaSignature is unavailable
,D/ActivityThread( 7936): Added TimaKeyStore provider
,D/ResourcesManager( 7936): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/ActivityManager(  893): Killing 6965:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,I/iu.Environment( 2482): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2482): num queued entries: 0
,I/iu.UploadsManager( 2482): num updated entries: 0
,I/iu.SyncManager( 2482): NEXT; no task
,D/ChimeraCfgMgr( 2482): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/libprocessgroup(  893): failed to open /acct/uid_1000/pid_6270/cgroup.procs: No such file or directory
W/libprocessgroup(  893): failed to open /acct/uid_10098/pid_6906/cgroup.procs: No such file or directory
,I/Hs20UtilService( 1300): Starting #8
,I/Hs20UtilService( 1300): Message received 5007
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1300): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1300): MountReceiver.mPrefHandler - 7002
,I/art     (  893): Explicit concurrent mark sweep GC freed 58498(3MB) AllocSpace objects, 6(96KB) LOS objects, 30% free, 36MB/52MB, paused 1.371ms total 120.381ms
,W/libprocessgroup(  893): failed to open /acct/uid_10033/pid_6965/cgroup.procs: No such file or directory
,W/ActivityManager(  893): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/PackageManager(  893): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager(  893): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,I/InputReader(  893): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  893): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7959 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,E/Zygote  ( 7959): MountEmulatedStorage()
,E/Zygote  ( 7959): v2
I/libpersona( 7959): KNOX_SDCARD checking this for 10034
I/libpersona( 7959): KNOX_SDCARD not a persona
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,I/SELinux ( 7959): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7959): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7959): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,E/WifiStateMachine(  893): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  893): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  893): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/RegisteredServicesCache( 1455): empty dynamic service
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/TimaKeyStoreProvider( 7959): TimaSignature is unavailable
,D/ActivityThread( 7959): Added TimaKeyStore provider
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/SecContentProvider2(  893): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  893): mCursor = null
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4312, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): stay LED for fully charged
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/FeatureConfig( 7959): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/BackupManagerService(  893): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  893): Plugged
I/MotionRecognitionService(  893): setPowerConnected  = true
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
W/ResourcesManager(  893): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  893): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  893): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 7959): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 7959): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7959): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 7959): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 7959): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 7959): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 7959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7959): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 7959): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7959): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 7959): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7959): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 7959): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7983): MountEmulatedStorage()
,E/Zygote  ( 7983): v2
I/libpersona( 7983): KNOX_SDCARD checking this for 10035
I/libpersona( 7983): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=7983 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 6931:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,I/SELinux ( 7983): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7983): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7983): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7983): TimaSignature is unavailable
,D/ActivityThread( 7983): Added TimaKeyStore provider
,D/ResourcesManager( 7983): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/libprocessgroup(  893): failed to open /acct/uid_10099/pid_6931/cgroup.procs: No such file or directory
,I/dhcpcd  ( 7760): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,I/jxcore-log( 7489): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7489): 
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/dhcpcd  ( 7760): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  893): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  893): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  893): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): checkState()
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): checkState() : APP TYPE = Full
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8009): MountEmulatedStorage()
E/Zygote  ( 8009): v2
I/libpersona( 8009): KNOX_SDCARD checking this for 10017
I/libpersona( 8009): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=8009 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,I/SELinux ( 8009): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8009): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8009): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8009): TimaSignature is unavailable
,D/ActivityThread( 8009): Added TimaKeyStore provider
,D/ResourcesManager( 8009): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/BluetoothManager( 7983): getConnectedDevices
,E/WifiStateMachine(  893): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  893): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/native  (  893): do suspend true
,D/-----SIC-----( 7983): ------------------skip uv
,D/-----SIC-----( 7983): ------------------skip SPO2
D/-----SIC-----( 7983): ------------------skip TGH
,D/WifiP2pService(  893): InactiveState{ what=143375 }
,D/WifiP2pService(  893): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  893): WifiStateMachine DHCP successful
,E/WifiStateMachine(  893): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  893): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  893): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  893): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  893): Not connected state, yet.
E/WifiStateMachine(  893): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiStateMachine(  893): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  893): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  893): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  893): callSECApiInt - ID [210]
,E/WifiStateMachine(  893): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService(  893): updateNetworkInfo()
,D/ConnectivityService(  893): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  893): Adding iface wlan0 to network 503
,I/CLocInfoService(  893): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  893): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  893): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  893): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  893): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  893): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,I/SecureStorage( 8009): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  365): [INFO]: SPID(0x00000005)Credentials: uid 10017, gid 10017, pid 8009
I/SecureStorage(  365): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,D/ConnectivityService(  893): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  893): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  893): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  893): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  893): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  893): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
V/        (  282): QcRouteController
,E/WifiStateMachine(  893): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/SSRM:m  (  893): SIOP:: AP = 400, PST = 417, CUR = 300
D/WifiStateMachine(  893): Now, connected state.
E/WifiStateMachine(  893): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  893): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,E/WifiStateMachine(  893): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  893): evaluateTrafficStatsPolling
,I/CLocInfoService(  893): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  893): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/        (  282): QcRouteController
,I/WifiTrafficPoller(  893): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  893): mBoosterFLAG : 0
I/WifiTrafficPoller(  893): current booster mode : FullMode
,D/WifiNative-HAL(  893): callSECApiVoid - ID [212]
,I/CLocInfoService(  893): External Intent Received android.net.wifi.STATE_CHANGE
W/NetworkManagementService(  893): route cmd failed: 
W/NetworkManagementService(  893): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '67 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 67 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  893): '
W/NetworkManagementService(  893): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  893): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  893): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  893): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  893): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  893): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  893): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  893): 	at com.android.server.ConnectivityService.updateNetworkInfo(ConnectivityService.java:5997)
W/NetworkManagementService(  893): 	at com.android.server.ConnectivityService.access$1900(ConnectivityService.java:230)
W/NetworkManagementService(  893): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2337)
W/NetworkManagementService(  893): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  893): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  893): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService(  893): updateSourceRoutes : add src route for:192.168.1.135
,V/        (  282): QcRouteController
I/WifiStateMachine(  893): REQUEST_POWER_SAVE_ON
D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
V/        (  282): QcRouteController
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7983): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
V/        (  282): QcRouteController
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7983): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,V/        (  282): QcRouteController
V/MediaPlayer( 7983): decode(34, 19359868, 4230)
V/        (  282): QcRouteController
V/MediaPlayerService(  301): decode(30, 19359868, 4230)
V/MediaPlayerService(  301): player type = 3
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): constructor
V/        (  282): QcRouteController
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/        (  282): QcRouteController
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): StagefrightPlayer
V/AwesomePlayer(  301): setListener
V/StagefrightPlayer(  301): initCheck
V/AwesomePlayer(  301): setAudioSink
V/StagefrightPlayer(  301): setDataSource(30, 19359868, 4230)
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
D/Utils   (  301): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  301): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  301): mBitrate = -1 bits/sec
I/OggExtractor(  301): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  301): current audio track index (0) is added to vector
V/AwesomePlayer(  301): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  301): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  301): prepare
V/AwesomePlayer(  301): prepareAsync
,V/MediaPlayerService(  301): wait for prepare
V/AwesomePlayer(  301): onPrepareAsyncEvent
I/SecMediaClock(  301): SecMediaClock constructor
I/SecMediaClock(  301): reset
I/SecVideoCapture(  301): SecVideoCapture constructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): initAudioDecoder
V/AwesomePlayer(  301): checkOffloadExceptions is true
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  301): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
,I/AwesomePlayer(  301): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,E/SMD     (  289): DCD ON
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/        (  282): QcRouteController
,V/AwesomePlayer(  301): finishAsyncPrepare_l
V/AwesomePlayer(  301): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 200, 973, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache(  301): notify(0xb0d14060, 5, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 1, 0, 0)
V/AudioCache(  301): prepared
V/AudioCache(  301): wait - success
,V/MediaPlayerService(  301): start
V/StagefrightPlayer(  301): start
V/AwesomePlayer(  301): play
V/AwesomePlayer(  301): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  301): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  301): start of Playback, useOffload 0
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  301): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] End Of Stream
,I/AudioPlayer(  301): Audio channels(1)
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  301): open(44100, 1, 0x0, 1, 0)
D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthServiceInstalled() : HealthService is Installed.
,V/AwesomePlayer(  301): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 6, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): addBatteryData
,V/MediaPlayerService(  301): wait for playback complete
,D/ConnectivityService(  893): Setting Dns servers for network 503 to [/192.168.1.1]
,I/AudioPlayer(  301): First fillBuffer call!!
I/AudioPlayer(  301): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  301): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
V/AwesomePlayer(  301): postAudioEOS delayUs (0)
,V/AwesomePlayer(  301): onCheckAudioStatus
V/AwesomePlayer(  301): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  301): onStreamDone
D/Nat464Xlat(  893): requiresClat: netType=1, connected=false, hasIPv4Address=true
V/AwesomePlayer(  301): MEDIA_PLAYBACK_COMPLETE
D/ConnectivityService(  893): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
V/AwesomePlayer(  301): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
D/ConnectivityService(  893): calling update connectivity
V/AudioCache(  301): notify(0xb0d14060, 2, 0, 0)
D/ConnectivityService(  893): ignoring duplicate network state non-change
V/AudioCache(  301): playback complete - thread will wake up later
D/ConnectivityService(  893): ignoring duplicate network state non-change
V/AwesomePlayer(  301): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
D/ConnectivityService(  893): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/AudioCache(  301): notify(0xb0d14060, 7, 0, 0)
D/ConnectivityService(  893): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
V/AudioCache(  301): ignored
D/ConnectivityService(  893): calling update connectivity
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=1)
D/ConnectivityService(  893): rematching NetworkAgentInfo [WIFI () - 503]
V/AwesomePlayer(  301): addBatteryData
D/ConnectivityService(  893):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  893): updateNetworkInfo()
D/ConnectivityService(  893):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
V/AudioCache(  301): wait - success
D/ConnectivityService(  893):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  893): updateNetworkInfo()
D/ConnectivityService(  893): currentScore = 0, newScore = 60
V/StagefrightPlayer(  301): reset
D/ConnectivityService(  893):    accepting network in place of null
V/AwesomePlayer(  301): reset_l()
D/ConnectivityService(  893): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
D/AudioPlayer(  301): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop() sendCommand(0x74, OMX_CommandStateSet, OMX_StateIdle)
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): Connected
I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): Validated
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  301): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  301): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  301): ~OggSource --
I/OggExtractor(  301): ~OggExtractor ++
I/OggExtractor(  301): ~MyVorbisExtractor ++ 
I/OggExtractor(  301): ~MyVorbisExtractor --
I/OggExtractor(  301): ~OggExtractor --
,I/AudioPlayer(  301): reset out
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  301): SecVideoCapture destructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): mSecCapture clear
I/SecMediaClock(  301): SecMediaClock destructor
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): ~StagefrightPlayer
V/StagefrightPlayer(  301): reset
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/AwesomePlayer(  301): destructor
E/CSLegacyTypeTracker(  893): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  893): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  893): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/MediaPlayer( 7983): decode(35, 19213040, 15440)
V/MediaPlayerService(  301): decode(30, 19213040, 15440)
V/MediaPlayerService(  301): player type = 3
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): constructor
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): StagefrightPlayer
V/AwesomePlayer(  301): setListener
V/StagefrightPlayer(  301): initCheck
V/AwesomePlayer(  301): setAudioSink
V/StagefrightPlayer(  301): setDataSource(30, 19213040, 15440)
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a7e0, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
D/Utils   (  301): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  301): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  301): mBitrate = -1 bits/sec
I/OggExtractor(  301): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  301): current audio track index (0) is added to vector
V/AwesomePlayer(  301): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  301): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  301): prepare
V/AwesomePlayer(  301): prepareAsync
V/MediaPlayerService(  301): wait for prepare
V/AwesomePlayer(  301): onPrepareAsyncEvent
I/SecMediaClock(  301): SecMediaClock constructor
I/SecMediaClock(  301): reset
I/SecVideoCapture(  301): SecVideoCapture constructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): initAudioDecoder
V/AwesomePlayer(  301): checkOffloadExceptions is true
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/TelephonyNetworkFactory( 1461): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/OMXCodec(  301): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
D/ConnectivityService(  893): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  893): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  893): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  893): getSBEnabled() enabled =false
D/SmartBondingService(  893): getSBEnabled() enabled =false
D/SmartBondingService(  893): getSBEnabled() enabled =false
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
V/NetworkStats(  893): updateIfacesLocked()
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
V/NetworkStats(  893): performPollLocked(flags=0x1)
I/AwesomePlayer(  301): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
D/NetworkStatsFactory(  893): UpdateStatsForKnox
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  301): finishAsyncPrepare_l
V/AwesomePlayer(  301): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
V/AudioCache(  301): notify(0xb061a7e0, 200, 973, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a7e0, 5, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a7e0, 1, 0, 0)
V/AudioCache(  301): prepared
V/AudioCache(  301): wait - success
V/MediaPlayerService(  301): start
V/StagefrightPlayer(  301): start
V/AwesomePlayer(  301): play
V/AwesomePlayer(  301): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  301): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  301): start of Playback, useOffload 0
D/ConnectivityService(  893): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
V/NetworkStats(  893): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  301): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  301): Audio channels(2)
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  301): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  301): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a7e0, 6, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): addBatteryData
V/MediaPlayerService(  301): wait for playback complete
I/AudioPlayer(  301): First fillBuffer call!!
I/AudioPlayer(  301): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  301): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
D/SmartBondingService(  893): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/NetworkStats(  893): performPollLocked() took 16ms
D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1170): updateDataNetType()
D/StatusBar.NetworkController( 1170): NoService, mRoamingIconId = 0
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
D/EntConnectivity(  893): Not allowed due to - mEnabled false
D/ConnectivityService(  893): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  893): calling update connectivity
D/ConnectivityService(  893):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  893):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/StatusBar.NetworkController( 1170): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/ConnectivityService(  893): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/ConnectivityService(  893): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524290
D/ConnectivityService(  893): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  893):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  893):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  893): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  893): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  893): calling update connectivity
D/ConnectivityService(  893):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  893):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  893): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  893): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524290
I/OMXCodec(  301): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  301): postAudioEOS delayUs (0)
V/AwesomePlayer(  301): onCheckAudioStatus
V/AwesomePlayer(  301): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  301): onStreamDone
V/AwesomePlayer(  301): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  301): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a7e0, 2, 0, 0)
V/AudioCache(  301): playback complete - thread will wake up later
D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/AwesomePlayer(  301): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a7e0, 7, 0, 0)
V/AudioCache(  301): ignored
D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1170): updateDataNetType()
D/StatusBar.NetworkController( 1170): NoService, mRoamingIconId = 0
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  301): addBatteryData
V/AudioCache(  301): wait - success
V/StagefrightPlayer(  301): reset
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
D/NtpTrustedTime(  893): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1170): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
V/AwesomePlayer(  301): reset_l()
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a7e0, 8, 0, 0)
D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
D/AudioPlayer(  301): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop() sendCommand(0x75, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  301): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  301): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  301): ~OggSource --
I/OggExtractor(  301): ~OggExtractor ++
I/OggExtractor(  301): ~MyVorbisExtractor ++ 
I/OggExtractor(  301): ~MyVorbisExtractor --
I/OggExtractor(  301): ~OggExtractor --
I/UpdateIcingCorporaServi( 1684): Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
I/AudioPlayer(  301): reset out
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  301): SecVideoCapture destructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): mSecCapture clear
I/SecMediaClock(  301): SecMediaClock destructor
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): ~StagefrightPlayer
V/StagefrightPlayer(  301): reset
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/AwesomePlayer(  301): destructor
D/AdaptiveEventManager( 1170): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
V/AwesomePlayer(  301): reset_l()
D/AdaptiveEventManager( 1170): M updateContainers()
D/AdaptiveEventContainerSmall( 1170): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1170): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1170): pedoEvent == null
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/MediaPlayer( 7983): decode(36, 19257568, 9226)
V/MediaPlayerService(  301): decode(30, 19257568, 9226)
V/MediaPlayerService(  301): player type = 3
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): constructor
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): StagefrightPlayer
V/AwesomePlayer(  301): setListener
V/StagefrightPlayer(  301): initCheck
V/AwesomePlayer(  301): setAudioSink
V/StagefrightPlayer(  301): setDataSource(30, 19257568, 9226)
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0f0f150, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
D/Utils   (  301): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  301): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  301): mBitrate = -1 bits/sec
I/OggExtractor(  301): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  301): current audio track index (0) is added to vector
V/AwesomePlayer(  301): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  301): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  301): prepare
V/AwesomePlayer(  301): prepareAsync
V/MediaPlayerService(  301): wait for prepare
V/AwesomePlayer(  301): onPrepareAsyncEvent
I/SecMediaClock(  301): SecMediaClock constructor
I/SecMediaClock(  301): reset
I/SecVideoCapture(  301): SecVideoCapture constructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): initAudioDecoder
V/AwesomePlayer(  301): checkOffloadExceptions is true
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  301): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  301): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  301): finishAsyncPrepare_l
V/AwesomePlayer(  301): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  301): notify(0xb0f0f150, 200, 973, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0f0f150, 5, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0f0f150, 1, 0, 0)
V/AudioCache(  301): prepared
V/AudioCache(  301): wait - success
V/MediaPlayerService(  301): start
V/StagefrightPlayer(  301): start
V/AwesomePlayer(  301): play
V/AwesomePlayer(  301): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  301): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  301): start of Playback, useOffload 0
I/OMXCodec(  301): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  301): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  301): Audio channels(2)
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  301): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  301): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0f0f150, 6, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): addBatteryData
V/MediaPlayerService(  301): wait for playback complete
I/AudioPlayer(  301): First fillBuffer call!!
I/AudioPlayer(  301): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  301): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
I/OMXCodec(  301): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  301): postAudioEOS delayUs (0)
V/AwesomePlayer(  301): onCheckAudioStatus
V/AwesomePlayer(  301): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  301): onStreamDone
V/AwesomePlayer(  301): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  301): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0f0f150, 2, 0, 0)
V/AudioCache(  301): playback complete - thread will wake up later
V/AwesomePlayer(  301): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0f0f150, 7, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  301): addBatteryData
V/AudioCache(  301): wait - success
V/StagefrightPlayer(  301): reset
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0f0f150, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
D/AudioPlayer(  301): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop() sendCommand(0x76, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  301): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  301): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  301): ~OggSource --
I/OggExtractor(  301): ~OggExtractor ++
I/OggExtractor(  301): ~MyVorbisExtractor ++ 
I/OggExtractor(  301): ~MyVorbisExtractor --
I/OggExtractor(  301): ~OggExtractor --
I/AudioPlayer(  301): reset out
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  301): SecVideoCapture destructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): mSecCapture clear
I/SecMediaClock(  301): SecMediaClock destructor
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): ~StagefrightPlayer
V/StagefrightPlayer(  301): reset
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/AwesomePlayer(  301): destructor
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/MediaPlayer( 7983): decode(37, 19364180, 4890)
V/MediaPlayerService(  301): decode(30, 19364180, 4890)
V/MediaPlayerService(  301): player type = 3
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): constructor
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): StagefrightPlayer
V/AwesomePlayer(  301): setListener
V/StagefrightPlayer(  301): initCheck
V/AwesomePlayer(  301): setAudioSink
D/AdaptiveEventManager( 1170): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1170): M updateContainers()
I/ActivityManager(  893): Killing 7013:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
D/AdaptiveEventContainerSmall( 1170): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1170): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1170): pedoEvent == null
I/ActivityManager(  893): Killing 7001:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##42
V/StagefrightPlayer(  301): setDataSource(30, 19364180, 4890)
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a650, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
D/Utils   (  301): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  301): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  301): mBitrate = -1 bits/sec
I/OggExtractor(  301): OggSource::OggSource() mExtractor ref count = 4
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
V/AwesomePlayer(  301): current audio track index (0) is added to vector
V/AwesomePlayer(  301): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  301): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  301): prepare
V/AwesomePlayer(  301): prepareAsync
V/MediaPlayerService(  301): wait for prepare
V/AwesomePlayer(  301): onPrepareAsyncEvent
I/SecMediaClock(  301): SecMediaClock constructor
I/SecMediaClock(  301): reset
I/SecVideoCapture(  301): SecVideoCapture constructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): initAudioDecoder
V/AwesomePlayer(  301): checkOffloadExceptions is true
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  301): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  301): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  301): finishAsyncPrepare_l
V/AwesomePlayer(  301): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  301): notify(0xb061a650, 200, 973, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a650, 5, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a650, 1, 0, 0)
V/AudioCache(  301): prepared
V/AudioCache(  301): wait - success
V/MediaPlayerService(  301): start
V/StagefrightPlayer(  301): start
V/AwesomePlayer(  301): play
V/AwesomePlayer(  301): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  301): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  301): start of Playback, useOffload 0
E/Zygote  ( 8097): MountEmulatedStorage()
I/libpersona( 8097): KNOX_SDCARD checking this for 10075
E/Zygote  ( 8097): v2
I/libpersona( 8097): KNOX_SDCARD not a persona
I/OMXCodec(  301): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  301): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  301): Audio channels(1)
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  301): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  301): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a650, 6, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): addBatteryData
V/MediaPlayerService(  301): wait for playback complete
,I/ActivityManager(  893): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=8097 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8097): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/AudioPlayer(  301): First fillBuffer call!!
I/AudioPlayer(  301): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
,E/AudioPlayer(  301): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/SELinux ( 8097): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] End Of Stream
E/SELinux ( 8097): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/AwesomePlayer(  301): postAudioEOS delayUs (0)
,V/AwesomePlayer(  301): onCheckAudioStatus
,V/AwesomePlayer(  301): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  301): onStreamDone
V/AwesomePlayer(  301): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  301): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a650, 2, 0, 0)
,V/AudioCache(  301): playback complete - thread will wake up later
V/AwesomePlayer(  301): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a650, 7, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  301): addBatteryData
V/AudioCache(  301): wait - success
V/StagefrightPlayer(  301): reset
,V/AwesomePlayer(  301): reset_l()
,V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a650, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
,D/AudioPlayer(  301): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop() sendCommand(0x77, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  301): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  301): OggSource::~OggSource() mExtractor !mStarted ref count = 1
,I/OggExtractor(  301): ~OggSource --
I/OggExtractor(  301): ~OggExtractor ++
I/OggExtractor(  301): ~MyVorbisExtractor ++ 
I/OggExtractor(  301): ~MyVorbisExtractor --
I/OggExtractor(  301): ~OggExtractor --
,I/AudioPlayer(  301): reset out
,V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  301): SecVideoCapture destructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): mSecCapture clear
I/SecMediaClock(  301): SecMediaClock destructor
V/AwesomePlayer(  301): mSecMediaClock clear
,V/StagefrightPlayer(  301): ~StagefrightPlayer
V/StagefrightPlayer(  301): reset
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/AwesomePlayer(  301): destructor
,V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
,V/AwesomePlayer(  301): mSecMediaClock clear
V/MediaPlayer( 7983): decode(38, 19290344, 17329)
,V/MediaPlayerService(  301): decode(30, 19290344, 17329)
V/MediaPlayerService(  301): player type = 3
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): constructor
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): StagefrightPlayer
V/AwesomePlayer(  301): setListener
V/StagefrightPlayer(  301): initCheck
V/AwesomePlayer(  301): setAudioSink
V/StagefrightPlayer(  301): setDataSource(30, 19290344, 17329)
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0a02330, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
D/Utils   (  301): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  301): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  301): mBitrate = -1 bits/sec
I/OggExtractor(  301): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  301): current audio track index (0) is added to vector
V/AwesomePlayer(  301): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  301): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  301): prepare
V/AwesomePlayer(  301): prepareAsync
V/MediaPlayerService(  301): wait for prepare
,D/TimaKeyStoreProvider( 8097): TimaSignature is unavailable
,D/ActivityThread( 8097): Added TimaKeyStore provider
,V/AwesomePlayer(  301): onPrepareAsyncEvent
I/SecMediaClock(  301): SecMediaClock constructor
I/SecMediaClock(  301): reset
I/SecVideoCapture(  301): SecVideoCapture constructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): initAudioDecoder
V/AwesomePlayer(  301): checkOffloadExceptions is true
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  301): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  301): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  301): finishAsyncPrepare_l
V/AwesomePlayer(  301): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  301): notify(0xb0a02330, 200, 973, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0a02330, 5, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0a02330, 1, 0, 0)
V/AudioCache(  301): prepared
V/AudioCache(  301): wait - success
V/MediaPlayerService(  301): start
V/StagefrightPlayer(  301): start
V/AwesomePlayer(  301): play
V/AwesomePlayer(  301): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  301): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  301): start of Playback, useOffload 0
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  301): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  301): Audio channels(2)
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  301): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  301): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0a02330, 6, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): addBatteryData
,V/MediaPlayerService(  301): wait for playback complete
,I/AudioPlayer(  301): First fillBuffer call!!
I/AudioPlayer(  301): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  301): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  301): postAudioEOS delayUs (0)
,V/AwesomePlayer(  301): onCheckAudioStatus
,V/AwesomePlayer(  301): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  301): onStreamDone
V/AwesomePlayer(  301): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  301): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0a02330, 2, 0, 0)
V/AudioCache(  301): playback complete - thread will wake up later
,V/AwesomePlayer(  301): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0a02330, 7, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  301): addBatteryData
V/AudioCache(  301): wait - success
V/StagefrightPlayer(  301): reset
,V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0a02330, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
D/AudioPlayer(  301): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop() sendCommand(0x78, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  301): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  301): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  301): ~OggSource --
I/OggExtractor(  301): ~OggExtractor ++
I/OggExtractor(  301): ~MyVorbisExtractor ++ 
I/OggExtractor(  301): ~MyVorbisExtractor --
I/OggExtractor(  301): ~OggExtractor --
,I/AudioPlayer(  301): reset out
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  301): SecVideoCapture destructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): mSecCapture clear
I/SecMediaClock(  301): SecMediaClock destructor
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): ~StagefrightPlayer
V/StagefrightPlayer(  301): reset
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/AwesomePlayer(  301): destructor
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/MediaPlayer( 7983): decode(39, 19190536, 6644)
V/MediaPlayerService(  301): decode(30, 19190536, 6644)
,V/MediaPlayerService(  301): player type = 3
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): constructor
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): StagefrightPlayer
V/AwesomePlayer(  301): setListener
V/StagefrightPlayer(  301): initCheck
V/AwesomePlayer(  301): setAudioSink
V/StagefrightPlayer(  301): setDataSource(30, 19190536, 6644)
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
D/Utils   (  301): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  301): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  301): mBitrate = -1 bits/sec
I/OggExtractor(  301): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  301): current audio track index (0) is added to vector
V/AwesomePlayer(  301): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  301): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  301): prepare
V/AwesomePlayer(  301): prepareAsync
V/MediaPlayerService(  301): wait for prepare
,V/AwesomePlayer(  301): onPrepareAsyncEvent
I/SecMediaClock(  301): SecMediaClock constructor
I/SecMediaClock(  301): reset
I/SecVideoCapture(  301): SecVideoCapture constructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): initAudioDecoder
V/AwesomePlayer(  301): checkOffloadExceptions is true
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
E/DatabaseUtils(  893): Writing exception to parcel
E/DatabaseUtils(  893): java.lang.NullPointerException: key == null
E/DatabaseUtils(  893): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils(  893): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils(  893): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils(  893): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/DatabaseUtils(  893): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils(  893): 	at android.os.Binder.execTransact(Binder.java:446)
,I/OMXCodec(  301): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  301): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/ResourcesManager( 8097): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  301): finishAsyncPrepare_l
V/AwesomePlayer(  301): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 200, 973, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 5, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 1, 0, 0)
V/AudioCache(  301): prepared
V/AudioCache(  301): wait - success
V/MediaPlayerService(  301): start
V/StagefrightPlayer(  301): start
V/AwesomePlayer(  301): play
V/AwesomePlayer(  301): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  301): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  301): start of Playback, useOffload 0
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  301): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  301): Audio channels(1)
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  301): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  301): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 6, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): addBatteryData
V/MediaPlayerService(  301): wait for playback complete
I/AudioPlayer(  301): First fillBuffer call!!
,I/AudioPlayer(  301): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  301): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  301): postAudioEOS delayUs (0)
,V/AwesomePlayer(  301): onCheckAudioStatus
V/AwesomePlayer(  301): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  301): onStreamDone
V/AwesomePlayer(  301): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  301): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 2, 0, 0)
V/AudioCache(  301): playback complete - thread will wake up later
V/AwesomePlayer(  301): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 7, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=1)
,D/FileShare-Server( 8097): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,V/AwesomePlayer(  301): addBatteryData
V/AudioCache(  301): wait - success
V/StagefrightPlayer(  301): reset
,V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
D/AudioPlayer(  301): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop() sendCommand(0x79, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  301): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  301): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  301): ~OggSource --
I/OggExtractor(  301): ~OggExtractor ++
I/OggExtractor(  301): ~MyVorbisExtractor ++ 
I/OggExtractor(  301): ~MyVorbisExtractor --
I/OggExtractor(  301): ~OggExtractor --
,I/AudioPlayer(  301): reset out
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  301): SecVideoCapture destructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): mSecCapture clear
I/SecMediaClock(  301): SecMediaClock destructor
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): ~StagefrightPlayer
V/StagefrightPlayer(  301): reset
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/AwesomePlayer(  301): destructor
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
,V/MediaPlayer( 7983): decode(40, 19266876, 23389)
,V/MediaPlayerService(  301): decode(30, 19266876, 23389)
V/MediaPlayerService(  301): player type = 3
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): constructor
,V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): StagefrightPlayer
V/AwesomePlayer(  301): setListener
V/StagefrightPlayer(  301): initCheck
V/AwesomePlayer(  301): setAudioSink
V/StagefrightPlayer(  301): setDataSource(30, 19266876, 23389)
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a7e0, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
D/Utils   (  301): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  301): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  301): mBitrate = -1 bits/sec
I/OggExtractor(  301): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  301): current audio track index (0) is added to vector
V/AwesomePlayer(  301): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  301): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  301): prepare
V/AwesomePlayer(  301): prepareAsync
V/MediaPlayerService(  301): wait for prepare
,I/UpdateIcingCorporaServi( 1684): UpdateCorporaTask done [took 204 ms] updated apps [took 204 ms] 
,V/AwesomePlayer(  301): onPrepareAsyncEvent
I/SecMediaClock(  301): SecMediaClock constructor
I/SecMediaClock(  301): reset
I/SecVideoCapture(  301): SecVideoCapture constructor
,I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): initAudioDecoder
V/AwesomePlayer(  301): checkOffloadExceptions is true
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  301): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  301): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  301): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  301): finishAsyncPrepare_l
V/AwesomePlayer(  301): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  301): notify(0xb061a7e0, 200, 973, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a7e0, 5, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a7e0, 1, 0, 0)
V/AudioCache(  301): prepared
V/AudioCache(  301): wait - success
V/MediaPlayerService(  301): start
V/StagefrightPlayer(  301): start
V/AwesomePlayer(  301): play
V/AwesomePlayer(  301): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  301): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  301): start of Playback, useOffload 0
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  301): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  301): Audio channels(2)
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  301): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  301): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a7e0, 6, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): addBatteryData
V/MediaPlayerService(  301): wait for playback complete
I/AudioPlayer(  301): First fillBuffer call!!
I/AudioPlayer(  301): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  301): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] End Of Stream
E/Zygote  ( 8126): MountEmulatedStorage()
E/Zygote  ( 8126): v2
I/libpersona( 8126): KNOX_SDCARD checking this for 1000
I/libpersona( 8126): KNOX_SDCARD not a persona
V/AwesomePlayer(  301): postAudioEOS delayUs (0)
V/AwesomePlayer(  301): onCheckAudioStatus
V/AwesomePlayer(  301): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  301): onStreamDone
V/AwesomePlayer(  301): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  301): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a7e0, 2, 0, 0)
V/AudioCache(  301): playback complete - thread will wake up later
V/AwesomePlayer(  301): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a7e0, 7, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  301): addBatteryData
V/AudioCache(  301): wait - success
V/StagefrightPlayer(  301): reset
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a7e0, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
D/AudioPlayer(  301): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop() sendCommand(0x7a, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  301): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  301): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  301): ~OggSource --
I/OggExtractor(  301): ~OggExtractor ++
I/OggExtractor(  301): ~MyVorbisExtractor ++ 
I/OggExtractor(  301): ~MyVorbisExtractor --
I/OggExtractor(  301): ~OggExtractor --
,I/AudioPlayer(  301): reset out
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  301): SecVideoCapture destructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): mSecCapture clear
I/SecMediaClock(  301): SecMediaClock destructor
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): ~StagefrightPlayer
V/StagefrightPlayer(  301): reset
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/AwesomePlayer(  301): destructor
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/MediaPlayer( 7983): decode(41, 19156232, 8154)
,I/ActivityManager(  893): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=8126 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 7033:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,V/MediaPlayerService(  301): decode(30, 19156232, 8154)
I/SELinux ( 8126): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
V/MediaPlayerService(  301): player type = 3
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): constructor
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): StagefrightPlayer
V/AwesomePlayer(  301): setListener
V/StagefrightPlayer(  301): initCheck
V/AwesomePlayer(  301): setAudioSink
V/StagefrightPlayer(  301): setDataSource(30, 19156232, 8154)
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0f0f150, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
D/Utils   (  301): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
I/SELinux ( 8126): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
V/AwesomePlayer(  301): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  301): mBitrate = -1 bits/sec
I/OggExtractor(  301): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  301): current audio track index (0) is added to vector
V/AwesomePlayer(  301): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  301): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  301): prepare
W/libprocessgroup(  893): failed to open /acct/uid_10020/pid_7001/cgroup.procs: No such file or directory
V/AwesomePlayer(  301): prepareAsync
V/MediaPlayerService(  301): wait for prepare
E/SELinux ( 8126): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/AwesomePlayer(  301): onPrepareAsyncEvent
I/SecMediaClock(  301): SecMediaClock constructor
I/SecMediaClock(  301): reset
I/SecVideoCapture(  301): SecVideoCapture constructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): initAudioDecoder
V/AwesomePlayer(  301): checkOffloadExceptions is true
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  301): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  301): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
W/libprocessgroup(  893): failed to open /acct/uid_10003/pid_7013/cgroup.procs: No such file or directory
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  301): finishAsyncPrepare_l
V/AwesomePlayer(  301): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  301): notify(0xb0f0f150, 200, 973, 0)
V/AudioCache(  301): ignored
,V/AwesomePlayer(  301): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0f0f150, 5, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0f0f150, 1, 0, 0)
V/AudioCache(  301): prepared
,V/AudioCache(  301): wait - success
V/MediaPlayerService(  301): start
V/StagefrightPlayer(  301): start
V/AwesomePlayer(  301): play
V/AwesomePlayer(  301): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  301): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  301): start of Playback, useOffload 0
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  301): Audio channels(1)
,I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  301): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  301): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0f0f150, 6, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): addBatteryData
,V/MediaPlayerService(  301): wait for playback complete
I/AudioPlayer(  301): First fillBuffer call!!
,I/AudioPlayer(  301): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  301): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  301): postAudioEOS delayUs (0)
V/AwesomePlayer(  301): onCheckAudioStatus
V/AwesomePlayer(  301): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  301): onStreamDone
V/AwesomePlayer(  301): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  301): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0f0f150, 2, 0, 0)
V/AudioCache(  301): playback complete - thread will wake up later
V/AwesomePlayer(  301): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0f0f150, 7, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  301): addBatteryData
,V/AudioCache(  301): wait - success
V/StagefrightPlayer(  301): reset
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0f0f150, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
D/AudioPlayer(  301): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop() sendCommand(0x7b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  301): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  301): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  301): ~OggSource --
I/OggExtractor(  301): ~OggExtractor ++
I/OggExtractor(  301): ~MyVorbisExtractor ++ 
I/OggExtractor(  301): ~MyVorbisExtractor --
I/OggExtractor(  301): ~OggExtractor --
,I/AudioPlayer(  301): reset out
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  301): SecVideoCapture destructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): mSecCapture clear
I/SecMediaClock(  301): SecMediaClock destructor
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): ~StagefrightPlayer
V/StagefrightPlayer(  301): reset
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/AwesomePlayer(  301): destructor
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/MediaPlayer( 7983): decode(42, 19129712, 4804)
,W/libprocessgroup(  893): failed to open /acct/uid_1000/pid_7033/cgroup.procs: No such file or directory
,V/MediaPlayerService(  301): decode(30, 19129712, 4804)
,V/MediaPlayerService(  301): player type = 3
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): constructor
,V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
,D/TimaKeyStoreProvider( 8126): TimaSignature is unavailable
,V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): StagefrightPlayer
V/AwesomePlayer(  301): setListener
V/StagefrightPlayer(  301): initCheck
,V/AwesomePlayer(  301): setAudioSink
V/StagefrightPlayer(  301): setDataSource(30, 19129712, 4804)
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a650, 8, 0, 0)
V/AudioCache(  301): ignored
,V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
,D/ActivityThread( 8126): Added TimaKeyStore provider
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
D/Utils   (  301): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  301): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  301): mBitrate = -1 bits/sec
,I/OggExtractor(  301): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  301): current audio track index (0) is added to vector
V/AwesomePlayer(  301): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  301): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  301): prepare
V/AwesomePlayer(  301): prepareAsync
,V/MediaPlayerService(  301): wait for prepare
V/AwesomePlayer(  301): onPrepareAsyncEvent
I/SecMediaClock(  301): SecMediaClock constructor
I/SecMediaClock(  301): reset
,I/SecVideoCapture(  301): SecVideoCapture constructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): initAudioDecoder
V/AwesomePlayer(  301): checkOffloadExceptions is true
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  301): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  301): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  301): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  301): finishAsyncPrepare_l
V/AwesomePlayer(  301): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache(  301): notify(0xb061a650, 200, 973, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a650, 5, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache(  301): notify(0xb061a650, 1, 0, 0)
V/AudioCache(  301): prepared
V/AudioCache(  301): wait - success
V/MediaPlayerService(  301): start
V/StagefrightPlayer(  301): start
V/AwesomePlayer(  301): play
,V/AwesomePlayer(  301): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  301): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  301): start of Playback, useOffload 0
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  301): Audio channels(1)
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
,V/AudioCache(  301): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  301): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  301): notify(0xb061a650, 6, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): addBatteryData
V/MediaPlayerService(  301): wait for playback complete
,D/ResourcesManager( 8126): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,I/AudioPlayer(  301): First fillBuffer call!!
,I/AudioPlayer(  301): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  301): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  301): postAudioEOS delayUs (0)
,V/AwesomePlayer(  301): onCheckAudioStatus
,V/AwesomePlayer(  301): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  301): onStreamDone
V/AwesomePlayer(  301): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  301): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a650, 2, 0, 0)
V/AudioCache(  301): playback complete - thread will wake up later
,V/AwesomePlayer(  301): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a650, 7, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  301): addBatteryData
V/AudioCache(  301): wait - success
,V/StagefrightPlayer(  301): reset
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  301): notify(0xb061a650, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
D/AudioPlayer(  301): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  301): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  301): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  301): ~OggSource --
I/OggExtractor(  301): ~OggExtractor ++
,I/OggExtractor(  301): ~MyVorbisExtractor ++ 
I/OggExtractor(  301): ~MyVorbisExtractor --
I/OggExtractor(  301): ~OggExtractor --
,I/AudioPlayer(  301): reset out
,V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  301): SecVideoCapture destructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): mSecCapture clear
I/SecMediaClock(  301): SecMediaClock destructor
V/AwesomePlayer(  301): mSecMediaClock clear
,V/StagefrightPlayer(  301): ~StagefrightPlayer
V/StagefrightPlayer(  301): reset
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
,V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/AwesomePlayer(  301): destructor
,V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
,V/AwesomePlayer(  301): mSecMediaClock clear
,V/MediaPlayer( 7983): decode(43, 19099164, 9400)
V/MediaPlayerService(  301): decode(30, 19099164, 9400)
,V/MediaPlayerService(  301): player type = 3
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): constructor
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): StagefrightPlayer
V/AwesomePlayer(  301): setListener
V/StagefrightPlayer(  301): initCheck
V/AwesomePlayer(  301): setAudioSink
V/StagefrightPlayer(  301): setDataSource(30, 19099164, 9400)
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0a02330, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
D/Utils   (  301): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  301): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  301): mBitrate = -1 bits/sec
I/OggExtractor(  301): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  301): current audio track index (0) is added to vector
V/AwesomePlayer(  301): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  301): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  301): prepare
V/AwesomePlayer(  301): prepareAsync
V/MediaPlayerService(  301): wait for prepare
,V/MediaPlayer( 7983): decode(49, 19172584, 4112)
,V/MediaPlayerService(  301): decode(33, 19172584, 4112)
,V/MediaPlayerService(  301): player type = 3
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): constructor
V/AwesomePlayer(  301): setDefault
,V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): onPrepareAsyncEvent
,V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): StagefrightPlayer
V/AwesomePlayer(  301): setListener
V/StagefrightPlayer(  301): initCheck
V/AwesomePlayer(  301): setAudioSink
V/StagefrightPlayer(  301): setDataSource(33, 19172584, 4112)
,V/AwesomePlayer(  301): reset_l()
I/SecMediaClock(  301): SecMediaClock constructor
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
D/Utils   (  301): printFileName fd(34) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/SecMediaClock(  301): reset
I/SecVideoCapture(  301): SecVideoCapture constructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): initAudioDecoder
V/AwesomePlayer(  301): checkOffloadExceptions is true
,V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AwesomePlayer(  301): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  301): mBitrate = -1 bits/sec
I/OggExtractor(  301): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  301): current audio track index (0) is added to vector
V/AwesomePlayer(  301): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  301): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  301): prepare
V/AwesomePlayer(  301): prepareAsync
V/MediaPlayerService(  301): wait for prepare
V/AwesomePlayer(  301): onPrepareAsyncEvent
I/SecMediaClock(  301): SecMediaClock constructor
I/SecMediaClock(  301): reset
I/SecVideoCapture(  301): SecVideoCapture constructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): initAudioDecoder
V/AwesomePlayer(  301): checkOffloadExceptions is true
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  301): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  301): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  301): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  301): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  301): finishAsyncPrepare_l
V/AwesomePlayer(  301): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 200, 973, 0)
V/AudioCache(  301): ignored
,V/AwesomePlayer(  301): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 5, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 1, 0, 0)
V/AudioCache(  301): prepared
V/AudioCache(  301): wait - success
V/MediaPlayerService(  301): start
,V/StagefrightPlayer(  301): start
V/AwesomePlayer(  301): play
V/AwesomePlayer(  301): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  301): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  301): start of Playback, useOffload 0
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  301): finishAsyncPrepare_l
,V/AwesomePlayer(  301): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  301): notify(0xb0a02330, 200, 973, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0a02330, 5, 0, 0)
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] End Of Stream
V/AudioCache(  301): ignored
I/OMXCodec(  301): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  301): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/AwesomePlayer(  301): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache(  301): notify(0xb0a02330, 1, 0, 0)
V/AudioCache(  301): prepared
I/AudioPlayer(  301): Audio channels(1)
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  301): open(44100, 1, 0x0, 1, 0)
V/AudioCache(  301): wait - success
V/AwesomePlayer(  301): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 6, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): addBatteryData
V/MediaPlayerService(  301): wait for playback complete
,V/MediaPlayerService(  301): start
V/StagefrightPlayer(  301): start
V/AwesomePlayer(  301): play
V/AwesomePlayer(  301): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  301): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  301): start of Playback, useOffload 0
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  301): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  301): Audio channels(1)
,I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
I/AudioPlayer(  301): First fillBuffer call!!
I/AudioPlayer(  301): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  301): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  301): postAudioEOS delayUs (0)
V/AwesomePlayer(  301): onCheckAudioStatus
V/AwesomePlayer(  301): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  301): onStreamDone
V/AwesomePlayer(  301): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  301): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 2, 0, 0)
V/AudioCache(  301): playback complete - thread will wake up later
V/AwesomePlayer(  301): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 7, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  301): addBatteryData
V/AudioCache(  301): wait - success
V/StagefrightPlayer(  301): reset
,V/AudioCache(  301): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
D/AudioPlayer(  301): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  301): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0a02330, 6, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): addBatteryData
V/MediaPlayerService(  301): wait for playback complete
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  301): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  301): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  301): ~OggSource --
I/OggExtractor(  301): ~OggExtractor ++
I/OggExtractor(  301): ~MyVorbisExtractor ++ 
I/OggExtractor(  301): ~MyVorbisExtractor --
I/OggExtractor(  301): ~OggExtractor --
,I/AudioPlayer(  301): First fillBuffer call!!
,I/AudioPlayer(  301): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  301): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
,I/AudioPlayer(  301): reset out
,V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  301): SecVideoCapture destructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): mSecCapture clear
,I/SecMediaClock(  301): SecMediaClock destructor
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): ~StagefrightPlayer
V/StagefrightPlayer(  301): reset
,V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/AwesomePlayer(  301): destructor
,V/AwesomePlayer(  301): reset_l()
,V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  301): postAudioEOS delayUs (0)
,V/AwesomePlayer(  301): onCheckAudioStatus
V/AwesomePlayer(  301): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  301): onStreamDone
V/AwesomePlayer(  301): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  301): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0a02330, 2, 0, 0)
V/AudioCache(  301): playback complete - thread will wake up later
V/AwesomePlayer(  301): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0a02330, 7, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  301): addBatteryData
V/AudioCache(  301): wait - success
V/StagefrightPlayer(  301): reset
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0a02330, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
D/AudioPlayer(  301): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop() sendCommand(0x7e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  301): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  301): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  301): ~OggSource --
I/OggExtractor(  301): ~OggExtractor ++
I/OggExtractor(  301): ~MyVorbisExtractor ++ 
I/OggExtractor(  301): ~MyVorbisExtractor --
I/OggExtractor(  301): ~OggExtractor --
,I/AudioPlayer(  301): reset out
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  301): SecVideoCapture destructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): mSecCapture clear
I/SecMediaClock(  301): SecMediaClock destructor
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): ~StagefrightPlayer
V/StagefrightPlayer(  301): reset
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/AwesomePlayer(  301): destructor
,V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
,V/MediaPlayer( 7983): decode(44, 19307764, 52024)
V/MediaPlayerService(  301): decode(30, 19307764, 52024)
,V/MediaPlayerService(  301): player type = 3
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): constructor
,V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): StagefrightPlayer
V/AwesomePlayer(  301): setListener
V/StagefrightPlayer(  301): initCheck
V/AwesomePlayer(  301): setAudioSink
V/StagefrightPlayer(  301): setDataSource(30, 19307764, 52024)
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a7e0, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
D/Utils   (  301): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  301): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  301): mBitrate = -1 bits/sec
I/OggExtractor(  301): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  301): current audio track index (0) is added to vector
V/AwesomePlayer(  301): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  301): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  301): prepare
V/AwesomePlayer(  301): prepareAsync
V/MediaPlayerService(  301): wait for prepare
V/AwesomePlayer(  301): onPrepareAsyncEvent
I/SecMediaClock(  301): SecMediaClock constructor
I/SecMediaClock(  301): reset
I/SecVideoCapture(  301): SecVideoCapture constructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): initAudioDecoder
V/AwesomePlayer(  301): checkOffloadExceptions is true
V/AudioPolicyManager(  301): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  301): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  301): >>>UHQA initOutputFormat 16
,I/AwesomePlayer(  301): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  301): finishAsyncPrepare_l
V/AwesomePlayer(  301): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  301): notify(0xb061a7e0, 200, 973, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a7e0, 5, 0, 0)
,V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a7e0, 1, 0, 0)
V/AudioCache(  301): prepared
V/AudioCache(  301): wait - success
V/MediaPlayerService(  301): start
,V/StagefrightPlayer(  301): start
V/AwesomePlayer(  301): play
V/AwesomePlayer(  301): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  301): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  301): start of Playback, useOffload 0
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  301): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  301): Audio channels(2)
,I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  301): open(48000, 2, 0x0, 1, 0)
V/AwesomePlayer(  301): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  301): notify(0xb061a7e0, 6, 0, 0)
V/AudioCache(  301): ignored
I/AudioPlayer(  301): First fillBuffer call!!
V/AwesomePlayer(  301): addBatteryData
V/MediaPlayerService(  301): wait for playback complete
,I/SecureStorage(  365): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
I/SecureStorage(  365): [INFO]: SPID(0x00000005)PID: 8009, TID: 8027
,I/jxcore-log( 7489): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7489): 
,I/jxcore-log( 7489): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7489): 
,D/ShortcutReceiver( 8126):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/ConnectivityService(  893): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  893): MasterInitialState.processMessage what=3
D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  893): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  893): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  893): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  893): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  893): getSBEnabled() enabled =false
D/SmartBondingService(  893): getSBEnabled() enabled =false
D/SmartBondingService(  893): getSBEnabled() enabled =false
I/CLocInfoService(  893): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  893): CLocinfo wifi true 
D/SmartBondingService(  893): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] End Of Stream
,D/accuweather( 2107): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,V/AwesomePlayer(  301): postAudioEOS delayUs (0)
V/AwesomePlayer(  301): onCheckAudioStatus
V/AwesomePlayer(  301): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  301): onStreamDone
V/AwesomePlayer(  301): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  301): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a7e0, 2, 0, 0)
V/AudioCache(  301): playback complete - thread will wake up later
V/AwesomePlayer(  301): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a7e0, 7, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  301): addBatteryData
V/AudioCache(  301): wait - success
V/StagefrightPlayer(  301): reset
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3834): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 3834): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,W/ContextImpl( 2218): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2218): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a7e0, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
D/AudioPlayer(  301): reset: mPlaying=0 mReachedEOS=1 useOffload=0
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop mState=4
D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop() sendCommand(0x7f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor(  301): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  301): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  301): ~OggSource --
I/SystemBroadcastReceiver( 7191): [#DCM#] [DCM_Performance] onReceive completed in time  223 microsec. 
I/OggExtractor(  301): ~OggExtractor ++
I/OggExtractor(  301): ~MyVorbisExtractor ++ 
I/OggExtractor(  301): ~MyVorbisExtractor --
,I/OggExtractor(  301): ~OggExtractor --
,I/AudioPlayer(  301): reset out
,V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  301): SecVideoCapture destructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): mSecCapture clear
I/SecMediaClock(  301): SecMediaClock destructor
V/AwesomePlayer(  301): mSecMediaClock clear
,V/StagefrightPlayer(  301): ~StagefrightPlayer
V/StagefrightPlayer(  301): reset
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
,V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/AwesomePlayer(  301): destructor
,V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7191): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7191): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7191): [#DCM#] setIsConnectedForExtractors 
,V/MediaPlayer( 7983): decode(45, 19172584, 4112)
,V/MediaPlayerService(  301): decode(30, 19172584, 4112)
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/MediaPlayerService(  301): player type = 3
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): constructor
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): StagefrightPlayer
V/AwesomePlayer(  301): setListener
V/StagefrightPlayer(  301): initCheck
V/AwesomePlayer(  301): setAudioSink
V/StagefrightPlayer(  301): setDataSource(30, 19172584, 4112)
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0f0f150, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
D/Utils   (  301): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  301): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  301): mBitrate = -1 bits/sec
I/OggExtractor(  301): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  301): current audio track index (0) is added to vector
V/AwesomePlayer(  301): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  301): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  301): prepare
V/AwesomePlayer(  301): prepareAsync
V/MediaPlayerService(  301): wait for prepare
,V/AwesomePlayer(  301): onPrepareAsyncEvent
I/SecMediaClock(  301): SecMediaClock constructor
I/SecMediaClock(  301): reset
I/SecVideoCapture(  301): SecVideoCapture constructor
I/SecVideoCapture(  301): reset
,V/AwesomePlayer(  301): initAudioDecoder
V/AwesomePlayer(  301): checkOffloadExceptions is true
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  301): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  301): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/NetworkMonitor( 5388): type=WIFI subType= reason=null isConnected=true
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  301): finishAsyncPrepare_l
V/AwesomePlayer(  301): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  301): notify(0xb0f0f150, 200, 973, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache(  301): notify(0xb0f0f150, 5, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0f0f150, 1, 0, 0)
V/AudioCache(  301): prepared
V/AudioCache(  301): wait - success
V/MediaPlayerService(  301): start
V/StagefrightPlayer(  301): start
V/AwesomePlayer(  301): play
V/AwesomePlayer(  301): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  301): startAudioPlayer_l, sendErrorNotification (0)
D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/AudioPlayer(  301): start of Playback, useOffload 0
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  301): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  301): Audio channels(1)
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  301): open(44100, 1, 0x0, 1, 0)
,I/DatabaseRebuilderTask( 7191): [#DCM#] postDBrebuildIntent rebuildLocation =  true
,V/AwesomePlayer(  301): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0f0f150, 6, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): addBatteryData
V/MediaPlayerService(  301): wait for playback complete
I/AudioPlayer(  301): First fillBuffer call!!
I/AudioPlayer(  301): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  301): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  301): postAudioEOS delayUs (0)
V/AwesomePlayer(  301): onCheckAudioStatus
V/AwesomePlayer(  301): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  301): onStreamDone
V/AwesomePlayer(  301): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  301): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0f0f150, 2, 0, 0)
V/AudioCache(  301): playback complete - thread will wake up later
V/AwesomePlayer(  301): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0f0f150, 7, 0, 0)
D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  301): addBatteryData
V/AudioCache(  301): wait - success
V/StagefrightPlayer(  301): reset
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0f0f150, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
D/AudioPlayer(  301): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  301): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  301): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  301): ~OggSource --
I/OggExtractor(  301): ~OggExtractor ++
I/OggExtractor(  301): ~MyVorbisExtractor ++ 
I/OggExtractor(  301): ~MyVorbisExtractor --
I/OggExtractor(  301): ~OggExtractor --
,I/AudioPlayer(  301): reset out
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  301): SecVideoCapture destructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): mSecCapture clear
I/SecMediaClock(  301): SecMediaClock destructor
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): ~StagefrightPlayer
V/StagefrightPlayer(  301): reset
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/AwesomePlayer(  301): destructor
,V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
,V/MediaPlayer( 7983): decode(46, 19235660, 21825)
V/MediaPlayerService(  301): decode(30, 19235660, 21825)
,V/MediaPlayerService(  301): player type = 3
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): constructor
V/AwesomePlayer(  301): setDefault
,V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): StagefrightPlayer
V/AwesomePlayer(  301): setListener
V/StagefrightPlayer(  301): initCheck
V/AwesomePlayer(  301): setAudioSink
V/StagefrightPlayer(  301): setDataSource(30, 19235660, 21825)
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a650, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
D/Utils   (  301): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
I/jxcore-log( 7489): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7489): 
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/AwesomePlayer(  301): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  301): mBitrate = -1 bits/sec
I/OggExtractor(  301): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  301): current audio track index (0) is added to vector
V/AwesomePlayer(  301): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  301): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  301): prepare
V/AwesomePlayer(  301): prepareAsync
V/MediaPlayerService(  301): wait for prepare
V/AwesomePlayer(  301): onPrepareAsyncEvent
I/SecMediaClock(  301): SecMediaClock constructor
I/SecMediaClock(  301): reset
I/SecVideoCapture(  301): SecVideoCapture constructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): initAudioDecoder
V/AwesomePlayer(  301): checkOffloadExceptions is true
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  301): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  301): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  301): finishAsyncPrepare_l
V/AwesomePlayer(  301): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  301): notify(0xb061a650, 200, 973, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a650, 5, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a650, 1, 0, 0)
V/AudioCache(  301): prepared
V/AudioCache(  301): wait - success
V/MediaPlayerService(  301): start
V/StagefrightPlayer(  301): start
V/AwesomePlayer(  301): play
V/AwesomePlayer(  301): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  301): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  301): start of Playback, useOffload 0
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  301): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AudioPlayer(  301): Audio channels(2)
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  301): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  301): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a650, 6, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): addBatteryData
,I/AudioPlayer(  301): First fillBuffer call!!
I/AudioPlayer(  301): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  301): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,V/MediaPlayerService(  301): wait for playback complete
,I/ActivityManager(  893): Killing 7056:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,D/SecContentProvider2(  893): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  893): mCursor = null
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  301): postAudioEOS delayUs (0)
,V/AwesomePlayer(  301): onCheckAudioStatus
V/AwesomePlayer(  301): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  301): onStreamDone
V/AwesomePlayer(  301): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  301): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a650, 2, 0, 0)
V/AudioCache(  301): playback complete - thread will wake up later
V/AwesomePlayer(  301): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a650, 7, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  301): addBatteryData
V/AudioCache(  301): wait - success
V/StagefrightPlayer(  301): reset
,V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb061a650, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
D/AudioPlayer(  301): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  301): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  301): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  301): ~OggSource --
I/OggExtractor(  301): ~OggExtractor ++
I/OggExtractor(  301): ~MyVorbisExtractor ++ 
I/OggExtractor(  301): ~MyVorbisExtractor --
I/OggExtractor(  301): ~OggExtractor --
,I/AudioPlayer(  301): reset out
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  301): SecVideoCapture destructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): mSecCapture clear
I/SecMediaClock(  301): SecMediaClock destructor
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): ~StagefrightPlayer
V/StagefrightPlayer(  301): reset
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/AwesomePlayer(  301): destructor
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/MediaPlayer( 7983): decode(47, 19134596, 21552)
V/MediaPlayerService(  301): decode(30, 19134596, 21552)
,V/MediaPlayerService(  301): player type = 3
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): constructor
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): StagefrightPlayer
V/AwesomePlayer(  301): setListener
V/StagefrightPlayer(  301): initCheck
V/AwesomePlayer(  301): setAudioSink
V/StagefrightPlayer(  301): setDataSource(30, 19134596, 21552)
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
D/Utils   (  301): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  301): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  301): mBitrate = -1 bits/sec
I/OggExtractor(  301): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  301): current audio track index (0) is added to vector
V/AwesomePlayer(  301): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  301): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  301): prepare
V/AwesomePlayer(  301): prepareAsync
V/MediaPlayerService(  301): wait for prepare
V/AwesomePlayer(  301): onPrepareAsyncEvent
I/SecMediaClock(  301): SecMediaClock constructor
I/SecMediaClock(  301): reset
I/SecVideoCapture(  301): SecVideoCapture constructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): initAudioDecoder
V/AwesomePlayer(  301): checkOffloadExceptions is true
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  301): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  301): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/FrameworkService( 7191): [#DCM#] onCreate FrameworkService 
,I/FrameworkService( 7191): [#DCM#] onCreate FrameworkService end 
I/DCMConfig( 7191): [#DCM#] getSuccessState = true
,I/FrameworkService( 7191): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
I/IntentHandler( 7191): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,I/jxcore-log( 7489): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7489): 
V/AwesomePlayer(  301): finishAsyncPrepare_l
V/AwesomePlayer(  301): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 200, 973, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 5, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 1, 0, 0)
V/AudioCache(  301): prepared
V/AudioCache(  301): wait - success
V/MediaPlayerService(  301): start
V/StagefrightPlayer(  301): start
V/AwesomePlayer(  301): play
V/AwesomePlayer(  301): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  301): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  301): start of Playback, useOffload 0
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  301): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/PackageBroadcastService( 2482): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
I/AudioPlayer(  301): Audio channels(2)
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  301): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  301): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 6, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): addBatteryData
V/MediaPlayerService(  301): wait for playback complete
I/AudioPlayer(  301): First fillBuffer call!!
I/AudioPlayer(  301): >>> setAudioEffect Read mAudioFormat : 1, event : 4292761, value : -2137358184
E/AudioPlayer(  301): >>> setAudioEffect Error mAudioFormat : 1, event : 4292761, value : -2137358184
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/X       (  893): broadcastSiopLevelIntent:: currentSiopLevel = -1
,I/SystemUtils( 7191): [#DCM#] LM: false,AM:614858752
,W/libprocessgroup(  893): failed to open /acct/uid_10112/pid_7056/cgroup.procs: No such file or directory
,I/jxcore-log( 7489): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7489): 
,I/jxcore-log( 7489): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7489): 
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  301): postAudioEOS delayUs (0)
,I/PeopleContactsSync( 2482): CP2 sync disabled
,V/AwesomePlayer(  301): onCheckAudioStatus
V/AwesomePlayer(  301): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  301): onStreamDone
V/AwesomePlayer(  301): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  301): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 2, 0, 0)
V/AudioCache(  301): playback complete - thread will wake up later
V/AwesomePlayer(  301): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 7, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  301): addBatteryData
V/AudioCache(  301): wait - success
V/StagefrightPlayer(  301): reset
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0d14060, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
D/AudioPlayer(  301): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  301): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  301): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  301): ~OggSource --
I/OggExtractor(  301): ~OggExtractor ++
I/OggExtractor(  301): ~MyVorbisExtractor ++ 
I/OggExtractor(  301): ~MyVorbisExtractor --
I/OggExtractor(  301): ~OggExtractor --
,I/AudioPlayer(  301): reset out
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  301): SecVideoCapture destructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): mSecCapture clear
I/SecMediaClock(  301): SecMediaClock destructor
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): ~StagefrightPlayer
V/StagefrightPlayer(  301): reset
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/AwesomePlayer(  301): destructor
,D/ContentApp( 1223):  LEVEL : -1
,V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
,V/MediaPlayer( 7983): decode(48, 19228560, 7017)
V/MediaPlayerService(  301): decode(30, 19228560, 7017)
V/MediaPlayerService(  301): player type = 3
V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): constructor
,V/AwesomePlayer(  301): setDefault
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): StagefrightPlayer
V/AwesomePlayer(  301): setListener
V/StagefrightPlayer(  301): initCheck
V/AwesomePlayer(  301): setAudioSink
V/StagefrightPlayer(  301): setDataSource(30, 19228560, 7017)
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0a02330, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
D/Utils   (  301): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  301): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  301): mBitrate = -1 bits/sec
I/OggExtractor(  301): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  301): current audio track index (0) is added to vector
V/AwesomePlayer(  301): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  301): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  301): prepare
V/AwesomePlayer(  301): prepareAsync
V/MediaPlayerService(  301): wait for prepare
,V/AwesomePlayer(  301): onPrepareAsyncEvent
I/DCMThreadPoolExecutor( 7191): [#DCM#] Task being added DatabaseRebuilderTask
I/SecMediaClock(  301): SecMediaClock constructor
I/SecMediaClock(  301): reset
I/DCMThreadPoolExecutor( 7191): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@34cdcbfe is submitted
I/FrameworkService( 7191): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 41732 mirosec. 
I/SecVideoCapture(  301): SecVideoCapture constructor
,I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): initAudioDecoder
V/AwesomePlayer(  301): checkOffloadExceptions is true
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/SystemBroadcastReceiver( 7191): [#DCM#] [DCM_Performance] onReceive completed in time  68 microsec. 
I/SystemBroadcastReceiver( 7191): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7191): [#DCM#] onReceive action = EVENT_SIOP
,I/OMXCodec(  301): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  301): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  301): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  301): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  301): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  301): finishAsyncPrepare_l
V/AwesomePlayer(  301): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  301): notify(0xb0a02330, 200, 973, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0a02330, 5, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0a02330, 1, 0, 0)
V/AudioCache(  301): prepared
V/AudioCache(  301): wait - success
V/MediaPlayerService(  301): start
V/StagefrightPlayer(  301): start
V/AwesomePlayer(  301): play
V/AwesomePlayer(  301): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  301): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  301): start of Playback, useOffload 0
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  301): >>>UHQA initOutputFormat 16
I/OMXCodec(  301): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  301): Audio channels(2)
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  301): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  301): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  301): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0a02330, 6, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): addBatteryData
V/MediaPlayerService(  301): wait for playback complete
,I/AudioPlayer(  301): First fillBuffer call!!
I/AudioPlayer(  301): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  301): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/OMXCodec(  301): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  301): postAudioEOS delayUs (0)
,V/AwesomePlayer(  301): onCheckAudioStatus
V/AwesomePlayer(  301): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  301): onStreamDone
V/AwesomePlayer(  301): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  301): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0a02330, 2, 0, 0)
V/AudioCache(  301): playback complete - thread will wake up later
V/AwesomePlayer(  301): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0a02330, 7, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  301): addBatteryData
V/AudioCache(  301): wait - success
V/StagefrightPlayer(  301): reset
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  301): notify(0xb0a02330, 8, 0, 0)
V/AudioCache(  301): ignored
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
D/AudioPlayer(  301): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  301): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  301): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  301): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  301): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  301): ~OggSource --
I/OggExtractor(  301): ~OggExtractor ++
I/OggExtractor(  301): ~MyVorbisExtractor ++ 
I/OggExtractor(  301): ~MyVorbisExtractor --
I/OggExtractor(  301): ~OggExtractor --
,I/AudioPlayer(  301): reset out
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  301): SecVideoCapture destructor
I/SecVideoCapture(  301): reset
V/AwesomePlayer(  301): mSecCapture clear
I/SecMediaClock(  301): SecMediaClock destructor
V/AwesomePlayer(  301): mSecMediaClock clear
V/StagefrightPlayer(  301): ~StagefrightPlayer
V/StagefrightPlayer(  301): reset
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
V/AwesomePlayer(  301): destructor
V/AwesomePlayer(  301): reset_l()
V/AwesomePlayer(  301): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  301): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  301): mAudioTrackVector clear
V/AwesomePlayer(  301): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  301): mSecCapture clear
V/AwesomePlayer(  301): mSecMediaClock clear
,I/Hs20UtilService( 1300): Starting #9
,I/Hs20UtilService( 1300): Message received 5007
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1300): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1300): Starting #10
,I/Hs20UtilService( 1300): Message received 5007
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1300): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1300): Starting #11
,I/Hs20UtilService( 1300): Message received 5007
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1300): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  893): callSECApi what=220
D/WifiStateMachine(  893): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 6806): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6806): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6806): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6806): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7690): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7690): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PowerManagerService(  893): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=893
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/SecureStorage( 8009): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 8009): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
,I/SecSQLiteOpenHelper( 7983): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper( 7983): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper( 7983): Open platform.db in secure mode
,D/SecSQLiteDatabase( 7983): Android Version: 5.0
,D/SecSQLiteDatabase( 7983): Load library secsqlite.so for Android 5.0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/SecSQLiteDatabase( 7983): openSecureDatabase...
I/SecSQLiteDatabase( 7983): private openSecureDatabase...
I/SecSQLiteConnectionPool( 7983): OpenSecure
I/SecSQLiteConnectionPool( 7983): OpenSecure with password
I/SecSQLiteConnectionPool( 7983): openSecureConnectionLocked
,I/SecSQLiteDatabase( 7983): ...private openSecureDatabase
I/SecSQLiteDatabase( 7983): ...openSecureDatabase
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/FOTA_Client( 7709): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/FOTA_Client( 7709): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7709): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7709): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7709): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
I/KLMS-2.4.503: ( 7730): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7730): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453202000077
,I/KLMS-2.4.503: ( 7730): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7730): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7730): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7730): NetworkChangeOperations(): uploadRequestLog().START 
,I/SecSQLiteOpenHelper( 7983): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper( 7983): ...getDatabaseLocked(b,b,pwd)
,I/KLMS-2.4.503: ( 7730): StateImplV2(): networkChangeListener().END
,W/System.err( 7983): java.lang.NumberFormatException: Invalid int: "null"
,W/System.err( 7983): 	at java.lang.Integer.invalidInt(Integer.java:138)
W/System.err( 7983): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err( 7983): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err( 7983): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:449)
W/System.err( 7983): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1173)
W/System.err( 7983): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7983): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7983): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SO_AGENT( 7745): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5141): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6846): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6846): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6846): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6846): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6846): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6846): [SCU] == networkStateCheck == true
,I/SA      ( 6846): [DM] getCountryCodeFromCSC : DE
I/SA      ( 6846): isChinaCountryCode : false
I/SA      ( 6846): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6846): [OR] == networkStateCheck true ==
,I/SA      ( 6846): [OR] GetMyCountryZoneTask
,I/SA      ( 6846): [OR] onReceive END
,I/SA      ( 6846): [SRS] prepareGetMyCountryZone
,I/SA      ( 6846): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6846): [SSP] query invoked
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 7769): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7769): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro( 7787): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7787): premStatus:2
,I/SA      ( 6846): [TPMU] GetMccFromDB : null
,I/SA      ( 6846): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6846): [TPM] isNoProxy(default) : true
,I/KnoxUsageLogPro( 7787): isEulaShown : false
I/KnoxUsageLogPro( 7787): KnoxUsageReceiver onReceive : not Processible, just return
,E/File    ( 6846): fail readDirectory() errno=2
,D/Headlines( 5535): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5535): getCountryCode(): countryCode = DE
,D/Headlines( 5535): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5535): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5535): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5535): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5535): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5535): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5535): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7882): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7882): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7882): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  893): exchangeData() failure , invalid userId
D/RCPManagerService(  893): exchangeData() failure , invalid userId
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7595): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7595): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7595): StateMachine : Current State = 1
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7595): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 5638): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5638): 
D/com.peel.receiver.ConnectivityActionReceiver( 5638): 
D/com.peel.receiver.ConnectivityActionReceiver( 5638): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5638): 
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5638): 
D/com.peel.receiver.ConnectivityActionReceiver( 5638): 
D/com.peel.receiver.ConnectivityActionReceiver( 5638):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5638): 
D/com.peel.receiver.ConnectivityActionReceiver( 5638): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5638): 
D/com.peel.receiver.ConnectivityActionReceiver( 5638): 
D/com.peel.receiver.ConnectivityActionReceiver( 5638): last run: 1453190654528 -- System.currentTimeMillis()-last_run: 11345712
D/com.peel.receiver.ConnectivityActionReceiver( 5638): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5638): ... skip last_72_check
,D/ConnectivityService(  893): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/iu.Environment( 2482): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2482): num queued entries: 0
,I/iu.UploadsManager( 2482): num updated entries: 0
,I/iu.SyncManager( 2482): NEXT; no task
,D/ChimeraCfgMgr( 2482): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2482): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1817): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1817): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1817): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1817): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/WaitQueueForNetworkActivate( 7167): notifyNetworkActivated
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  893): uri = 14 selection = getSealedState
D/SecContentProvider2(  893): mCursor = null
D/SecContentProvider2(  893): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  893): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  893): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2482): [AccountUtils] Account not ready
W/Kids    ( 2482): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2482): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2482): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2482): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2482): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2482): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2482): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2482): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2482): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2482): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2482): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2482): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/ContextImpl( 7167): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  893): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/dhcpcd  ( 7760): wlan0: sending IPv6 Router Solicitation
,D/GCM     ( 1817): Connected
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1817): Message class com.google.f.a.a.p
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,D/hcjo    ( 7167): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7167): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7167): exit::IDLE
,D/InitializeManagerStateMachine( 7167): entry::NETWORK_CHECK
,E/Zygote  ( 8204): MountEmulatedStorage()
I/libpersona( 8204): KNOX_SDCARD checking this for 10054
E/Zygote  ( 8204): v2
I/libpersona( 8204): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=8204 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  337): Explicit concurrent mark sweep GC freed 8717(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 292us total 15.785ms
,I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 7.850ms
,I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 7.914ms
,I/SELinux ( 8204): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7167): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7167): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7167): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7167): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7167): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7167): entry::SUCCESS
D/hcjo    ( 7167): AutoUpdateManager:INITCHECK:onInitializeSuccess
I/SELinux ( 8204): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8204): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/hcjo    ( 7167): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7167): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7167): exit::SUCCESS
D/InitializeManagerStateMachine( 7167): entry::IDLE
,D/TimaKeyStoreProvider( 8204): TimaSignature is unavailable
D/ActivityThread( 8204): Added TimaKeyStore provider
,D/ResourcesManager( 8204): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8204): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8204): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/TranscodeReceiver( 8204): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 8204): core_num = 4
,W/linker  ( 8204): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 8204): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 8204): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
,D/videowall-Global( 8204): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 8204):  SIOP_LEVEL: -1
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7983): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/SA      ( 6846): [RC New] Execute method=[GET] start
,I/SA      ( 6846): [RC New] Security=[true]
,I/System.out( 6846): Thread-1125(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6846): Thread-1125(ApacheHTTPLog):isShipBuild true
,I/System.out( 6846): Thread-1125(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/SA      ( 6846): [RC New] [v2liruge] api execute + 652
,I/SA      ( 6846): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6846): AsyncTask #1 calls detatch()
,I/SA      ( 6846): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6846): [OCP] update openData : PL
,I/SA      ( 6846): [TPMU] getNetworkMcc : 
,I/SA      ( 6846): [SCU] saveMccToPreferece Start
I/SA      ( 6846): [SCU] RegionMCC : 260
I/SA      ( 6846): [SSP] query invoked
,I/SA      ( 6846): [TPMU] GetMccFromDB : null
I/SA      ( 6846): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6846): [SCU] saveMccToPreferece End
,I/SA      ( 6846): [RC New] executeRequest [v2liruge] end. 709
I/SA      ( 6846): [RC New] Execute end
I/SA      ( 6846): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6846): [OR] GetMyCountryZoneTask Success
,I/GAV4    ( 7821): Thread[GAThread,5,main]: No campaign data found.
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,I/WifiStateMachine(  893): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  893): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/jxcore-log( 7489): Test app app.js loaded
I/jxcore-log( 7489): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7489): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7489): BLE advertisement is supported
I/jxcore-log( 7489): 
,I/chromium( 7489): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/SurfaceFlinger(  249): id=16 Removed Toast (8/9)
,I/SurfaceFlinger(  249): id=16 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/PowerManagerService(  893): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 893) eventTime = 113835
,D/PowerManagerService(  893): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=893 (0x0)
,D/PowerManagerService(  893): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=893, ws=WorkSource{10059}) (elapsedTime=3529)
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/GAV3    ( 7983): Thread[GAThread,5,main]: No campaign data found.
,I/dhcpcd  ( 7760): wlan0: sending IPv6 Router Solicitation
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6806): mConnectivityHandler : connected,
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6806): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 6806): ================================================
,I/CSTORAGE( 6806):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
,I/CSTORAGE( 6806): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6806): [GetString-S]
,E/art     ( 6806): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6806): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6806): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6806): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6806): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6806): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6806): [ensureRegistration] - No Samsung account
,E/SMD     (  289): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 1
,V/AlarmManager(  893): waitForAlarm result :4
,D/FactoryTest( 6731): Not factory mode
,D/FactoryTest( 6731): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6731): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6731): still no open session command from host, so toast
,E/SMD     (  289): DCD ON
,W/ContextImpl( 6731): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6731): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6731): Timeline: Activity_launch_request id:com.android.settings time:118487
,E/PersonaManagerService(  893): inState():  stateMachine is null !!
,V/ApplicationPolicy(  893): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  893): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  893): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/MTPRx   ( 6731): started activity for popup
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SQLiteSecureOpenHelper( 3549): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3549): getDatabaseLocked(b,b,pwd)...
,V/AlarmManager(  893): waitForAlarm result :4
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6731): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6731): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6731): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6731): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6731): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6731): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6731): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6731): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6731): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/InputMethodManagerService(  893): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  893): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1ee87dc0 attribute=null, token = android.os.BinderProxy@e836395
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6731): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6731): dev.kiessupport is : TRUE
,D/Activity( 6731): performCreate Call secproduct feature valuefalse
D/Activity( 6731): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ActivityManager(  893): post active user change for 0
,D/KnoxTimeoutHandler(  893): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  893): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/dhcpcd  ( 7760): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 7760): wlan0: no IPv6 Routers available
,I/Timeline( 7489): Timeline: Activity_idle id: android.os.BinderProxy@3ed7f34e time:118781
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1817): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1817): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1817): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1817): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6615): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6615): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6615): [1] 5.onFinished: Scheduling replication attempt 3.
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  893): waitForAlarm result :4
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  893): stay LED for fully charged
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
I/MotionRecognitionService(  893): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,I/PowerManagerService(  893): [PWL] Off : 30s ago
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  893): SIOP:: AP = 390, PST = 409, CUR = 300
,D/PreloadUpdateManagerStateMachine( 7167): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7167): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7167): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7167): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7167): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7167): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7167): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7167): entry::IDLE
,E/SMD     (  289): DCD ON
,W/ActivityManager(  893): mDVFSHelper.release()
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ActivityManager(  893): Waited long enough for: ServiceRecord{3b4d4192 u0 com.samsung.dcm/.framework.FrameworkService}
,I/ActivityManager(  893): Waited long enough for: ServiceRecord{273b70ea u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:m  (  893): SIOP:: AP = 340, PST = 395, CUR = 300
,E/SMD     (  289): DCD ON
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,E/Watchdog(  893): !@Sync 4
,E/SMD     (  289): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...,
,V/AlarmManager(  893): waitForAlarm result :4
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  893): stay LED for fully charged
D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  893): [PWL] Off : 50s ago
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 330, PST = 379, CUR = 300
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1817): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1817): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1817): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1817): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6615): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6615): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6615): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 320, PST = 366, CUR = 300
,V/AlarmManager(  893): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,V/AlarmManager(  893): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): stay LED for fully charged
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1817): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1817): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1817): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1817): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  893): uri = 14 selection = getSealedState
D/SecContentProvider2(  893): mCursor = null
,D/SecContentProvider2(  893): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  893): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  893): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6586): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6586): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6586): 	at kfv.a(PG:65)
E/HttpOperation( 6586): 	at kff.u(PG:385)
E/HttpOperation( 6586): 	at kfb.a(PG:29)
E/HttpOperation( 6586): 	at kff.l(PG:132)
E/HttpOperation( 6586): 	at dsf.a(PG:807)
E/HttpOperation( 6586): 	at fhk.a(PG:1126)
E/HttpOperation( 6586): 	at fhk.a(PG:908)
E/HttpOperation( 6586): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6586): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6586): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6586): 	at ihi.a(PG:22)
E/HttpOperation( 6586): 	at kft.a(PG:91)
E/HttpOperation( 6586): 	at kfv.a(PG:62)
E/HttpOperation( 6586): 	... 8 more
E/HttpOperation( 6586): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6586): 	at gde.c(Unknown Source)
E/HttpOperation( 6586): 	at gde.b(Unknown Source)
E/HttpOperation( 6586): 	at ihi.a(PG:19)
E/HttpOperation( 6586): 	... 10 more
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,I/GLSUser ( 1817): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1817): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1817): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1817): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  893): uri = 14 selection = getSealedState
D/SecContentProvider2(  893): mCursor = null
,D/SecContentProvider2(  893): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  893): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  893): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6586): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6586): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6586): 	at kfv.a(PG:65)
E/HttpOperation( 6586): 	at kff.u(PG:385)
E/HttpOperation( 6586): 	at kfb.a(PG:29)
E/HttpOperation( 6586): 	at kff.l(PG:132)
E/HttpOperation( 6586): 	at ieo.a(PG:43)
E/HttpOperation( 6586): 	at iep.a(PG:93)
E/HttpOperation( 6586): 	at fhn.a(PG:59)
E/HttpOperation( 6586): 	at lex.a(PG:85)
E/HttpOperation( 6586): 	at lex.b(PG:132)
E/HttpOperation( 6586): 	at fhk.a(PG:1146)
E/HttpOperation( 6586): 	at fhk.a(PG:908)
E/HttpOperation( 6586): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6586): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6586): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6586): 	at ihi.a(PG:22)
E/HttpOperation( 6586): 	at kft.a(PG:91)
E/HttpOperation( 6586): 	at kfv.a(PG:62)
E/HttpOperation( 6586): 	... 12 more
E/HttpOperation( 6586): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6586): 	at gde.c(Unknown Source)
E/HttpOperation( 6586): 	at gde.b(Unknown Source)
E/HttpOperation( 6586): 	at ihi.a(PG:19)
E/HttpOperation( 6586): 	... 14 more
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/ExperimentLoader( 6586): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6586): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6586): 	at kfv.a(PG:65)
E/ExperimentLoader( 6586): 	at kff.u(PG:385)
E/ExperimentLoader( 6586): 	at kfb.a(PG:29)
E/ExperimentLoader( 6586): 	at kff.l(PG:132)
E/ExperimentLoader( 6586): 	at ieo.a(PG:43)
E/ExperimentLoader( 6586): 	at iep.a(PG:93)
E/ExperimentLoader( 6586): 	at fhn.a(PG:59)
E/ExperimentLoader( 6586): 	at lex.a(PG:85)
E/ExperimentLoader( 6586): 	at lex.b(PG:132)
E/ExperimentLoader( 6586): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6586): 	at fhk.a(PG:908)
E/ExperimentLoader( 6586): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6586): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6586): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6586): 	at ihi.a(PG:22)
E/ExperimentLoader( 6586): 	at kft.a(PG:91)
E/ExperimentLoader( 6586): 	at kfv.a(PG:62)
E/ExperimentLoader( 6586): 	... 12 more
E/ExperimentLoader( 6586): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6586): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6586): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6586): 	at ihi.a(PG:19)
E/ExperimentLoader( 6586): 	... 14 more
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/GLSUser ( 1817): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1817): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1817): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1817): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  893): uri = 14 selection = getSealedState
,D/SecContentProvider2(  893): mCursor = null
,D/SecContentProvider2(  893): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  893): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  893): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6586): [getaccountstatus] Unexpected exception
E/HttpOperation( 6586): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6586): 	at kfv.a(PG:65)
E/HttpOperation( 6586): 	at kff.u(PG:385)
E/HttpOperation( 6586): 	at kfb.a(PG:29)
E/HttpOperation( 6586): 	at ixd.a(PG:248)
E/HttpOperation( 6586): 	at ixd.b(PG:206)
E/HttpOperation( 6586): 	at ixd.a(PG:175)
E/HttpOperation( 6586): 	at fig.a(PG:78)
E/HttpOperation( 6586): 	at lex.a(PG:85)
E/HttpOperation( 6586): 	at lex.b(PG:132)
E/HttpOperation( 6586): 	at fhk.a(PG:1146)
E/HttpOperation( 6586): 	at fhk.a(PG:908)
E/HttpOperation( 6586): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6586): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6586): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6586): 	at ihi.a(PG:22)
E/HttpOperation( 6586): 	at kft.a(PG:91)
E/HttpOperation( 6586): 	at kfv.a(PG:62)
E/HttpOperation( 6586): 	... 12 more
E/HttpOperation( 6586): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6586): 	at gde.c(Unknown Source)
E/HttpOperation( 6586): 	at gde.b(Unknown Source)
E/HttpOperation( 6586): 	at ihi.a(PG:19)
E/HttpOperation( 6586): 	... 14 more
,E/EsSyncAdapterService( 6586): Sync failure
E/EsSyncAdapterService( 6586): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6586): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6586): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6586): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6586): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6586): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6586): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6586): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6586): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6586): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6586): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6586): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6586): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6586): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6586): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6586): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6586): 	... 10 more
E/EsSyncAdapterService( 6586): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6586): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6586): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6586): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6586): 	... 12 more
E/EsSyncAdapterService( 6586): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6586): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6586): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6586): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6586): 	... 14 more
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  893): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 152301, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  893): Explicit concurrent mark sweep GC freed 82725(4MB) AllocSpace objects, 23(628KB) LOS objects, 30% free, 37MB/53MB, paused 1.799ms total 175.828ms
D/SecContentProvider2(  893): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  893): mCursor = null
,E/SQLiteLog( 1817): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/SSRM:m  (  893): SIOP:: AP = 320, PST = 357, CUR = 300
,V/AlarmManager(  893): waitForAlarm result :4
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/art     ( 1817): Explicit concurrent mark sweep GC freed 36883(2MB) AllocSpace objects, 23(1863KB) LOS objects, 39% free, 17MB/29MB, paused 447us total 35.639ms
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1817): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1817): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1817): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1817): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6615): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6615): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6615): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  289): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD ON
,E/Watchdog(  893): !@Sync 5
,I/PowerManagerService(  893): [PWL] Off : 75s ago
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 320, PST = 352, CUR = 300
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 310, PST = 346, CUR = 300
,V/AlarmManager(  893): waitForAlarm result :4
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1817): Vacuum at: now=1453202070145 tag=VacuumService
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GoogleURLConnFactory( 1817): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1817): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1817): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1817): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1817): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  893): uri = 14 selection = getSealedState
,D/SecContentProvider2(  893): mCursor = null
,D/SecContentProvider2(  893): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  893): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  893): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/Uploader( 1817): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1817): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1817): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1817): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1817): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1817): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1817): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1817): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1817): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1817): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1817): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1817): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1817): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,I/System.out( 1817): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1817): (HTTPLog)-Static: isShipBuild true
I/System.out( 1817): (HTTPLog)-Thread-226-952105398: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1817): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1817, getuid(): 10012
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 1817): Tagging socket 61 with tag 120100000000{4609,0} uid -1, pid: 1817, getuid(): 10012
,I/GLSUser ( 1817): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1817): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1817): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1817): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6615): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6615): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6615): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1817): No account for auth token provided
,I/qtaguid ( 1817): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1817, getuid(): 10012
,W/Uploader( 1817): No account for auth token provided
,I/qtaguid ( 1817): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1817, getuid(): 10012
,W/Uploader( 1817): No account for auth token provided
,I/qtaguid ( 1817): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1817, getuid(): 10012
,E/SMD     (  289): DCD ON
,W/Uploader( 1817):  no longer exists, so no auth token.
,I/qtaguid ( 1817): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1817, getuid(): 10012
,E/SQLiteLog( 1817): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  893): waitForAlarm result :4
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7322): Starting books sync, d
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/GLSUser ( 1817): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1817): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1817): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1817): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1817): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1817): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  893): uri = 14 selection = getSealedState
,D/SecContentProvider2(  893): mCursor = null
,D/SecContentProvider2(  893): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  893): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  893): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1817): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1817): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1817): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1817): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1817): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1817): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1817): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7322): Authentication error
E/BooksAccountManager( 7322): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7322): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7322): null auth token
,I/qtaguid ( 7322): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7322, getuid(): 10082
,I/qtaguid ( 7322): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7322, getuid(): 10082
,I/qtaguid ( 7322): Untagging socket 34
,W/ApiaryClient( 7322): Error response from books API: {
W/ApiaryClient( 7322):  "error": {
W/ApiaryClient( 7322):   "errors": [
W/ApiaryClient( 7322):    {
W/ApiaryClient( 7322):     "domain": "global",
W/ApiaryClient( 7322):     "reason": "required",
W/ApiaryClient( 7322):     "message": "Login Required",
W/ApiaryClient( 7322):     "locationType": "header",
W/ApiaryClient( 7322):     "location": "Authorization"
W/ApiaryClient( 7322):    }
W/ApiaryClient( 7322):   ],
W/ApiaryClient( 7322):   "code": 401,
W/ApiaryClient( 7322):   "message": "Login Required"
W/ApiaryClient( 7322):  }
W/ApiaryClient( 7322): }
,W/ApiaryClient( 7322): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7322): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8035244709693314883&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7322): Headers suppressed
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1817): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1817): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1817): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1817): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  893): uri = 14 selection = getSealedState
,D/SecContentProvider2(  893): mCursor = null
D/SecContentProvider2(  893): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  893): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  893): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1817): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1817): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1817): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1817): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1817): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1817): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1817): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7322): Authentication error
E/BooksAccountManager( 7322): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7322): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7322): null auth token
,I/qtaguid ( 7322): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7322, getuid(): 10082
,I/qtaguid ( 7322): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7322, getuid(): 10082
,I/qtaguid ( 7322): Untagging socket 34
,W/ApiaryClient( 7322): Error response from books API: {
W/ApiaryClient( 7322):  "error": {
W/ApiaryClient( 7322):   "errors": [
W/ApiaryClient( 7322):    {
W/ApiaryClient( 7322):     "domain": "global",
W/ApiaryClient( 7322):     "reason": "required",
W/ApiaryClient( 7322):     "message": "Login Required",
W/ApiaryClient( 7322):     "locationType": "header",
W/ApiaryClient( 7322):     "location": "Authorization"
W/ApiaryClient( 7322):    }
W/ApiaryClient( 7322):   ],
W/ApiaryClient( 7322):   "code": 401,
W/ApiaryClient( 7322):   "message": "Login Required"
W/ApiaryClient( 7322):  }
W/ApiaryClient( 7322): }
,W/ApiaryClient( 7322): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7322): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8035244709693314883&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7322): Headers suppressed
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  289): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...,
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1817): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1817): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1817): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1817): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  893): uri = 14 selection = getSealedState
,D/SecContentProvider2(  893): mCursor = null
D/SecContentProvider2(  893): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  893): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  893): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1817): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1817): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1817): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1817): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1817): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1817): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1817): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7322): Authentication error
E/BooksAccountManager( 7322): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7322): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7322): null auth token
,I/qtaguid ( 7322): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7322, getuid(): 10082
,I/qtaguid ( 7322): Untagging socket 34
,W/ApiaryClient( 7322): Error response from books API: {
W/ApiaryClient( 7322):  "error": {
W/ApiaryClient( 7322):   "errors": [
W/ApiaryClient( 7322):    {
W/ApiaryClient( 7322):     "domain": "global",
W/ApiaryClient( 7322):     "reason": "required",
W/ApiaryClient( 7322):     "message": "Login Required",
W/ApiaryClient( 7322):     "locationType": "header",
W/ApiaryClient( 7322):     "location": "Authorization"
W/ApiaryClient( 7322):    }
W/ApiaryClient( 7322):   ],
W/ApiaryClient( 7322):   "code": 401,
W/ApiaryClient( 7322):   "message": "Login Required"
W/ApiaryClient( 7322):  }
W/ApiaryClient( 7322): }
,W/ApiaryClient( 7322): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7322): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8035244709693314883&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7322): Headers suppressed
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/BooksSync( 7322): Soft error
E/BooksSync( 7322): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7322): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8035244709693314883&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7322): Headers suppressed
E/BooksSync( 7322): 
E/BooksSync( 7322): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7322): Sync error
E/BooksSync( 7322): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7322): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8035244709693314883&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7322): Headers suppressed
E/BooksSync( 7322): 
E/BooksSync( 7322): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7322): Finished books sync
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  893): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 157729, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  893): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  893): mCursor = null
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1817): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1817): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1817): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1817): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1817): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1817): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  893): uri = 14 selection = getSealedState
D/SecContentProvider2(  893): mCursor = null
,D/SecContentProvider2(  893): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  893): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  893): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6586): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6586): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6586): 	at kfv.a(PG:65)
E/HttpOperation( 6586): 	at kff.u(PG:385)
E/HttpOperation( 6586): 	at kfb.a(PG:29)
E/HttpOperation( 6586): 	at kff.l(PG:132)
E/HttpOperation( 6586): 	at dsf.a(PG:807)
E/HttpOperation( 6586): 	at fhk.a(PG:1126)
E/HttpOperation( 6586): 	at fhk.a(PG:908)
E/HttpOperation( 6586): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6586): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6586): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6586): 	at ihi.a(PG:22)
E/HttpOperation( 6586): 	at kft.a(PG:91)
E/HttpOperation( 6586): 	at kfv.a(PG:62)
E/HttpOperation( 6586): 	... 8 more
E/HttpOperation( 6586): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6586): 	at gde.c(Unknown Source)
E/HttpOperation( 6586): 	at gde.b(Unknown Source)
E/HttpOperation( 6586): 	at ihi.a(PG:19)
E/HttpOperation( 6586): 	... 10 more
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/GLSUser ( 1817): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1817): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1817): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1817): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  893): uri = 14 selection = getSealedState
D/SecContentProvider2(  893): mCursor = null
,D/SecContentProvider2(  893): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  893): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  893): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6586): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6586): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6586): 	at kfv.a(PG:65)
E/HttpOperation( 6586): 	at kff.u(PG:385)
E/HttpOperation( 6586): 	at kfb.a(PG:29)
E/HttpOperation( 6586): 	at kff.l(PG:132)
E/HttpOperation( 6586): 	at ieo.a(PG:43)
E/HttpOperation( 6586): 	at iep.a(PG:93)
E/HttpOperation( 6586): 	at fhn.a(PG:59)
E/HttpOperation( 6586): 	at lex.a(PG:85)
E/HttpOperation( 6586): 	at lex.b(PG:132)
E/HttpOperation( 6586): 	at fhk.a(PG:1146)
E/HttpOperation( 6586): 	at fhk.a(PG:908)
E/HttpOperation( 6586): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6586): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6586): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6586): 	at ihi.a(PG:22)
E/HttpOperation( 6586): 	at kft.a(PG:91)
E/HttpOperation( 6586): 	at kfv.a(PG:62)
E/HttpOperation( 6586): 	... 12 more
E/HttpOperation( 6586): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6586): 	at gde.c(Unknown Source)
E/HttpOperation( 6586): 	at gde.b(Unknown Source)
E/HttpOperation( 6586): 	at ihi.a(PG:19)
E/HttpOperation( 6586): 	... 14 more
,E/ExperimentLoader( 6586): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6586): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6586): 	at kfv.a(PG:65)
E/ExperimentLoader( 6586): 	at kff.u(PG:385)
E/ExperimentLoader( 6586): 	at kfb.a(PG:29)
E/ExperimentLoader( 6586): 	at kff.l(PG:132)
E/ExperimentLoader( 6586): 	at ieo.a(PG:43)
E/ExperimentLoader( 6586): 	at iep.a(PG:93)
E/ExperimentLoader( 6586): 	at fhn.a(PG:59)
E/ExperimentLoader( 6586): 	at lex.a(PG:85)
E/ExperimentLoader( 6586): 	at lex.b(PG:132)
E/ExperimentLoader( 6586): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6586): 	at fhk.a(PG:908)
E/ExperimentLoader( 6586): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6586): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6586): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6586): 	at ihi.a(PG:22)
E/ExperimentLoader( 6586): 	at kft.a(PG:91)
E/ExperimentLoader( 6586): 	at kfv.a(PG:62)
E/ExperimentLoader( 6586): 	... 12 more
E/ExperimentLoader( 6586): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6586): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6586): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6586): 	at ihi.a(PG:19)
E/ExperimentLoader( 6586): 	... 14 more
D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/SMD     (  289): DCD ON
,E/SQLiteLog( 1817): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1817): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1817): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1817): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1817): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  893): uri = 14 selection = getSealedState
,D/SecContentProvider2(  893): mCursor = null
,D/SecContentProvider2(  893): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  893): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  893): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6586): [getaccountstatus] Unexpected exception
E/HttpOperation( 6586): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6586): 	at kfv.a(PG:65)
E/HttpOperation( 6586): 	at kff.u(PG:385)
E/HttpOperation( 6586): 	at kfb.a(PG:29)
E/HttpOperation( 6586): 	at ixd.a(PG:248)
E/HttpOperation( 6586): 	at ixd.b(PG:206)
E/HttpOperation( 6586): 	at ixd.a(PG:175)
E/HttpOperation( 6586): 	at fig.a(PG:78)
E/HttpOperation( 6586): 	at lex.a(PG:85)
E/HttpOperation( 6586): 	at lex.b(PG:132)
E/HttpOperation( 6586): 	at fhk.a(PG:1146)
E/HttpOperation( 6586): 	at fhk.a(PG:908)
E/HttpOperation( 6586): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6586): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6586): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6586): 	at ihi.a(PG:22)
E/HttpOperation( 6586): 	at kft.a(PG:91)
E/HttpOperation( 6586): 	at kfv.a(PG:62)
E/HttpOperation( 6586): 	... 12 more
E/HttpOperation( 6586): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6586): 	at gde.c(Unknown Source)
E/HttpOperation( 6586): 	at gde.b(Unknown Source)
E/HttpOperation( 6586): 	at ihi.a(PG:19)
E/HttpOperation( 6586): 	... 14 more
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/EsSyncAdapterService( 6586): Sync failure
E/EsSyncAdapterService( 6586): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6586): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6586): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6586): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6586): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6586): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6586): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6586): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6586): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6586): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6586): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6586): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6586): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6586): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6586): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6586): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6586): 	... 10 more
E/EsSyncAdapterService( 6586): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6586): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6586): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6586): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6586): 	... 12 more
E/EsSyncAdapterService( 6586): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6586): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6586): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6586): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6586): 	... 14 more
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  893): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 184571, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 5
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  893): Explicit concurrent mark sweep GC freed 42123(2MB) AllocSpace objects, 19(759KB) LOS objects, 30% free, 36MB/52MB, paused 2.242ms total 196.621ms
,D/SecContentProvider2(  893): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  893): mCursor = null
,E/SQLiteLog( 1817): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:m  (  893): SIOP:: AP = 310, PST = 340, CUR = 300
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,E/Watchdog(  893): !@Sync 6
,I/PowerManagerService(  893): [PWL] Off : 105s ago
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 310, PST = 335, CUR = 300
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,D/BatteryService(  893): stay LED for fully charged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 300, PST = 325, CUR = 300
,V/AlarmManager(  893): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  893): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,I/Atfwd_Sendcmd(  347): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  347): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  893): stay LED for fully charged
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
I/MotionRecognitionService(  893): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 300, PST = 316, CUR = 300
,E/SMD     (  289): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/Watchdog(  893): !@Sync 7
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 1
,I/PowerManagerService(  893): [PWL] Off : 140s ago
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 300, PST = 312, CUR = 300
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 300, PST = 309, CUR = 300
,E/SMD     (  289): DCD ON
,V/AlarmManager(  893): waitForAlarm result :4
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7322): Starting books sync, d
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1817): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1817): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1817): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1817): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  893): uri = 14 selection = getSealedState
,D/SecContentProvider2(  893): mCursor = null
D/SecContentProvider2(  893): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  893): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  893): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1817): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1817): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1817): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1817): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1817): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1817): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1817): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7322): Authentication error
E/BooksAccountManager( 7322): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7322): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7322): null auth token
,I/qtaguid ( 7322): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7322, getuid(): 10082
,I/qtaguid ( 7322): Untagging socket 34
,W/ApiaryClient( 7322): Error response from books API: {
W/ApiaryClient( 7322):  "error": {
W/ApiaryClient( 7322):   "errors": [
W/ApiaryClient( 7322):    {
W/ApiaryClient( 7322):     "domain": "global",
W/ApiaryClient( 7322):     "reason": "required",
W/ApiaryClient( 7322):     "message": "Login Required",
W/ApiaryClient( 7322):     "locationType": "header",
W/ApiaryClient( 7322):     "location": "Authorization"
W/ApiaryClient( 7322):    }
W/ApiaryClient( 7322):   ],
W/ApiaryClient( 7322):   "code": 401,
W/ApiaryClient( 7322):   "message": "Login Required"
W/ApiaryClient( 7322):  }
W/ApiaryClient( 7322): }
,W/ApiaryClient( 7322): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7322): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6959334497693751306&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7322): Headers suppressed
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1817): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1817): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1817): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1817): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  893): uri = 14 selection = getSealedState
,D/SecContentProvider2(  893): mCursor = null
D/SecContentProvider2(  893): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  893): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  893): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/SMD     (  289): DCD ON
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1817): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1817): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1817): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1817): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1817): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1817): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1817): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7322): Authentication error
E/BooksAccountManager( 7322): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7322): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7322): null auth token
,I/qtaguid ( 7322): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7322, getuid(): 10082
,I/qtaguid ( 7322): Untagging socket 34
,W/ApiaryClient( 7322): Error response from books API: {
W/ApiaryClient( 7322):  "error": {
W/ApiaryClient( 7322):   "errors": [
W/ApiaryClient( 7322):    {
W/ApiaryClient( 7322):     "domain": "global",
W/ApiaryClient( 7322):     "reason": "required",
W/ApiaryClient( 7322):     "message": "Login Required",
W/ApiaryClient( 7322):     "locationType": "header",
W/ApiaryClient( 7322):     "location": "Authorization"
W/ApiaryClient( 7322):    }
W/ApiaryClient( 7322):   ],
W/ApiaryClient( 7322):   "code": 401,
W/ApiaryClient( 7322):   "message": "Login Required"
W/ApiaryClient( 7322):  }
W/ApiaryClient( 7322): }
,W/ApiaryClient( 7322): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7322): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6959334497693751306&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7322): Headers suppressed
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1817): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1817): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1817): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1817): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  893): uri = 14 selection = getSealedState
,D/SecContentProvider2(  893): mCursor = null
D/SecContentProvider2(  893): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  893): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  893): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1817): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1817): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1817): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1817): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1817): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1817): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1817): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7322): Authentication error
E/BooksAccountManager( 7322): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7322): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7322): null auth token
,I/qtaguid ( 7322): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7322, getuid(): 10082
,I/qtaguid ( 7322): Untagging socket 34
,W/ApiaryClient( 7322): Error response from books API: {
W/ApiaryClient( 7322):  "error": {
W/ApiaryClient( 7322):   "errors": [
W/ApiaryClient( 7322):    {
W/ApiaryClient( 7322):     "domain": "global",
W/ApiaryClient( 7322):     "reason": "required",
W/ApiaryClient( 7322):     "message": "Login Required",
W/ApiaryClient( 7322):     "locationType": "header",
W/ApiaryClient( 7322):     "location": "Authorization"
W/ApiaryClient( 7322):    }
W/ApiaryClient( 7322):   ],
W/ApiaryClient( 7322):   "code": 401,
W/ApiaryClient( 7322):   "message": "Login Required"
W/ApiaryClient( 7322):  }
W/ApiaryClient( 7322): }
,W/ApiaryClient( 7322): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7322): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6959334497693751306&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7322): Headers suppressed
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7322): Soft error
E/BooksSync( 7322): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7322): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6959334497693751306&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7322): Headers suppressed
E/BooksSync( 7322): 
E/BooksSync( 7322): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7322): Sync error
E/BooksSync( 7322): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7322): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6959334497693751306&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7322): Headers suppressed
E/BooksSync( 7322): 
E/BooksSync( 7322): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7322): Finished books sync
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  893): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 217898, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  893): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  893): mCursor = null
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  289): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/SSRM:m  (  893): SIOP:: AP = 300, PST = 307, CUR = 300
,E/SMD     (  289): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/BatteryService(  893): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/Watchdog(  893): !@Sync 8
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 300, PST = 305, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/PowerManagerService(  893): [PWL] Off : 180s ago
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,D/SSRM:m  (  893): SIOP:: AP = 300, PST = 303, CUR = 300
,V/AlarmManager(  893): waitForAlarm result :8
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 4
,V/AlarmManager(  893): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1817): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1817): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1817): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1817): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  893): uri = 14 selection = getSealedState
,D/SecContentProvider2(  893): mCursor = null
D/SecContentProvider2(  893): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  893): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  893): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6586): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6586): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6586): 	at kfv.a(PG:65)
E/HttpOperation( 6586): 	at kff.u(PG:385)
E/HttpOperation( 6586): 	at kfb.a(PG:29)
E/HttpOperation( 6586): 	at kff.l(PG:132)
E/HttpOperation( 6586): 	at dsf.a(PG:807)
E/HttpOperation( 6586): 	at fhk.a(PG:1126)
E/HttpOperation( 6586): 	at fhk.a(PG:908)
E/HttpOperation( 6586): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6586): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6586): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6586): 	at ihi.a(PG:22)
E/HttpOperation( 6586): 	at kft.a(PG:91)
E/HttpOperation( 6586): 	at kfv.a(PG:62)
E/HttpOperation( 6586): 	... 8 more
E/HttpOperation( 6586): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6586): 	at gde.c(Unknown Source)
E/HttpOperation( 6586): 	at gde.b(Unknown Source)
E/HttpOperation( 6586): 	at ihi.a(PG:19)
E/HttpOperation( 6586): 	... 10 more
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/GLSUser ( 1817): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1817): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1817): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1817): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  893): uri = 14 selection = getSealedState
,D/SecContentProvider2(  893): mCursor = null
,D/SecContentProvider2(  893): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  893): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  893): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6586): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6586): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6586): 	at kfv.a(PG:65)
E/HttpOperation( 6586): 	at kff.u(PG:385)
E/HttpOperation( 6586): 	at kfb.a(PG:29)
E/HttpOperation( 6586): 	at kff.l(PG:132)
E/HttpOperation( 6586): 	at ieo.a(PG:43)
E/HttpOperation( 6586): 	at iep.a(PG:93)
E/HttpOperation( 6586): 	at fhn.a(PG:59)
E/HttpOperation( 6586): 	at lex.a(PG:85)
E/HttpOperation( 6586): 	at lex.b(PG:132)
E/HttpOperation( 6586): 	at fhk.a(PG:1146)
E/HttpOperation( 6586): 	at fhk.a(PG:908)
E/HttpOperation( 6586): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6586): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6586): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6586): 	at ihi.a(PG:22)
E/HttpOperation( 6586): 	at kft.a(PG:91)
E/HttpOperation( 6586): 	at kfv.a(PG:62)
E/HttpOperation( 6586): 	... 12 more
E/HttpOperation( 6586): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6586): 	at gde.c(Unknown Source)
E/HttpOperation( 6586): 	at gde.b(Unknown Source)
E/HttpOperation( 6586): 	at ihi.a(PG:19)
E/HttpOperation( 6586): 	... 14 more
,E/ExperimentLoader( 6586): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6586): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6586): 	at kfv.a(PG:65)
E/ExperimentLoader( 6586): 	at kff.u(PG:385)
E/ExperimentLoader( 6586): 	at kfb.a(PG:29)
E/ExperimentLoader( 6586): 	at kff.l(PG:132)
E/ExperimentLoader( 6586): 	at ieo.a(PG:43)
E/ExperimentLoader( 6586): 	at iep.a(PG:93)
E/ExperimentLoader( 6586): 	at fhn.a(PG:59)
E/ExperimentLoader( 6586): 	at lex.a(PG:85)
E/ExperimentLoader( 6586): 	at lex.b(PG:132)
E/ExperimentLoader( 6586): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6586): 	at fhk.a(PG:908)
E/ExperimentLoader( 6586): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6586): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6586): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6586): 	at ihi.a(PG:22)
E/ExperimentLoader( 6586): 	at kft.a(PG:91)
E/ExperimentLoader( 6586): 	at kfv.a(PG:62)
E/ExperimentLoader( 6586): 	... 12 more
E/ExperimentLoader( 6586): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6586): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6586): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6586): 	at ihi.a(PG:19)
E/ExperimentLoader( 6586): 	... 14 more
,I/art     ( 1817): Explicit concurrent mark sweep GC freed 64470(3MB) AllocSpace objects, 56(3MB) LOS objects, 40% free, 18MB/30MB, paused 944us total 80.638ms
,I/GLSUser ( 1817): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1817): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1817): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1817): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1817): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1817): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1817): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  893): uri = 14 selection = getSealedState
D/SecContentProvider2(  893): mCursor = null
,D/SecContentProvider2(  893): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  893): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  893): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6586): [getaccountstatus] Unexpected exception
E/HttpOperation( 6586): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6586): 	at kfv.a(PG:65)
E/HttpOperation( 6586): 	at kff.u(PG:385)
E/HttpOperation( 6586): 	at kfb.a(PG:29)
E/HttpOperation( 6586): 	at ixd.a(PG:248)
E/HttpOperation( 6586): 	at ixd.b(PG:206)
E/HttpOperation( 6586): 	at ixd.a(PG:175)
E/HttpOperation( 6586): 	at fig.a(PG:78)
E/HttpOperation( 6586): 	at lex.a(PG:85)
E/HttpOperation( 6586): 	at lex.b(PG:132)
E/HttpOperation( 6586): 	at fhk.a(PG:1146)
E/HttpOperation( 6586): 	at fhk.a(PG:908)
E/HttpOperation( 6586): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6586): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6586): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6586): 	at ihi.a(PG:22)
E/HttpOperation( 6586): 	at kft.a(PG:91)
E/HttpOperation( 6586): 	at kfv.a(PG:62)
E/HttpOperation( 6586): 	... 12 more
E/HttpOperation( 6586): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6586): 	at gde.c(Unknown Source)
E/HttpOperation( 6586): 	at gde.b(Unknown Source)
E/HttpOperation( 6586): 	at ihi.a(PG:19)
E/HttpOperation( 6586): 	... 14 more
,E/EsSyncAdapterService( 6586): Sync failure
E/EsSyncAdapterService( 6586): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6586): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6586): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6586): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6586): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6586): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6586): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6586): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6586): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6586): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6586): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6586): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6586): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6586): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6586): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6586): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6586): 	... 10 more
E/EsSyncAdapterService( 6586): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6586): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6586): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6586): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6586): 	... 12 more
E/EsSyncAdapterService( 6586): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6586): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6586): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6586): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6586): 	... 14 more
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  893): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 250288, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2852): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  893): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  893): mCursor = null
,E/SQLiteLog( 1817): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON,
,D/SSRM:m  (  893): SIOP:: AP = 300, PST = 302, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  893): stay LED for fully charged
,D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,I/MotionRecognitionService(  893): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/Watchdog(  893): !@Sync 9
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 300, PST = 301, CUR = 300
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,I/ServiceManager(  347): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  347): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  289): DCD ON
,V/AlarmManager(  893): waitForAlarm result :4
,D/ConnectivityService(  893): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  893): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  893): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  893): stay LED for fully charged
D/BatteryService(  893): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  893):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  893): Plugged
I/MotionRecognitionService(  893): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  289): DCD ON
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
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,E/Watchdog(  893): !@Sync 10
,I/PowerManagerService(  893): [PWL] Off : 225s ago
,I/PowerManagerService(  893): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  893): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  893): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=893, ws=null) (elapsedTime=3143)
,I/TLC_TIMA_PKM_measure_kernel(  893): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  893): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  893): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  893): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD ON,
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  893): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  289): DCD ON
,I/Atfwd_Sendcmd(  347): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  347): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/jxcore-log( 7489): --= Surplus to requirements =--
I/jxcore-log( 7489): 
,I/jxcore-log( 7489): ****TEST TOOK:  ms ****
I/jxcore-log( 7489): 
I/jxcore-log( 7489): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7489): 
,D/AndroidRuntime( 8485): 
D/AndroidRuntime( 8485): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8485): CheckJNI is OFF
,D/AndroidRuntime( 8485): setted country_code = Germany
D/AndroidRuntime( 8485): setted countryiso_code = DE
,D/AndroidRuntime( 8485): setted sales_code = DBT
D/AndroidRuntime( 8485): readGMSProperty: start
,D/AndroidRuntime( 8485): readGMSProperty: already setted!!
D/AndroidRuntime( 8485): readGMSProperty: end
D/AndroidRuntime( 8485): addProductProperty: start
,E/AffinityControl( 8485): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8485): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  893): START PACKAGE DELETE: observer{746873751}
D/PackageManager(  893): pkg{<packageName>}
D/PackageManager(  893): user{0}
D/PackageManager(  893): caller{2000}
D/PackageManager(  893): flags{3}
D/PersonaManagerService(  893): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  893): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  893): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  893): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  893): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  893): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  893): deletePackage- pkg:com.test.thalitest, edmuserId:0
,D/PackageManagerService(  893): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  893): getApplicationUninstallationEnabled
D/ApplicationPolicy(  893): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  893): !@killApplicatoin: 10200, uninstall pkg
,I/ActivityManager(  893): Force stopping com.test.thalitest appid=10200 user=-1: uninstall pkg
,I/ActivityManager(  893): Killing 7489:com.test.thalitest/u0a200 (adj 0): stop com.test.thalitest
,I/ActivityManager(  893):   Force finishing activity ActivityRecord{276d1384 u0 com.test.thalitest/.MainActivity t18}
,W/ActivityManager(  893): mDVFSHelper.acquire()
,I/WindowState(  893): WIN DEATH: Window{1086fcaa u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  893): Client connection lost with reason: 4
,I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
,I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/FocusedStackFrame(  893): Set to : 0
,I/ActivityManager(  893): Force stopping com.test.thalitest appid=10200 user=0: pkg removed
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/art     ( 4382): Explicit concurrent mark sweep GC freed 5023(278KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 1.123ms total 36.976ms
,I/DBG_DM  ( 3834): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/DBG_DM  ( 3834): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 65
,I/art     ( 1684): Explicit concurrent mark sweep GC freed 60101(3MB) AllocSpace objects, 0(0B) LOS objects, 39% free, 16MB/27MB, paused 3.492ms total 160.349ms
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/DBG_DM  ( 3834): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/InputReader(  893): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1838): mOCRHelper is null
,W/GeofencerStateMachine( 2230): Ignoring removeGeofence because network location is disabled.
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/DBG_DM  ( 3834): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3834): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 65
,I/DBG_DM  ( 3834): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/KLMS-2.4.503: ( 7730): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/DBG_DM  ( 3834): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/ResourcesManager( 2852): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,I/KLMS-2.4.503: ( 7730): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1453202214302
,I/DBG_DM  ( 3834): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/KLMS-2.4.503: ( 7730): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.503: ( 7730): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,D/SecContentProvider2(  893): uri = 14 selection = getSealedState
D/SecContentProvider2(  893): mCursor = null
,D/SecContentProvider2(  893): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  893): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy(  893): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/DBG_DM  ( 3834): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 65
,I/art     (  893): Explicit concurrent mark sweep GC freed 49123(3MB) AllocSpace objects, 54(1254KB) LOS objects, 30% free, 36MB/52MB, paused 2.356ms total 198.065ms
,I/DBG_DM  ( 3834): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/art     (  893): WaitForGcToComplete blocked for 91.410ms for cause Explicit
,D/ResourcesManager(  893): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/DBG_DM  ( 3834): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3834): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3834): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 3834): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager(  893): post active user change for 0
D/KnoxTimeoutHandler(  893): postActiveUserChange for user 0
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
I/DBG_DM  ( 3834): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/SurfaceFlinger(  249): id=17 createSurf (1080x1920),2 flag=404, com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/StatusBarManagerService(  893): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager( 2852): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/SurfaceWidgetView( 1478): destroyHardwareResources():740023516
,D/SecContentProvider2(  893): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  893): mCursor = null
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/RegisteredServicesCache( 1455): empty dynamic service
,V/WindowOrientationListener(  893): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  893): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  893): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  893): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  893): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/Launcher( 1478): onRestart, Launcher: 82435601
,D/Launcher( 1478): onStart, Launcher: 82435601
D/Launcher.HomeView( 1478): onStart
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/Launcher.HomeView( 1478): onStop
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2107): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 2107): [237392/6] SurfaceWidget drawing first frame
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/SurfaceFlinger(  249): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/StatusBarManagerService(  893): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/StatusBarManagerService(  893): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/SurfaceFlinger(  249): id=17 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (5/9)
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,I/SurfaceFlinger(  249): id=17 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/9)
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Books/Books.apk
,I/Timeline( 3834): Timeline: Activity_idle id: android.os.BinderProxy@39e2ede2 time:324856
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,E/Zygote  ( 8517): MountEmulatedStorage()
E/Zygote  ( 8517): v2
I/libpersona( 8517): KNOX_SDCARD checking this for 10104
I/libpersona( 8517): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8517 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/InputMethodManagerService(  893): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/SELinux ( 8517): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/ContextImpl(  893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SELinux ( 8517): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8517): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/talkback/talkback.apk
,W/InputMethodManagerService(  893): Got RemoteException sending setActive(false) notification to pid 7489 uid 10200
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/TimaKeyStoreProvider( 8517): TimaSignature is unavailable
,D/ActivityThread( 8517): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager( 8517): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/EnterpriseDeviceManagerService(  893): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  893): Admin package name: com.google.android.gms
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/RCPManagerService(  893): PackageReceiver onReceive()
,I/HarmonyEASService(  893): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/KnoxMUMContainerPolicy(  893): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/ActivityManager(  893): mDVFSHelper.release()
,I/Timeline(  893): Timeline: Activity_windows_visible id: ActivityRecord{38ce80f4 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t15} time:324991
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/BackupManagerService(  893): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  893): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  893): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  893): uID is 10200
V/EnterpriseBillingPolicy(  893): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  893): getProfileForApplication - enter
,D/elm:14451( 8517): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,V/EnterpriseBillingPolicyStorage(  893): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  893): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  893): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  893): getBillingProfileForVpnEngine - start - com.test.thalitest
,D/elm:14451( 8517): ELMEngine.ELMEngine( context ).
,V/EnterpriseBillingPolicyStorage(  893): getBillingProfileForVpnEngine - end - null
W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/elm:14451( 8517): MDMBridge.setEnterpriseBridge()
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/elm:14451( 8517): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14451( 8517): ElmAgentService : onCreate()
,D/elm:14451( 8517): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8517): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8517): MDMBridge.getInstance()
D/elm:14451( 8517): MDMBridge.getAllLicenseInfoFromSDK()
,D/TaskPersister(  893): removeObsoleteFile: deleting file=18_task.xml
,D/KnoxTimeoutHandler(  893): handleActiveUserChange for user 0
D/TaskPersister(  893): removeObsoleteFile: deleting file=17_task.xml
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 8009): onReceive()
,I/com.sec.android.service.health.upgrade.UninstallReceiver( 8009): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8009): onReceive() : package name is not s health. Return !!!
,D/elm:14451( 8517): MDMBridge.getAllLicenseInfoFromSDK()
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PCWCLIENTTRACE_PushUtil( 6806): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6806): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6806): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6806): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/elm:14451( 8517): ElmAgentService : onDestroy().
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,I/art     (  893): Explicit concurrent mark sweep GC freed 14467(727KB) AllocSpace objects, 1(16KB) LOS objects, 30% free, 37MB/53MB, paused 3.972ms total 372.747ms
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,E/Zygote  ( 8538): MountEmulatedStorage()
E/Zygote  ( 8538): v2
I/libpersona( 8538): KNOX_SDCARD checking this for 10038
I/libpersona( 8538): KNOX_SDCARD not a persona
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/ActivityManager(  893): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8538 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 7073:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/PackageManager(  893): delete codoeFile: 
,D/ConnectivityService(  893): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 8538): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8538): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8538): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/PackageManager(  893): result of delete: 1{746873751}
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/AndroidRuntime( 8485): Shutting down VM
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/TimaKeyStoreProvider( 8538): TimaSignature is unavailable
,D/ActivityThread( 8538): Added TimaKeyStore provider
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  893): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  893): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  893): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager( 8538): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,W/libprocessgroup(  893): failed to open /acct/uid_10118/pid_7073/cgroup.procs: No such file or directory
,D/ResourcesManager(  893): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  893): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  893): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  893): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  893): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  893): onPackageRemoved : com.test.thalitest
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,E/SPPClientService( 8538): ============PushLog. commonIsShipBuild. stop!
W/ResourcesManager( 7959): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
E/SPPClientService( 8538): [PushClientApplication] Push log off : This is Ship build version
,W/ResourcesManager( 7959): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/SPPClientService( 8538): PushLog.txt file is not deleted.
,D/SPPClientService( 8538): PushLog.txt file is not deleted.
D/SPPClientService( 8538): ============PushLog. stop!
,W/ResourcesManager( 7959): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7959): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 7959): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,E/Zygote  ( 8554): MountEmulatedStorage()
I/ActivityManager(  893): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8554 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
E/Zygote  ( 8554): v2
I/libpersona( 8554): KNOX_SDCARD checking this for 10042
I/libpersona( 8554): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Killing 7090:com.samsung.helphub/1000 (adj 15): bgCount ##41
,W/ResourcesManager( 7959): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/SELinux ( 8554): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,I/SELinux ( 8554): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,W/ResourcesManager( 7959): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/SELinux ( 8554): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 7959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7959): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/libprocessgroup(  893): failed to open /acct/uid_1000/pid_7090/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8554): TimaSignature is unavailable
,D/ActivityThread( 8554): Added TimaKeyStore provider
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 7959): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 8554): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,W/ResourcesManager( 8554): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8554): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7959): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 7959): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7959): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7959): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 7959): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SMD     (  289): DCD ON
,F/libc    ( 8554): Fatal signal 7 (SIGBUS), code 2, fault addr 0x78285364 in tid 8554 (sdk.samsunglink)
,E/audit_log( 2173): File locking failed. error= Bad file number
,F/libc    ( 8554): Failed while talking to debuggerd: Broken pipe
E/audit_log( 2173): File locking failed. error= Bad file number
,I/EventHub(  893): Removing device '/dev/input/event4' due to inotify event
,I/ActivityManager(  893): Process com.samsung.android.sdk.samsunglink (pid 8554)(adj 0) has died(140,543)
,I/EventHub(  893): Removing device '/dev/input/event5' due to inotify event
,I/SA      ( 6846): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6846): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10200 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/Zygote  (  337): Process 8554 exited due to signal (7)
,F/libc    ( 1787): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7828ee10 in tid 1891 (ContactsProvide)
,F/libc    ( 1787): Unable to open connection to debuggerd: Connection refused
,F/libc    ( 1787): Fatal signal 7 (SIGBUS), code 2, fault addr 0x77e0044c in tid 1787 (d.process.acore)
,E/audit_log( 2173): File locking failed. error= Bad file number
,I/EventHub(  893): Removing device '/dev/input/event6' due to inotify event
,I/ActivityManager(  893): Process android.process.acore (pid 1787)(adj 0) has died(145,543)
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,E/SharedPreferencesImpl( 6063): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml
,I/EventHub(  893): Removing device '/dev/input/event7' due to inotify event
,E/Zygote  ( 8573): MountEmulatedStorage()
,E/Zygote  ( 8573): v2
I/Zygote  (  337): Process 1787 exited due to signal (7)
,I/libpersona( 8573): KNOX_SDCARD checking this for 10050
,I/libpersona( 8573): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageReceiver: pid=8573 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/EventHub(  893): Removing device '/dev/input/event8' due to inotify event
,I/SELinux ( 8573): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
E/SELinux ( 8573): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/EventHub(  893): Removing device '/dev/input/event9' due to inotify event
,I/EventHub(  893): Removing device '/dev/input/event10' due to inotify event
,D/TimaKeyStoreProvider( 8573): TimaSignature is unavailable
,D/ActivityThread( 8573): Added TimaKeyStore provider
,I/EventHub(  893): Removing device '/dev/input/event11' due to inotify event
,D/ResourcesManager( 8573): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8573): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8573): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8573): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8573): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8573): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ContextImpl( 8573): Unable to create files subdir /data/data/com.android.mms/cache
,E/ActivityThread( 8573): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 8573): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7429da62 in tid 8573 (com.android.mms)
,F/libc    ( 8573): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2173): File locking failed. error= Bad file number
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,I/ActivityManager(  893): Process com.android.mms (pid 8573)(adj 0) has died(144,543)
,I/TactileAssist(  893): enable value -1
I/TactileAssist(  893): internal enable value -1
I/TactileAssist(  893): intensity value -1
I/TactileAssist(  893): saveAppList value true
,I/TactileAssist(  893): List of disabled apps :
,I/TactileAssist(  893): de.zalando.mobile
,E/SharedPreferencesImpl(  893): Couldn't create directory for SharedPreferences file /data/data/com.android.settings/shared_prefs/com.android.settings_tactileassist.xml
,E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  893): checkUser: useridlist=null, currentuser=0
,I/Zygote  (  337): Process 8573 exited due to signal (7)
,E/Zygote  ( 8588): MountEmulatedStorage()
,E/Zygote  ( 8588): v2
I/libpersona( 8588): KNOX_SDCARD checking this for 10058
I/libpersona( 8588): KNOX_SDCARD not a persona
,I/ActivityManager(  893): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=8588 uid=10058 gids={50058, 9997, 3003, 3002} abi=armeabi-v7a

```
