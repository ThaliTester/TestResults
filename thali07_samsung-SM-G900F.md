#### Test 56151093b6ab50f_thali07_samsung-SM-G900F Logs


```
--------- beginning of system
,V/AlarmManager(  875): waitForAlarm result :8
V/AlarmManager(  875): waitForAlarm result :4
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
--------- beginning of main
E/Zygote  ( 7376): MountEmulatedStorage()
E/Zygote  ( 7376): v2
I/libpersona( 7376): KNOX_SDCARD checking this for 10179
I/libpersona( 7376): KNOX_SDCARD not a persona
I/SELinux ( 7376): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7376): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7376): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  875): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler: pid=7376 uid=10179 gids={50179, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/TimaKeyStoreProvider( 7376): TimaSignature is unavailable
D/ActivityThread( 7376): Added TimaKeyStore provider
D/ResourcesManager( 7376): creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
W/ResourcesManager( 7376): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/UMC:Core( 7376): onCreate(): 
D/USER_AGENT( 7376): UMC/1.1.39 (SM-G900F) SAFE-5.3 KNOX-2.3
D/[SAMSUNG SMARCART NATIVE]( 7376): initialize...
D/[SAMSUNG SMARCART NATIVE]( 7376): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
I/CSTORAGE( 7376): ================================================
I/CSTORAGE( 7376):  CSTORAGE_SKM_LIB v1.0.8
I/CSTORAGE( 7376): ================================================
I/TZ_CCM_C_GetFunctionList: ( 7376): TZ_CCM_C_GetFunctionList was called
D/[SAMSUNG SMARCART NATIVE]( 7376): FINISHED: initialize rv:0
D/AndroidRuntime( 7374): 
D/AndroidRuntime( 7374): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7374): CheckJNI is OFF
D/AndroidRuntime( 7374): setted country_code = Germany
D/AndroidRuntime( 7374): setted countryiso_code = DE
D/AndroidRuntime( 7374): setted sales_code = DBT
D/AndroidRuntime( 7374): readGMSProperty: start
D/AndroidRuntime( 7374): readGMSProperty: already setted!!
D/AndroidRuntime( 7374): readGMSProperty: end
D/AndroidRuntime( 7374): addProductProperty: start
E/SMD     (  286): DCD ON
D/UMC:SecurityUtils( 7376): Loaded server certificates: 0
D/UMC:SecurityUtils( 7376): Loaded server certificates: 0
D/UMC:SecurityUtils( 7376): timaVersion on the device: 3.0
D/UMC:CloudMDMSecurity( 7376): New Flow
D/TimaService(  875): TIMA3: in ccmRegisterForDefaultCertificate
I/        (  875): CCM JNI: In ccm_register_for_default_cert
D/TimaService(  875): TIMA: in getTimaVersion
I/        (  875): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: (  875): DEBUG_CONTAINER_PROBLEM Enter TZ_CCM_C_Initialize_TLC!
I/TZ_CCM_C_Initialize: (  875): pInitArgs 0x96fff814 has not called C_Init before.
I/TZ_CCM_C_Initialize: (  875): &ctx = 0x9fab6c1c
I/TLC_TZ_CCM: (  875): creating new ccm context...
I/TLC_TZ_CCM: (  875): initializing ccm context...
I/TLC_TZ_CCM: (  875): root = /firmware/image, root_strlen = 15
I/TLC_TZ_CCM: (  875): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  875): input max_sendmsg_size = 19420
I/TZ: client_server_communication(  875): input max_recvmsg_size = 19420
I/TZ: client_server_communication(  875): root = /firmware/image, root_len = 15
I/TZ: client_server_communication(  875): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  875): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication(  875): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication(  875): Client_Server_Open was called
I/TZ: client_server_communication(  875): IClientServer::IClientServer()
I/TZ: client_server_communication(  875): BpClientServer::BpClientServer()
I/TZ: client_server_communication(  875): IClientServer::~IClientServer()
I/TZ_CCM_SERVER( 1076): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 1076): OPENSWCONN
I/TZ_CCM_SERVER( 1076): creating new ccm context...
I/TZ_CCM_SERVER( 1076): initializing ccm context...
I/TZ_CCM_SERVER( 1076): root = /firmware/image, root_strlen = 15
I/TZ_CCM_SERVER( 1076): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1076): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1076): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1076): aligned max_sendmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1076): aligned max_recvmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1076): max_message_size = 38912 = 0x9800
D/QSEECOMAPI: ( 1076): QSEECom_get_handle sb_length = 0x9800
V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QSEECOMAPI: ( 1076): App is not loaded in QSEE
D/QSEECOMAPI: ( 1076): Loaded image: APP id = 3
I/TZ: qc_tlc_communication( 1076): TIMA: path = /firmware/image, fname = tz_ccm, tzapp is loaded
I/TZ: client_server_communication(  875): OpenSWConn(CCM) is successful
I/TZ: client_server_communication(  875): Client_Server_Open succeeded, serverName = CCM
I/TZ_CCM_C_Initialize: (  875): ctx = 0x93398830, comm = 0x8c019280, sendmsg = 0x8c038000, recvmsg = 0x8c03cc00
I/TZ_init: (  875): TZ_init: sending initialization request...
I/TZ: client_server_communication(  875): Cmd id = 2, len = 19456
I/TZ: client_server_communication(  875): Calling Communicate()
I/TZ_CCM_SERVER( 1076): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1076): COMM
I/TZ_init: (  875): TZ_init: successful initialization
I/TLC_TZ_COMMON: key_db_init: (  875): Exercising TZ_DB_INIT in TLC
I/TZ: client_server_communication(  875): Cmd id = 17, len = 19456
I/TZ: client_server_communication(  875): Calling Communicate()
I/TZ_CCM_SERVER( 1076): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1076): COMM
I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/TZ_COMMON: tlc_key_db_util: (  875): DB Operation suceeded
I/TLC_TZ_CCM: register for default cert: (  875): Exercising TZ_CCM_register_default_TLC
I/TZ: client_server_communication(  875): Cmd id = 25, len = 19456
I/TZ: client_server_communication(  875): Calling Communicate()
I/TZ_CCM_SERVER( 1076): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1076): COMM
I/TLC_TZ_CCM: register for default cert: (  875): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: (  875): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
I/TZ_CCM_C_Finalize: (  875): DEBUG_CONTAINER_PROBLEM Exercising TZ_CCM_C_Finalize_TLC
I/TZ: client_server_communication(  875): Cmd id = 41, len = 19456
I/TZ: client_server_communication(  875): Calling Communicate()
I/TZ_CCM_SERVER( 1076): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1076): COMM
I/TZ: client_server_communication(  875): Client_Server_Close was called
I/TZ_CCM_SERVER( 1076): BnCCM::onTransact(1) 16
I/TZ_CCM_SERVER( 1076): CLOSESWCONN
D/QSEECOMAPI: ( 1076): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1076): QSEECom_shutdown_app, app_id = 3
I/TZ: client_server_communication(  875): Client_Server_Close succeeded
D/UMC:CloudMDMSecurity( 7376): ccmRegisterForDefaultCertificate: 0
D/UMC:CloudMDMSecurity( 7376): TIMA service call for password change success!!
D/UMC:AdminManager( 7376): init - start
D/Finsky  ( 6593): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6593): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6593): [1] 5.onFinished: Scheduling replication attempt 2.
D/UMC:AdminManager( 7376): loadAdmins
D/UMC:AdminManager( 7376): startPolicyHandlers
I/UMC:TestPolicyHandler( 7376): Setup is called in testpolicyhandler
D/UMC:AdminManager( 7376): init - end
V/UMC:AlarmHandler( 7376): Enter loadList
D/GSLBManager( 7376): migrateStoredUrlFromOldPref
D/GSLBManager( 7376): migrateStoredUrlFromOldPref : Migration Not Needed
D/UMC:UMCAdmin( 7376): deactivateUMCAdminIfNotRequired : -1
E/UMC:Utils( 7376): Admin not found in package com.samsung.knoxpb.mdm
D/UMC:UMCAdmin( 7376): deactivateUMCAdmin : -1
D/UMC:UMCAdmin( 7376): isContainer : 0
W/LicenseLogService(  875): log() failed
D/EnterpriseDeviceManagerService(  875): isManagedProfileUser(): userId = 0
E/UMC:UMCAdmin( 7376): No active admin owned by uid 10179
D/UMC:UMCAdmin( 7376): isContainer : 0
D/UMC:UMCAdmin( 7376): deactivateUMCAdmin - UMC App Admin deactivated
V/UMC:AlarmHandler( 7376): onReceive :Intent { flg=0x14 cmp=com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler (has extras) }
I/ActivityManager(  875): Killing 5048:com.android.providers.calendar/u0a46 (adj 15): bgCount ##41
D/QuickStartReceiver( 7376): Msg Id : 2
D/QuickStartReceiver( 7376): model : SM-G900F
D/QuickStartReceiver( 7376): id : 100
D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4317, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  875): stay LED for fully charged
D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  875): Plugged
I/MotionRecognitionService(  875): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
E/AffinityControl( 7374): AffinityControl: registerfunction enter
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3241): Disconnected process message: 10
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
W/libprocessgroup(  875): failed to open /acct/uid_10046/pid_5048/cgroup.procs: No such file or directory
D/AndroidRuntime( 7374): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  875): inState():  stateMachine is null !!
V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  875): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  875): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  875): mDVFSHelper.acquire()
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7423): MountEmulatedStorage()
E/Zygote  ( 7423): v2
I/libpersona( 7423): KNOX_SDCARD checking this for 10200
I/libpersona( 7423): KNOX_SDCARD not a persona
I/ActivityManager(  875): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7423 uid=10200 gids={50200, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/SELinux ( 7423): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/AndroidRuntime( 7374): Shutting down VM
I/SELinux ( 7423): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7423): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/TimaKeyStoreProvider( 7423): TimaSignature is unavailable
D/ActivityThread( 7423): Added TimaKeyStore provider
V/ActivityManager(  875): Display changed displayId=0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/SurfaceFlinger(  248): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (5/8)
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/SurfaceFlinger(  248): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/8)
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
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager( 7423): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SQLiteSecureOpenHelper( 3562): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3562): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/WebViewFactory( 7423): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7423): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7423): Loading: webviewchromium
,I/LibraryLoader( 7423): Time to load native libraries: 3 ms (timestamps 8457-8460)
I/LibraryLoader( 7423): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7423): Binding Chromium to main looper Looper (main, tid 1) {18c4ba40}
,I/LibraryLoader( 7423): Expected native library version number "",actual native library version number ""
,I/chromium( 7423): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7423): Initializing chromium process, renderers=0
,W/art     ( 7423): Attempt to remove local handle scope entry from IRT, ignoring,
,W/ActivityManager(  875): Activity pause timeout for ActivityRecord{a8f7812 u0 com.test.thalitest/.MainActivity t18}
,W/chromium( 7423): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7423): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium( 7423): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,I/Adreno-EGL( 7423): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7423): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7423): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7423): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7423): Remote Branch: 
I/Adreno-EGL( 7423): Local Patches: 
I/Adreno-EGL( 7423): Reconstruct Branch: 
,D/SSRM:m  (  875): SIOP:: AP = 350, PST = 413, CUR = 300
,W/chromium( 7423): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7423): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7423): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7423): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7423): CordovaWebView is running on device made by: samsung
,W/art     ( 7423): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 7423): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 7423): performCreate Call secproduct feature valuefalse
,D/Activity( 7423): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 7423): Render dirty regions requested: true
,D/ActivityManager(  875): post active user change for 0
D/KnoxTimeoutHandler(  875): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  875): handleActiveUserChange for user 0
,I/SurfaceFlinger(  248): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
,D/StatusBarManagerService(  875): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/StatusBarManagerService(  875): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/OpenGLRenderer( 7423): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7423): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7423): Enabling debug mode 0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/InputMethodManagerService(  875): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,W/ActivityManager(  875): mDVFSHelper.release()
,I/Timeline(  875): Timeline: Activity_windows_visible id: ActivityRecord{a8f7812 u0 com.test.thalitest/.MainActivity t18} time:99092
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/Timeline( 7423): Timeline: Activity_idle id: android.os.BinderProxy@1fdac1b3 time:99097
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,W/IInputConnectionWrapper( 7423): showStatusIcon on inactive InputConnection
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/chromium( 7423): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7423): 
,D/JsMessageQueue( 7423): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7423): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1360632576
D/JX-Cordova( 7423): jxcore cordova android initializing
,E/SMD     (  286): DCD ON
,W/jxcore-log( 7423): Initializing JXcore engine
,W/jxcore-log( 7423): JXcore engine is ready
,W/jxcore-log( 7423): Starting JXcore engine
,E/auditd  ( 2139): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  875): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  875): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7498): MountEmulatedStorage()
E/Zygote  ( 7498): v2
I/libpersona( 7498): KNOX_SDCARD checking this for 1000
I/libpersona( 7498): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7498 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     (  313): Explicit concurrent mark sweep GC freed 8730(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 280us total 22.065ms
,I/SELinux ( 7498): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7498): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7498): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 8.446ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 256us total 11.755ms
,D/TimaKeyStoreProvider( 7498): TimaSignature is unavailable
,D/ActivityThread( 7498): Added TimaKeyStore provider
,D/ResourcesManager( 7498): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,W/jxcore-log( 7423): Platform android
W/jxcore-log( 7423): 
W/jxcore-log( 7423): Process ARCH arm
W/jxcore-log( 7423): 
,D/SecurityLogAgent( 7498):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7498):  SeDenialReceiver : File path = null
,I/ActivityManager(  875): Killing 5897:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  875): failed to open /acct/uid_1000/pid_5897/cgroup.procs: No such file or directory
,I/jxcore-log( 7423): JXcore Cordova bridge is ready!
I/jxcore-log( 7423): 
,W/jxcore-log( 7423): JXcore engine is started
,I/jxcore-log( 7423): Toggling radios to true
I/jxcore-log( 7423): 
,D/BluetoothAdapter( 7423): enable()
,D/BluetoothAdapter( 7423): enable(): BT is already enabled..!
,D/WifiService(  875): New client listening to asynchronous messages
,I/WifiManager( 7423): packageName : com.test.thalitest
,D/SecContentProvider(  875): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  875): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  875): mCursor = null
,D/WifiService(  875): setWifiEnabled: true pid=7423, uid=10200
,E/WifiService(  875): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  875): Permission Denial: getCurrentUser() from pid=7423, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  875): Failed getting userId using ActivityManagerNative
W/WifiService(  875): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7423, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  875): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  875): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  875): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  875): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  875): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  875): name = wifi_on
,I/WifiService(  875): disconnect: pid=7423, uid=10200
,I/jxcore-log( 7423): Radios toggled
I/jxcore-log( 7423): 
,I/wpa_supplicant( 1280): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7423): My device name is: samsung-SM-G900F
I/jxcore-log( 7423): 
,I/wpa_supplicant( 1280): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1280): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1280): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1280): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  875): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1280): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1280): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1280): Disconnected - do not scan
I/wpa_supplicant( 1280): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  875): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  875): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  875): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  875): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  875): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  875): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  875): do suspend true
,D/WifiP2pService(  875): InactiveState{ what=143375 }
,D/WifiP2pService(  875): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  281): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1670): Read error: ssl=0xad342600: I/O error during system call, Connection timed out
,E/WifiStateMachine(  875): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  875): updateNetworkInfo()
D/ConnectivityService(  875): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  875): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,I/WifiTrafficPoller(  875): evaluateTrafficStatsPolling
,I/CLocInfoService(  875): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,V/NativeCrypto( 1670): SSL shutdown failed: ssl=0xad342600: I/O error during system call, Broken pipe
,E/WifiConfigStore(  875): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/WifiStateMachine(  875): Start Disconnecting Watchdog 1
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,I/wpa_supplicant( 1280): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1280): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1280): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1280): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1280): First Scan Start
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  875): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  875): DefaultState{ when=-2ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  875): Forcing reevaluation
,I/wpa_supplicant( 1280): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  875): ConnectModeState: Network connection lost 
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  875): EvaluatingState{ when=-3ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  875): Validated
,E/WifiStateMachine(  875): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine(  875): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  875): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  875): do suspend true
,I/Hs20UtilService( 1302): Starting #6
,I/Hs20UtilService( 1302): Message received 5007
D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiP2pService(  875): InactiveState{ what=143375 }
,D/WifiP2pService(  875): P2pEnabledState{ what=143375 }
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  281): Clearing all IP addresses on wlan0
,D/ConnectivityService(  875): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  875): calling update connectivity
D/ConnectivityService(  875):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  875):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  875): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/EntConnectivity(  875): Not allowed due to - mEnabled false
D/Nat464Xlat(  875): requiresClat: netType=1, connected=false, hasIPv4Address=true
,E/WifiStateMachine(  875): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  875): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  875): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  875): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524292
,I/WifiTrafficPoller(  875): evaluateTrafficStatsPolling
D/WifiStateMachine(  875): updateConfiguredNetworkExpiration - currTime: 1453102504935
,D/WifiStateMachine(  875): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine(  875): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
I/CLocInfoService(  875): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  875): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  875): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  875): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiNetworkAgent(  875): NetworkAgent: NetworkAgent channel lost
,D/TelephonyNetworkFactory( 1478): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/CSLegacyTypeTracker(  875): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  875): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  875): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  875): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  875): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  875): setDetailed state send new extra info"NG700"
,D/ConnectivityService(  875): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SecContentProvider2(  875): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  875): mCursor = null
,D/SmartBondingService(  875): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,V/NetworkStats(  875): updateIfacesLocked()
D/NtpTrustedTime(  875): currentTimeMillis() cache hit
V/NetworkStats(  875): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  875): UpdateStatsForKnox
D/SmartBondingService(  875): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  875): getSBEnabled() enabled =false
D/SmartBondingService(  875): getSBEnabled() enabled =false
D/SmartBondingService(  875): getSBEnabled() enabled =false
,E/ConnectivityService(  875): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,E/ConnectivityService(  875): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/SmartBondingService(  875): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  875): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1171): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 1171): updateDataNetType()
D/StatusBar.NetworkController( 1171): NoService, mRoamingIconId = 0
,D/NtpTrustedTime(  875): currentTimeMillis() cache hit
D/NtpTrustedTime(  875): currentTimeMillis() cache hit
,V/NetworkStats(  875): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  875): currentTimeMillis() cache hit
,V/NetworkStats(  875): performPollLocked() took 9ms
D/NtpTrustedTime(  875): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1171): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/NtpTrustedTime(  875): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/NtpTrustedTime(  875): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/SecContentProvider2(  875): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  875): mCursor = null
,I/Hs20UtilService( 1302): Starting #7
,I/Hs20UtilService( 1302): Message received 5007
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/ConnectivityService(  875): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ApplicationPolicy(  875): updateDataUsageMap
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  875): MasterInitialState.processMessage what=3
D/SmartBondingService(  875): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2011): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/SmartBondingService(  875): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  875): getSBEnabled() enabled =false
D/SmartBondingService(  875): getSBEnabled() enabled =false
D/SmartBondingService(  875): getSBEnabled() enabled =false
I/CLocInfoService(  875): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  875): CLoinfo wifi false
,D/SmartBondingService(  875): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7143): [#DCM#] [DCM_Performance] onReceive completed in time  1473 microsec. 
,W/SLocation(  875): No Active Data Connection
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7143): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7143): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
,I/DCMController( 7143): [#DCM#] setIsConnectedForExtractors 
,I/DBG_DM  ( 3824): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/NetworkMonitor( 5368): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 6777): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6777): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6777): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6777): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6777): noConnectivity : true
,I/DBG_DM  ( 3824): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  875): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7575 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 7575): MountEmulatedStorage()
E/Zygote  ( 7575): v2
I/libpersona( 7575): KNOX_SDCARD checking this for 10002
I/libpersona( 7575): KNOX_SDCARD not a persona
,I/SELinux ( 7575): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7575): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7575): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7575): TimaSignature is unavailable
,D/ActivityThread( 7575): Added TimaKeyStore provider
,D/ResourcesManager( 7575): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  875): Killing 6248:com.sec.providers.settingsearch/u0a168 (adj 15): bgCount ##41
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7592): MountEmulatedStorage()
E/Zygote  ( 7592): v2
I/libpersona( 7592): KNOX_SDCARD checking this for 1000
I/libpersona( 7592): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7592 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7592): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7592): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7592): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7592): TimaSignature is unavailable
,D/ActivityThread( 7592): Added TimaKeyStore provider
,D/ResourcesManager( 7592): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,W/libprocessgroup(  875): failed to open /acct/uid_10168/pid_6248/cgroup.procs: No such file or directory
,V/AlarmManager(  875): waitForAlarm result :4
,I/DIAGMON_AGENT( 7592): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7592): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7592): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7592): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7592): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7592): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7608): MountEmulatedStorage()
,E/Zygote  ( 7608): v2
I/libpersona( 7608): KNOX_SDCARD checking this for 10011
I/libpersona( 7608): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7608 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7608): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7608): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7608): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 1280): nl80211: Received scan results (3 BSSes)
,I/wpa_supplicant( 1280): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 1280): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1280): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1280): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  875): [1,453,102,505,999 ms] noteScanEnd no scan source
,E/WifiStateMachine(  875): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@371064d0 sup_state=SCANNING debouncing=false
,I/CLocInfoService(  875): External Intent Received android.net.wifi.SCAN_RESULTS
,E/WifiStateMachine(  875): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  875): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,E/WifiStateMachine(  875): setDetailed state send new extra info0x
D/SecContentProvider2(  875): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  875): mCursor = null
,D/TimaKeyStoreProvider( 7608): TimaSignature is unavailable
,D/ActivityThread( 7608): Added TimaKeyStore provider
,D/ResourcesManager( 7608): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager(  875): Killing 6734:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,I/wpa_supplicant( 1280): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1280): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1280): Associated with C0.AA.48
,E/WifiStateMachine(  875): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  875): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  875): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  875): mCursor = null
,I/FOTA_Client( 7608): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/wpa_supplicant( 1280): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1280): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  875): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  875): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  875): setDetailed state send new extra info"NG700"
,I/FOTA_Client( 7608): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,D/SecContentProvider2(  875): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  875): mCursor = null
,I/wpa_supplicant( 1280): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1280): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1280): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1280): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1280): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1280): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1280): Blacklist: Clear (temp) 
I/wpa_supplicant( 1280): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  875): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  875): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  875): Network connection established
,D/WifiNative-HAL(  875): callSECApiVoid - ID [50]
,E/WifiStateMachine(  875): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  875): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  875): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  875): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  875): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  875): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  875): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  875): Got NetworkAgent Messenger
D/ConnectivityService(  875): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  875): updateNetworkInfo()
,D/ConnectivityService(  875): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  875): NetworkAgent connected
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  875): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  875): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  875): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  875): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/FOTA_Client( 7608): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7608): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,D/CommandListener(  281): Setting iface cfg
,E/WifiStateMachine(  875): Start Dhcp Watchdog 2
,D/SecContentProvider2(  875): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  875): mCursor = null
,I/FOTA_Client( 7608): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  875): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  875): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService(  875): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,W/libprocessgroup(  875): failed to open /acct/uid_10015/pid_6734/cgroup.procs: No such file or directory
,E/Zygote  ( 7625): MountEmulatedStorage()
E/Zygote  ( 7625): v2
I/libpersona( 7625): KNOX_SDCARD checking this for 10019
I/libpersona( 7625): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7625 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  875): Killing 6756:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,I/SELinux ( 7625): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7625): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7625): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine(  875): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  875): do suspend false
,D/SecContentProvider2(  875): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService(  875): InactiveState{ what=143375 }
D/SecContentProvider2(  875): mCursor = null
D/WifiP2pService(  875): P2pEnabledState{ what=143375 }
,D/TimaKeyStoreProvider( 7625): TimaSignature is unavailable
,D/ActivityThread( 7625): Added TimaKeyStore provider
,D/ResourcesManager( 7625): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,W/libprocessgroup(  875): failed to open /acct/uid_10016/pid_6756/cgroup.procs: No such file or directory
,I/KLMS-2.4.503: ( 7625): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7625): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453102506266
,I/KLMS-2.4.503: ( 7625): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7625): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7625): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  875): Killing 6463:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7640): MountEmulatedStorage()
I/libpersona( 7640): KNOX_SDCARD checking this for 10037
E/Zygote  ( 7640): v2
I/libpersona( 7640): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7640 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7640): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7640): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7640): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7640): TimaSignature is unavailable
,D/ActivityThread( 7640): Added TimaKeyStore provider
,D/ResourcesManager( 7640): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,W/libprocessgroup(  875): failed to open /acct/uid_10034/pid_6463/cgroup.procs: No such file or directory
,I/SO_AGENT( 7640): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5230): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6816): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6816): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6816): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6816): [SLFUCHKMGR] constructor called
,I/SA      ( 6816): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6816): [OR] == isSIMCardReady false ==
,I/SA      ( 6816): [SCU] == networkStateCheck == false
,I/SA      ( 6816): [OR] onReceive END
,E/dhcpcd  ( 7656): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7656): version 5.5.6 starting
,E/dhcpcd  ( 7656): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7660): MountEmulatedStorage()
,E/Zygote  ( 7660): v2
,I/libpersona( 7660): KNOX_SDCARD checking this for 10071
I/libpersona( 7660): KNOX_SDCARD not a persona
I/ActivityManager(  875): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7660 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7660): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
E/SPPClientService( 5230): [[SystemStateMonitorService]] No Active Internet
,I/SELinux ( 7660): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7660): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  875): Killing 4711:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,I/dhcpcd  ( 7656): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7656): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7656): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7656): bssid match
,I/dhcpcd  ( 7656): wlan0: rebinding lease of 192.168.1.135
,I/PowerManagerService(  875): [PWL] Off : 15s ago
,I/PowerManagerService(  875): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  875): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  875): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=875, ws=null) (elapsedTime=1566)
,I/PowerManagerService(  875): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=875, ws=WorkSource{10012}) (elapsedTime=764)
,D/TimaKeyStoreProvider( 7660): TimaSignature is unavailable
,D/ActivityThread( 7660): Added TimaKeyStore provider
,E/SMD     (  286): DCD ON
,D/ResourcesManager( 7660): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7660): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7660): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7660): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/comsamsunglog( 7660): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7660): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7660): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7660): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7660): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7660): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7660): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7660): [KK AccuPhone]>>> ==============================================================================================
W/libprocessgroup(  875): failed to open /acct/uid_10035/pid_4711/cgroup.procs: No such file or directory
,D/SettingsProvider(  875): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  875): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  875): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  875): selectionArgs: false
D/SettingsProvider(  875): selectionArgs: 10071
D/SecContentProvider(  875): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  875): ret = -1
,D/daemonapp( 1330): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7660): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7660): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
D/accuweather( 7660): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7660): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
D/accuweather( 7660): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 7660): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1330): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7660): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1330): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7660): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1330): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7660): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7660): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7685): MountEmulatedStorage()
,E/Zygote  ( 7685): v2
I/libpersona( 7685): KNOX_SDCARD checking this for 1000
I/libpersona( 7685): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7685 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  875): Killing 6064:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/SELinux ( 7685): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7685): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7685): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Watchdog(  875): !@Sync 3
,D/TimaKeyStoreProvider( 7685): TimaSignature is unavailable
,D/ActivityThread( 7685): Added TimaKeyStore provider
,D/ResourcesManager( 7685): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7685): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  875): failed to open /acct/uid_10042/pid_6064/cgroup.procs: No such file or directory
,I/KnoxUsageLogPro( 7685): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7685): premStatus:2
,I/KnoxUsageLogPro( 7685): isEulaShown : false
I/KnoxUsageLogPro( 7685): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7700): MountEmulatedStorage()
E/Zygote  ( 7700): v2
I/libpersona( 7700): KNOX_SDCARD checking this for 10088
I/libpersona( 7700): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7700 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  875): Killing 5709:com.android.mms/u0a50 (adj 15): bgCount ##41
,I/SELinux ( 7700): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7700): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/CountryDetector(  875): No listener is left
,E/SELinux ( 7700): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7700): TimaSignature is unavailable
,D/ActivityThread( 7700): Added TimaKeyStore provider
,D/ResourcesManager( 7700): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  875): failed to open /acct/uid_10050/pid_5709/cgroup.procs: No such file or directory
,I/ActivityManager(  875): Killing 6837:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,D/Headlines( 5512): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5512): getCountryCode(): countryCode = DE
,D/Headlines( 5512): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5512): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 5512): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 5512): queryCategory.  mRequest is not initialized.
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,D/HeadlinesCardManager( 5512): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5512): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5512): requestUpdateNewsWelcomeCard !!! no welcome card
,E/Zygote  ( 7719): MountEmulatedStorage()
E/Zygote  ( 7719): v2
I/libpersona( 7719): KNOX_SDCARD checking this for 10128
I/libpersona( 7719): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7719 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7719): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  875): failed to open /acct/uid_10051/pid_6837/cgroup.procs: No such file or directory
,I/SELinux ( 7719): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7719): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7719): TimaSignature is unavailable
,D/ActivityThread( 7719): Added TimaKeyStore provider
,D/ResourcesManager( 7719): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    (  247): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7719): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  247): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7719): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  247): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7719): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  247): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7719): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7719): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7719): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7719): Loading: webviewchromium
,I/LibraryLoader( 7719): Time to load native libraries: 4 ms (timestamps 4459-4463)
,I/LibraryLoader( 7719): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7719): Binding Chromium to main looper Looper (main, tid 1) {b24957e}
,I/LibraryLoader( 7719): Expected native library version number "",actual native library version number ""
,I/chromium( 7719): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7719): Initializing chromium process, renderers=0
,W/art     ( 7719): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7719): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7719): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7719): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7719): Requires BLUETOOTH permission
,I/Adreno-EGL( 7719): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7719): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7719): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7719): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7719): Remote Branch: 
I/Adreno-EGL( 7719): Local Patches: 
I/Adreno-EGL( 7719): Reconstruct Branch: 
,I/NSApplication( 7719): Starting up...
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,I/jxcore-log( 7423): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7423): 
,E/Zygote  ( 7774): MountEmulatedStorage()
,E/Zygote  ( 7774): v2
I/libpersona( 7774): KNOX_SDCARD checking this for 10138
I/libpersona( 7774): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7774 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  875): Killing 6854:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,I/SELinux ( 7774): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7774): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7774): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  875): failed to open /acct/uid_10058/pid_6854/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7774): TimaSignature is unavailable
,D/ActivityThread( 7774): Added TimaKeyStore provider
,D/ResourcesManager( 7774): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7774): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7774): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7774): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7774): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7774): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7774): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7794): MountEmulatedStorage()
E/Zygote  ( 7794): v2
I/libpersona( 7794): KNOX_SDCARD checking this for 10163
I/libpersona( 7794): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7794 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  875): Killing 6267:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/art     (  313): Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 273us total 13.128ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 397us total 7.751ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 247us total 7.790ms
,I/SELinux ( 7794): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7794): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7794): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7794): TimaSignature is unavailable
,D/ActivityThread( 7794): Added TimaKeyStore provider
,D/ResourcesManager( 7794): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7794): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7794): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7794): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7794): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  875): failed to open /acct/uid_1000/pid_6267/cgroup.procs: No such file or directory
,D/RCPManagerService(  875): exchangeData() failure , invalid userId
,D/RCPManagerService(  875): exchangeData() failure , invalid userId
,D/RCPManagerService(  875): exchangeData() failure , invalid userId
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/RCPManagerService(  875): exchangeData() failure , invalid userId
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,E/Zygote  ( 7818): MountEmulatedStorage()
I/libpersona( 7818): KNOX_SDCARD checking this for 10078
E/Zygote  ( 7818): v2
I/libpersona( 7818): KNOX_SDCARD not a persona
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,I/ActivityManager(  875): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7818 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,I/SELinux ( 7818): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7818): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7818): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7794): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,D/RCPManagerService(  875): exchangeData() failure , invalid userId
,D/RCPManagerService(  875): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 7818): TimaSignature is unavailable
,D/ActivityThread( 7818): Added TimaKeyStore provider
,I/ActivityManager(  875): Killing 6876:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7498): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7498): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7498): StateMachine : Current State = 1
,D/SecurityLogAgent( 7498): StateMachine : Changed Current State = 1
,I/ActivityManager(  875): Killing 6923:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,D/com.peel.receiver.ConnectivityActionReceiver( 5616): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
,D/com.peel.receiver.ConnectivityActionReceiver( 5616): NO active network... no services...
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): last run: 1453102420700 -- System.currentTimeMillis()-last_run: 87187
,D/com.peel.receiver.ConnectivityActionReceiver( 5616): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): ... skip last_72_check
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 7818): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
I/jxcore-log( 7423): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7423): 
,I/jxcore-log( 7423): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7423): 
,E/Zygote  ( 7834): MountEmulatedStorage()
I/libpersona( 7834): KNOX_SDCARD checking this for 10178
E/Zygote  ( 7834): v2
I/libpersona( 7834): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7834 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7834): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7834): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7834): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/jxcore-log( 7423): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7423): 
,D/BadgeProvider( 7818): onCreate
,D/BadgeProvider( 7818): DatabaseHelper
,I/jxcore-log( 7423): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7423): 
,D/TimaKeyStoreProvider( 7834): TimaSignature is unavailable
,D/ActivityThread( 7834): Added TimaKeyStore provider
,I/jxcore-log( 7423): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7423): 
,D/BadgeProvider( 7818): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7818): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7818): sendNotify, [notify] : null
D/BadgeProvider( 7818): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7818): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7818): update, [UpdateCount] : 1
D/Launcher.Model( 1484): reloadBadges entered.
,D/ResourcesManager( 7834): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/jxcore-log( 7423): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7423): 
,W/ActivityManager(  875): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager(  875): Killing 6905:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,W/libprocessgroup(  875): failed to open /acct/uid_10098/pid_6876/cgroup.procs: No such file or directory
,W/libprocessgroup(  875): failed to open /acct/uid_10033/pid_6923/cgroup.procs: No such file or directory
,I/iu.Environment( 2415): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2415): num queued entries: 0
,I/iu.UploadsManager( 2415): num updated entries: 0
,I/iu.SyncManager( 2415): NEXT; no task
,D/ChimeraCfgMgr( 2415): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Hs20UtilService( 1302): Starting #8
I/Hs20UtilService( 1302): Message received 5007
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
,W/libprocessgroup(  875): failed to open /acct/uid_10099/pid_6905/cgroup.procs: No such file or directory
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
,I/jxcore-log( 7423): Test app app.js loaded
I/jxcore-log( 7423): 
,I/chromium( 7423): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 7423): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/WifiStateMachine(  875): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  875): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/ConnectivityService(  875): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/dhcpcd  ( 7656): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,I/dhcpcd  ( 7656): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  875): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  875): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  875): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  875): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  875): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/native  (  875): do suspend true
,D/WifiP2pService(  875): InactiveState{ what=143375 }
D/WifiP2pService(  875): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  875): WifiStateMachine DHCP successful
E/WifiStateMachine(  875): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  875): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  875): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  875): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/WifiStateMachine(  875): Not connected state, yet.
E/WifiStateMachine(  875): VerifyingLinkState enter
,D/WifiStateMachine(  875): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
,D/WifiStateMachine(  875): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  875): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  875): callSECApiInt - ID [210]
,E/WifiStateMachine(  875): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  875): updateNetworkInfo()
,D/ConnectivityService(  875): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  875): Adding iface wlan0 to network 503
,I/CLocInfoService(  875): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  875): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  875): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  875): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  875): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  875): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,I/Hs20UtilService( 1302): Starting #9
,I/Hs20UtilService( 1302): Message received 5007
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  875): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  875): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  875): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  875): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  875): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  875): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
,V/        (  281): QcRouteController
,E/WifiStateMachine(  875): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine(  875): Now, connected state.
,E/WifiStateMachine(  875): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/SMD     (  286): DCD ON
,I/WifiTrafficPoller(  875): evaluateTrafficStatsPolling
,V/        (  281): QcRouteController
,I/CLocInfoService(  875): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
W/NetworkManagementService(  875): route cmd failed: 
W/NetworkManagementService(  875): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '67 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 67 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  875): '
W/NetworkManagementService(  875): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  875): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  875): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  875): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  875): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  875): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  875): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  875): 	at com.android.server.ConnectivityService.updateNetworkInfo(ConnectivityService.java:5997)
W/NetworkManagementService(  875): 	at com.android.server.ConnectivityService.access$1900(ConnectivityService.java:230)
W/NetworkManagementService(  875): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2337)
W/NetworkManagementService(  875): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  875): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  875): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/ConnectivityService(  875): updateSourceRoutes : add src route for:192.168.1.135
V/        (  281): QcRouteController
E/WifiStateMachine(  875): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
E/WifiStateMachine(  875): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/WifiStateMachine(  875): ConnectedState Enter  mScreenOn=false scanperiod=20000
I/WifiTrafficPoller(  875): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  875): mBoosterFLAG : 0
I/WifiTrafficPoller(  875): current booster mode : FullMode
D/WifiNative-HAL(  875): callSECApiVoid - ID [212]
I/CLocInfoService(  875): External Intent Received android.net.wifi.STATE_CHANGE
I/WifiStateMachine(  875): REQUEST_POWER_SAVE_ON
V/        (  281): QcRouteController
D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
I/Hs20UtilService( 1302): Starting #10
I/Hs20UtilService( 1302): Message received 5007
D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
V/        (  281): QcRouteController
,V/        (  281): QcRouteController
I/Hs20UtilService( 1302): Starting #11
I/Hs20UtilService( 1302): Message received 5007
D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
I/WifiStateMachine(  875): callSECApi what=220
D/WifiStateMachine(  875): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
V/        (  281): QcRouteController
V/        (  281): QcRouteController
V/        (  281): QcRouteController
,V/        (  281): QcRouteController
,I/SurfaceFlinger(  248): id=16 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PowerManagerService(  875): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=875
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  875): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  875): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  875): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  875): calling update connectivity
,D/ConnectivityService(  875): ignoring duplicate network state non-change
,E/ConnectivityService(  875): updateNetworkInfo()
D/ConnectivityService(  875): ignoring duplicate network state non-change
E/ConnectivityService(  875): updateNetworkInfo()
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  875): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  875): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  875): calling update connectivity
D/ConnectivityService(  875): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  875): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  875): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  875): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  875): Validated
D/ConnectivityService(  875):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  875):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  875):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  875): currentScore = 0, newScore = 60
,D/ConnectivityService(  875):    accepting network in place of null
D/ConnectivityService(  875): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1478): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  875): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  875): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  875): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/ConnectivityService(  875): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  875): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/SmartBondingService(  875): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  875): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  875): getSBEnabled() enabled =false
D/SmartBondingService(  875): getSBEnabled() enabled =false
V/NetworkStats(  875): updateIfacesLocked()
D/NtpTrustedTime(  875): currentTimeMillis() cache hit
V/NetworkStats(  875): performPollLocked(flags=0x1)
,D/SmartBondingService(  875): getSBEnabled() enabled =false
D/NetworkStatsFactory(  875): UpdateStatsForKnox
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  875): performPollLocked() took 3ms
D/NtpTrustedTime(  875): currentTimeMillis() cache hit
,D/SmartBondingService(  875): getNetworkEnabled : wifi : true mobile : true
D/EntConnectivity(  875): Not allowed due to - mEnabled false
D/ConnectivityService(  875): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  875): calling update connectivity
,D/ConnectivityService(  875):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  875):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NtpTrustedTime(  875): currentTimeMillis() cache hit
D/NtpTrustedTime(  875): currentTimeMillis() cache hit
D/NtpTrustedTime(  875): currentTimeMillis() cache hit
V/NetworkStats(  875): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  875): currentTimeMillis() cache hit
D/ConnectivityService(  875): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  875): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524290
D/ConnectivityService(  875): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  875):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  875):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  875): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  875): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  875): calling update connectivity
,D/ConnectivityService(  875):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  875):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/StatusBar.NetworkController( 1171): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1171): updateDataNetType()
D/StatusBar.NetworkController( 1171): NoService, mRoamingIconId = 0
D/ConnectivityService(  875): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  875): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524290
,D/NtpTrustedTime(  875): currentTimeMillis() cache hit
,D/NtpTrustedTime(  875): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1171): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/StatusBar.NetworkController( 1171): getUpdateDataNetType(): 0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/StatusBar.NetworkController( 1171): updateDataNetType()
D/StatusBar.NetworkController( 1171): NoService, mRoamingIconId = 0
D/LockPatternUtilsCache( 1171): value : false
,D/StatusBar.NetworkController( 1171): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
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
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7423): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7423): BLE advertisement is supported
I/jxcore-log( 7423): 
,D/ConnectivityService(  875): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  875): MasterInitialState.processMessage what=3
,D/SmartBondingService(  875): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  875): SmartBondingReceiver: wifi is connected
,D/SmartBondingService(  875): SmartBondingReceiver: wifi ap is not changed
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  875): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  875): getSBEnabled() enabled =false
D/SmartBondingService(  875): getSBEnabled() enabled =false
,D/SmartBondingService(  875): getSBEnabled() enabled =false
,I/CLocInfoService(  875): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  875): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  875): CLocinfo wifi true 
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2216): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2216): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7143): [#DCM#] [DCM_Performance] onReceive completed in time  685 microsec. 
,D/accuweather( 2011): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SystemBroadcastReceiver( 7143): [#DCM#] Calling notifyListeners. 
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DCMController( 7143): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7143): [#DCM#] setIsConnectedForExtractors 
I/NetworkMonitor( 5368): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 6777): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6777): sales region : global
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 6777): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6777): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DatabaseRebuilderTask( 7143): [#DCM#] postDBrebuildIntent rebuildLocation =  true
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3824): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3824): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FrameworkService( 7143): [#DCM#] onCreate FrameworkService 
,I/FrameworkService( 7143): [#DCM#] onCreate FrameworkService end 
,I/DCMConfig( 7143): [#DCM#] getSuccessState = true
I/FrameworkService( 7143): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
,I/IntentHandler( 7143): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,I/DIAGMON_AGENT( 7592): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7592): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/SystemUtils( 7143): [#DCM#] LM: false,AM:673640448
,I/art     (  875): Explicit concurrent mark sweep GC freed 72228(4MB) AllocSpace objects, 7(112KB) LOS objects, 30% free, 36MB/52MB, paused 1.835ms total 163.690ms
,D/SecContentProvider2(  875): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  875): mCursor = null
,I/DCMThreadPoolExecutor( 7143): [#DCM#] Task being added DatabaseRebuilderTask
,I/DCMThreadPoolExecutor( 7143): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@4177da3 is submitted
,I/FrameworkService( 7143): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 210223 mirosec. 
,D/ConnectivityService(  875): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/FOTA_Client( 7608): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/FOTA_Client( 7608): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7608): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7608): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,D/PackageManager(  875): [MSG] SEND_PENDING_BROADCAST
,I/FOTA_Client( 7608): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,D/ResourcesManager(  875): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  875): stay LED for fully charged
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,I/InputReader(  875): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/KLMS-2.4.503: ( 7625): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/dhcpcd  ( 7656): wlan0: sending IPv6 Router Solicitation
,I/KLMS-2.4.503: ( 7625): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453102510849
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/RegisteredServicesCache( 1471): empty dynamic service
,I/KLMS-2.4.503: ( 7625): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/KLMS-2.4.503: ( 7625): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/KLMS-2.4.503: ( 7625): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7625): NetworkChangeOperations(): uploadRequestLog().START 
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/KLMS-2.4.503: ( 7625): StateImplV2(): networkChangeListener().END
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/SecContentProvider2(  875): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  875): mCursor = null
,I/SO_AGENT( 7640): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/SPPClientService( 5230): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6816): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6816): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 6816): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6816): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6816): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6816): [SCU] == networkStateCheck == true
,I/SA      ( 6816): [DM] getCountryCodeFromCSC : DE
I/SA      ( 6816): isChinaCountryCode : false
I/SA      ( 6816): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6816): [OR] == networkStateCheck true ==
,I/SA      ( 6816): [OR] GetMyCountryZoneTask
,I/SA      ( 6816): [OR] onReceive END
,I/SA      ( 6816): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6816): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6816): [SSP] query invoked
,D/accuweather( 7660): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7660): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro( 7685): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7685): premStatus:2
,D/BackupManagerService(  875): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  875): Plugged
I/MotionRecognitionService(  875): setPowerConnected  = true
,I/KnoxUsageLogPro( 7685): isEulaShown : false
I/KnoxUsageLogPro( 7685): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,I/SA      ( 6816): [TPMU] GetMccFromDB : null
I/SA      ( 6816): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6816): [TPM] isNoProxy(default) : true
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,E/File    ( 6816): fail readDirectory() errno=2
,D/Headlines( 5512): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 5512): getCountryCode(): countryCode = DE
,D/Headlines( 5512): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5512): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5512): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5512): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5512): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5512): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5512): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ResourcesManager(  875): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  875): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ResourcesManager(  875): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/QuickConnect( 7774): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7774): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7774): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  875): exchangeData() failure , invalid userId
,D/RCPManagerService(  875): exchangeData() failure , invalid userId
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7498): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7498): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7498): StateMachine : Current State = 1
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7498): StateMachine : Changed Current State = 1
,D/ResourcesManager(  875): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/com.peel.receiver.ConnectivityActionReceiver( 5616): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
,D/com.peel.receiver.ConnectivityActionReceiver( 5616): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): last run: 1453102420700 -- System.currentTimeMillis()-last_run: 90566
D/com.peel.receiver.ConnectivityActionReceiver( 5616): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): ... skip last_72_check
,D/ResourcesManager(  875): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/iu.Environment( 2415): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2415): num queued entries: 0
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/iu.UploadsManager( 2415): num updated entries: 0
,I/iu.SyncManager( 2415): NEXT; no task
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,D/ChimeraCfgMgr( 2415): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ChimeraCfgMgr( 2415): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7119): notifyNetworkActivated
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,W/ContextImpl( 7119): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
D/SecContentProvider2(  875): mCursor = null
W/ActivityManager(  875): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2415): [AccountUtils] Account not ready
W/Kids    ( 2415): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2415): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2415): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2415): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2415): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2415): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2415): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2415): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2415): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2415): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2415): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2415): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,D/GCM     ( 1670): Connected
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1670): Message class com.google.f.a.a.p
D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  875): SIOP:: AP = 400, PST = 410, CUR = 300
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,D/hcjo    ( 7119): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7119): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7119): exit::IDLE
D/InitializeManagerStateMachine( 7119): entry::NETWORK_CHECK
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7119): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 7119): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7119): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7119): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7119): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7119): entry::SUCCESS
,D/hcjo    ( 7119): AutoUpdateManager:INITCHECK:onInitializeSuccess
,E/Zygote  ( 7969): MountEmulatedStorage()
E/Zygote  ( 7969): v2
I/libpersona( 7969): KNOX_SDCARD checking this for 10034
I/libpersona( 7969): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7969 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 7969): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/hcjo    ( 7119): AutoUpdateTriggerManager:IDLE:notifyNextTime
I/SELinux ( 7969): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/hcjo    ( 7119): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7119): exit::SUCCESS
D/InitializeManagerStateMachine( 7119): entry::IDLE
,E/SELinux ( 7969): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7969): TimaSignature is unavailable
,D/ActivityThread( 7969): Added TimaKeyStore provider
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/FeatureConfig( 7969): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 7969): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 7969): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7969): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 7969): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 7969): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 7969): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 7969): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7969): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 7969): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7969): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 7969): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7969): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 7969): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/GAV4    ( 7719): Thread[GAThread,5,main]: No campaign data found.
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7988): MountEmulatedStorage()
,E/Zygote  ( 7988): v2
,I/libpersona( 7988): KNOX_SDCARD checking this for 10035
I/libpersona( 7988): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=7988 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 7988): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7988): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7988): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7988): TimaSignature is unavailable
,D/ActivityThread( 7988): Added TimaKeyStore provider
,D/ResourcesManager( 7988): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/SA      ( 6816): [RC New] Execute method=[GET] start
,I/SA      ( 6816): [RC New] Security=[true]
,I/System.out( 6816): Thread-1110(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6816): Thread-1110(ApacheHTTPLog):isShipBuild true
,I/System.out( 6816): Thread-1110(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/SMD     (  286): DCD ON
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): checkState() : APP TYPE = Full
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8010): MountEmulatedStorage()
E/Zygote  ( 8010): v2
I/libpersona( 8010): KNOX_SDCARD checking this for 10017
I/libpersona( 8010): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=8010 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,I/SELinux ( 8010): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8010): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8010): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8010): TimaSignature is unavailable
,D/ActivityThread( 8010): Added TimaKeyStore provider
,D/ResourcesManager( 8010): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/WifiStateMachine(  875): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  875): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/BluetoothManager( 7988): getConnectedDevices
,D/-----SIC-----( 7988): ------------------skip uv
,D/-----SIC-----( 7988): ------------------skip SPO2
,D/-----SIC-----( 7988): ------------------skip TGH
,I/SecureStorage( 8010): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  330): [INFO]: SPID(0x00000005)Credentials: uid 10017, gid 10017, pid 8010
I/SecureStorage(  330): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,E/Vold    (  247): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7988): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,E/Vold    (  247): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7988): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,V/MediaPlayer( 7988): decode(32, 19359868, 4230)
,V/MediaPlayerService(  292): decode(32, 19359868, 4230)
,V/MediaPlayerService(  292): player type = 3
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
V/AwesomePlayer(  292): setDefault
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19359868, 4230)
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
,I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
,V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
,I/SecMediaClock(  292): SecMediaClock constructor
,I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/ActivityManager(  875): Killing 6967:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
,V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 200, 973, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
,I/AudioPlayer(  292): First fillBuffer call!!
V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
,V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 2, 0, 0)
,V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 7, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x74, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
,I/SurfaceFlinger(  248): id=16 Removed Toast (8/9)
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
I/SurfaceFlinger(  248): id=16 Removed Toast (-2/9)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,V/MediaPlayer( 7988): decode(36, 19213040, 15440)
,V/MediaPlayerService(  292): decode(32, 19213040, 15440)
,V/MediaPlayerService(  292): player type = 3
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,D/PowerManagerService(  875): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 875) eventTime = 110288
,V/AwesomePlayer(  292): setDefault
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
D/PowerManagerService(  875): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=875 (0x0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
,V/AwesomePlayer(  292): setListener
D/PowerManagerService(  875): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=875, ws=WorkSource{10059}) (elapsedTime=3496)
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
,V/StagefrightPlayer(  292): setDataSource(32, 19213040, 15440)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0f1c330, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,D/AdaptiveEventManager( 1171): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/AdaptiveEventManager( 1171): M updateContainers()
D/AdaptiveEventContainerSmall( 1171): C updatePedoContainer()
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
D/AdaptiveEventContainerSmall( 1171): handlePedoUpdate()
,D/AdaptiveEventContainerSmall( 1171): pedoEvent == null
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,E/DatabaseUtils(  875): Writing exception to parcel
E/DatabaseUtils(  875): java.lang.NullPointerException: key == null
E/DatabaseUtils(  875): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils(  875): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils(  875): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils(  875): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/DatabaseUtils(  875): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils(  875): 	at android.os.Binder.execTransact(Binder.java:446)
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/AdaptiveEventManager( 1171): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
,D/AdaptiveEventManager( 1171): M updateContainers()
D/AdaptiveEventContainerSmall( 1171): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1171): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1171): pedoEvent == null
,I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 6, 0, 0)
V/AudioCache(  292): ignored
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
V/AwesomePlayer(  292): addBatteryData
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
I/AudioPlayer(  292): First fillBuffer call!!
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
V/MediaPlayerService(  292): wait for playback complete
,I/UpdateIcingCorporaServi( 1551): Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,E/Zygote  ( 8066): MountEmulatedStorage()
E/Zygote  ( 8066): v2
I/libpersona( 8066): KNOX_SDCARD checking this for 10075
I/libpersona( 8066): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=8066 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
,V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 2, 0, 0)
,V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x75, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7988): decode(35, 19257568, 9226)
,I/SELinux ( 8066): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8066): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8066): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/MediaPlayerService(  292): decode(32, 19257568, 9226)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19257568, 9226)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/ActivityManager(  875): Killing 6980:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
,V/MediaPlayerService(  292): wait for prepare
,V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
,V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,W/libprocessgroup(  875): failed to open /acct/uid_10020/pid_6967/cgroup.procs: No such file or directory
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 200, 973, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
,I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x76, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,D/TimaKeyStoreProvider( 8066): TimaSignature is unavailable
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,D/ActivityThread( 8066): Added TimaKeyStore provider
I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/MediaPlayer( 7988): decode(37, 19364180, 4890)
,V/MediaPlayerService(  292): decode(32, 19364180, 4890)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19364180, 4890)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/ResourcesManager( 8066): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x77, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7988): decode(38, 19290344, 17329)
V/MediaPlayerService(  292): decode(32, 19290344, 17329)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19290344, 17329)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/SA      ( 6816): [RC New] [v2liruge] api execute + 773
I/SA      ( 6816): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 6816): AsyncTask #1 calls detatch()
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(2)
,I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
I/AudioPlayer(  292): First fillBuffer call!!
V/AudioCache(  292): notify(0xb0b546f0, 6, 0, 0)
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
,V/MediaPlayerService(  292): wait for playback complete
I/SA      ( 6816): [ODM] saveOpenData( GEO_IP, PL )
,D/FileShare-Server( 8066): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,I/UpdateIcingCorporaServi( 1551): UpdateCorporaTask done [took 140 ms] updated apps [took 140 ms] 
,I/SA      ( 6816): [OCP] update openData : PL
,I/SA      ( 6816): [TPMU] getNetworkMcc : 
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,I/SA      ( 6816): [SCU] saveMccToPreferece Start
V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,I/SA      ( 6816): [SCU] RegionMCC : 260
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
,I/SA      ( 6816): [SSP] query invoked
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x78, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
,V/StagefrightPlayer(  292): ~StagefrightPlayer
I/SA      ( 6816): [TPMU] GetMccFromDB : null
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
I/SA      ( 6816): [SCU] getMccFromPreferece mcc = 260
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear,
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
,I/SA      ( 6816): [SCU] saveMccToPreferece End
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,I/SA      ( 6816): [RC New] executeRequest [v2liruge] end. 872
I/SA      ( 6816): [RC New] Execute end
V/MediaPlayer( 7988): decode(39, 19190536, 6644)
V/MediaPlayerService(  292): decode(32, 19190536, 6644),
V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  292): mAudioTrackVector clear
I/libpersona( 8093): KNOX_SDCARD checking this for 1000
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/libpersona( 8093): KNOX_SDCARD not a persona
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
I/ActivityManager(  875): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=8093 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener,
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19190536, 6644)
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 8, 0, 0)
V/AudioCache(  292): ignored
I/ActivityManager(  875): Killing 6997:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4,
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare,
I/SA      ( 6816): [OR] GetMyCountryZoneTask mcc = 260
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
,I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
,V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
E/Zygote  ( 8093): MountEmulatedStorage()
E/Zygote  ( 8093): v2
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder',
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/SA      ( 6816): [OR] GetMyCountryZoneTask Success
,I/SELinux ( 8093): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/SELinux ( 8093): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8093): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
W/libprocessgroup(  875): failed to open /acct/uid_10003/pid_6980/cgroup.procs: No such file or directory
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
I/AudioPlayer(  292): First fillBuffer call!!
V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x79, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7988): decode(40, 19266876, 23389)
V/MediaPlayerService(  292): decode(32, 19266876, 23389)
V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19266876, 23389)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA,_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
D/TimaKeyStoreProvider( 8093): TimaSignature is unavailable
D/ActivityThread( 8093): Added TimaKeyStore provider
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
D/ResourcesManager( 8093): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
W/libprocessgroup(  875): failed to open /acct/uid_1000/pid_6997/cgroup.procs: No such file or directory
I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7988): decode(42, 19156232, 8154)
D/ShortcutReceiver( 8093):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
V/MediaPlayerService(  292): decode(32, 19156232, 8154)
V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19156232, 8154)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
I/AudioPlayer(  292): First fillBuffer call!!
V/MediaPlayerService(  292): wait for playback complete
,I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7988): decode(41, 19129712, 4804)
V/MediaPlayerService(  292): decode(32, 19129712, 4804)
V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19129712, 4804)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
I/ActivityManager(  875): Killing 7015:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7988): decode(43, 19099164, 9400)
V/MediaPlayerService(  292): decode(32, 19099164, 9400)
V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19099164, 9400)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
D/PackageBroadcastService( 2415): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayer( 7988): decode(49, 19172584, 4112)
V/MediaPlayerService(  292): decode(35, 19172584, 4112)
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(35, 19172584, 4112)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(37) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
V/AwesomePlayer(  292): finishAsyncPrepare_l
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 1, 0, 0)
V/AudioC,ache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthServiceInstalled() : HealthService is Installed.
V/MediaPlayerService(  292): wait for playback complete
D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
,I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
I/SecMediaClock(  292): SecMediaClock destructor
,V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/MediaPlayer( 7988): decode(44, 19307764, 52024)
V/MediaPlayerService(  292): decode(32, 19307764, 52024)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19307764, 52024)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
,V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
,I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
,V/AudioPolicyManager(  292): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
I/PeopleContactsSync( 2415): CP2 sync disabled
V/AudioCache(  292): notify(0xb0d14150, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(48000, 2, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 6, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
,I/AudioPlayer(  292): First fillBuffer call!!
,W/libprocessgroup(  875): failed to open /acct/uid_10112/pid_7015/cgroup.procs: No such file or directory
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
,V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
,V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7988): decode(45, 19172584, 4112)
,V/MediaPlayerService(  292): decode(32, 19172584, 4112)
V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
,V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(32, 19172584, 4112)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0b546f0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
,I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
,V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
,V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
,I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 200, 973, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0b546f0, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
,V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  292): Audio channels(1)
,I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
,V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
,V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 2, 0, 0)
,V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 7, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
,V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b546f0, 8, 0, 0)
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
,I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
,V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/MediaPlayer( 7988): decode(46, 19235660, 21825)
V/MediaPlayerService(  292): decode(33, 19235660, 21825)
V/MediaPlayerService(  292): player type = 3
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
,V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
,V/StagefrightPlayer(  292): setDataSource(33, 19235660, 21825)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 8, 0, 0)
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,D/Utils   (  292): printFileName fd(34) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
,V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
,V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
,V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
,V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0f1c330, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 1, 0, 0)
V/AudioCache(  292): prepared
,V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 6, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): addBatteryData
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
V/MediaPlayerService(  292): wait for playback complete
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
,V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0f1c330, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
,V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0f1c330, 8, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
,I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
,I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out,
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
,I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
,V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted,
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
I/SecureStorage(  330): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage(  330): [INFO]: SPID(0x00000005)PID: 8010, TID: 8022
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0),
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/MediaPlayer( 7988): decode(47, 19134596, 21552)
V/MediaPlayerService(  292): decode(32, 19134596, 21552)
V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
,V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
,V/StagefrightPlayer(  292): setDataSource(32, 19134596, 21552)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0b54420, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
,I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder,
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
,V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
,V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0),
V/AudioCache(  292): notify(0xb0b54420, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 1, 0, 0)
,V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start,
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 6, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): addBatteryData
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
V/MediaPlayerService(  292): wait for playback complete
,E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
,V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0b54420, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
,V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0b54420, 8, 0, 0)
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
,I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
,I/OggExtractor(  292): ~OggExtractor --
I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset,
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7988): decode(48, 19228560, 7017)
V/MediaPlayerService(  292): decode(32, 19228560, 7017)
V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
,V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
,V/StagefrightPlayer(  292): setDataSource(32, 19228560, 7017)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 8, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
,V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
,V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
,V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
,V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 5, 0, 0)
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
,V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete,
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0d14150, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0d14150, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
,I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
,I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,I/SecureStorage( 8010): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 8010): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
,I/SecSQLiteOpenHelper( 7988): getWritableDatabase(pwd)
,I/SecSQLiteOpenHelper( 7988): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper( 7988): Open platform.db in secure mode
,D/SecSQLiteDatabase( 7988): Android Version: 5.0
D/SecSQLiteDatabase( 7988): Load library secsqlite.so for Android 5.0
,I/SecSQLiteDatabase( 7988): openSecureDatabase...
,I/SecSQLiteDatabase( 7988): private openSecureDatabase...
I/SecSQLiteConnectionPool( 7988): OpenSecure
I/SecSQLiteConnectionPool( 7988): OpenSecure with password
I/SecSQLiteConnectionPool( 7988): openSecureConnectionLocked
,I/SecSQLiteDatabase( 7988): ...private openSecureDatabase
,I/SecSQLiteDatabase( 7988): ...openSecureDatabase
,I/SecSQLiteOpenHelper( 7988): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper( 7988): ...getDatabaseLocked(b,b,pwd)
,W/System.err( 7988): java.lang.NumberFormatException: Invalid int: "null"
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7988): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,W/System.err( 7988): 	at java.lang.Integer.invalidInt(Integer.java:138)
W/System.err( 7988): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err( 7988): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err( 7988): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:449)
W/System.err( 7988): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1173)
,W/System.err( 7988): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7988): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7988): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/dhcpcd  ( 7656): wlan0: sending IPv6 Router Solicitation
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6777): mConnectivityHandler : connected
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6777): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 6777): ================================================
,I/CSTORAGE( 6777):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
,I/CSTORAGE( 6777): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6777): [GetString-S]
,E/art     ( 6777): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6777): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6777): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6777): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6777): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 6777): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6777): [ensureRegistration] - No Samsung account
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/GAV3    ( 7988): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/dhcpcd  ( 7656): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7656): wlan0: no IPv6 Routers available
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/FactoryTest( 6703): Not factory mode
,D/FactoryTest( 6703): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6703): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6703): still no open session command from host, so toast
,W/ContextImpl( 6703): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6703): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6703): Timeline: Activity_launch_request id:com.android.settings time:117738
,E/PersonaManagerService(  875): inState():  stateMachine is null !!
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  875): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  875): mDVFSHelper.acquire()
,V/AlarmManager(  875): waitForAlarm result :4
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/MTPRx   ( 6703): started activity for popup
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,V/AlarmManager(  875): waitForAlarm result :4
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SQLiteSecureOpenHelper( 3562): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3562): getDatabaseLocked(b,b,pwd)...
,D/ResourcesManager( 6703): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6703): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6703): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6703): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6703): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6703): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6703): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6703): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6703): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/InputMethodManagerService(  875): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  875): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@104d3dae attribute=null, token = android.os.BinderProxy@f9b8a4b
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6703): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6703): dev.kiessupport is : TRUE
,D/Activity( 6703): performCreate Call secproduct feature valuefalse
D/Activity( 6703): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ActivityManager(  875): post active user change for 0
D/KnoxTimeoutHandler(  875): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  875): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/Timeline( 7423): Timeline: Activity_idle id: android.os.BinderProxy@1fdac1b3 time:118240
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  875): waitForAlarm result :4
,I/PowerManagerService(  875): [PWL] Off : 30s ago
,I/PowerManagerService(  875): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  875): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  875): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=875, ws=WorkSource{10012}) (elapsedTime=23)
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
,I/MotionRecognitionService(  875): setPowerConnected  = true
,D/BatteryService(  875): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  875): SIOP:: AP = 360, PST = 399, CUR = 300
,D/X       (  875): broadcastSiopLevelIntent:: currentSiopLevel = -1
,D/ContentApp( 1223):  LEVEL : -1
,I/SystemBroadcastReceiver( 7143): [#DCM#] [DCM_Performance] onReceive completed in time  604 microsec. 
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,I/SystemBroadcastReceiver( 7143): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7143): [#DCM#] onReceive action = EVENT_SIOP
,E/Zygote  ( 8214): MountEmulatedStorage()
E/Zygote  ( 8214): v2
I/libpersona( 8214): KNOX_SDCARD checking this for 10054
I/libpersona( 8214): KNOX_SDCARD not a persona
,D/PreloadUpdateManagerStateMachine( 7119): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 7119): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7119): entry::CHECK_TIMEOUT_FOR_UPDATE
,I/ActivityManager(  875): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=8214 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,I/SELinux ( 8214): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/hcjo    ( 7119): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,I/SELinux ( 8214): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8214): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/hcjo    ( 7119): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 7119): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7119): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7119): entry::IDLE
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 8214): TimaSignature is unavailable
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/ActivityThread( 8214): Added TimaKeyStore provider
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 8214): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8214): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8214): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8214): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8214): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8214): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/Finsky  ( 6593): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6593): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6593): [1] 5.onFinished: Scheduling replication attempt 3.
,E/TranscodeReceiver( 8214): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 8214): core_num = 4
,W/linker  ( 8214): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 8214): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 8214): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
,D/videowall-Global( 8214): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 8214):  SIOP_LEVEL: -1
,I/ActivityManager(  875): Killing 7033:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,W/libprocessgroup(  875): failed to open /acct/uid_10118/pid_7033/cgroup.procs: No such file or directory
,W/ActivityManager(  875): mDVFSHelper.release()
,E/SMD     (  286): DCD ON
,I/ActivityManager(  875): Waited long enough for: ServiceRecord{7a8e3c9 u0 com.samsung.dcm/.framework.FrameworkService}
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
,I/MotionRecognitionService(  875): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/BatteryService(  875): stay LED for fully charged
,D/SSRM:m  (  875): SIOP:: AP = 330, PST = 384, CUR = 300
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,E/Watchdog(  875): !@Sync 4
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/PowerManagerService(  875): [PWL] Off : 50s ago
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  875): SIOP:: AP = 320, PST = 368, CUR = 300
,V/AlarmManager(  875): waitForAlarm result :4
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6593): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6593): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6593): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 320, PST = 356, CUR = 300
,V/AlarmManager(  875): waitForAlarm result :4
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  875): stay LED for fully charged
,D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
,I/MotionRecognitionService(  875): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1670): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6559): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6559): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6559): 	at kfv.a(PG:65)
E/HttpOperation( 6559): 	at kff.u(PG:385)
E/HttpOperation( 6559): 	at kfb.a(PG:29)
E/HttpOperation( 6559): 	at kff.l(PG:132)
E/HttpOperation( 6559): 	at dsf.a(PG:807)
E/HttpOperation( 6559): 	at fhk.a(PG:1126)
E/HttpOperation( 6559): 	at fhk.a(PG:908)
E/HttpOperation( 6559): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6559): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6559): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6559): 	at ihi.a(PG:22)
E/HttpOperation( 6559): 	at kft.a(PG:91)
E/HttpOperation( 6559): 	at kfv.a(PG:62)
E/HttpOperation( 6559): 	... 8 more
E/HttpOperation( 6559): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6559): 	at gde.c(Unknown Source)
E/HttpOperation( 6559): 	at gde.b(Unknown Source)
E/HttpOperation( 6559): 	at ihi.a(PG:19)
E/HttpOperation( 6559): 	... 10 more
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6559): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6559): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6559): 	at kfv.a(PG:65)
E/HttpOperation( 6559): 	at kff.u(PG:385)
E/HttpOperation( 6559): 	at kfb.a(PG:29)
E/HttpOperation( 6559): 	at kff.l(PG:132)
E/HttpOperation( 6559): 	at ieo.a(PG:43)
E/HttpOperation( 6559): 	at iep.a(PG:93)
E/HttpOperation( 6559): 	at fhn.a(PG:59)
E/HttpOperation( 6559): 	at lex.a(PG:85)
E/HttpOperation( 6559): 	at lex.b(PG:132)
E/HttpOperation( 6559): 	at fhk.a(PG:1146)
E/HttpOperation( 6559): 	at fhk.a(PG:908)
E/HttpOperation( 6559): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6559): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6559): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6559): 	at ihi.a(PG:22)
E/HttpOperation( 6559): 	at kft.a(PG:91)
E/HttpOperation( 6559): 	at kfv.a(PG:62)
E/HttpOperation( 6559): 	... 12 more
E/HttpOperation( 6559): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6559): 	at gde.c(Unknown Source)
E/HttpOperation( 6559): 	at gde.b(Unknown Source)
E/HttpOperation( 6559): 	at ihi.a(PG:19)
E/HttpOperation( 6559): 	... 14 more
,E/ExperimentLoader( 6559): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6559): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6559): 	at kfv.a(PG:65)
E/ExperimentLoader( 6559): 	at kff.u(PG:385)
E/ExperimentLoader( 6559): 	at kfb.a(PG:29)
E/ExperimentLoader( 6559): 	at kff.l(PG:132)
E/ExperimentLoader( 6559): 	at ieo.a(PG:43)
E/ExperimentLoader( 6559): 	at iep.a(PG:93)
E/ExperimentLoader( 6559): 	at fhn.a(PG:59)
E/ExperimentLoader( 6559): 	at lex.a(PG:85)
E/ExperimentLoader( 6559): 	at lex.b(PG:132)
E/ExperimentLoader( 6559): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6559): 	at fhk.a(PG:908)
E/ExperimentLoader( 6559): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6559): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6559): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6559): 	at ihi.a(PG:22)
E/ExperimentLoader( 6559): 	at kft.a(PG:91)
E/ExperimentLoader( 6559): 	at kfv.a(PG:62)
E/ExperimentLoader( 6559): 	... 12 more
E/ExperimentLoader( 6559): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6559): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6559): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6559): 	at ihi.a(PG:19)
E/ExperimentLoader( 6559): 	... 14 more
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 6559): [getaccountstatus] Unexpected exception
E/HttpOperation( 6559): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6559): 	at kfv.a(PG:65)
E/HttpOperation( 6559): 	at kff.u(PG:385)
E/HttpOperation( 6559): 	at kfb.a(PG:29)
E/HttpOperation( 6559): 	at ixd.a(PG:248)
E/HttpOperation( 6559): 	at ixd.b(PG:206)
E/HttpOperation( 6559): 	at ixd.a(PG:175)
E/HttpOperation( 6559): 	at fig.a(PG:78)
E/HttpOperation( 6559): 	at lex.a(PG:85)
E/HttpOperation( 6559): 	at lex.b(PG:132)
E/HttpOperation( 6559): 	at fhk.a(PG:1146)
E/HttpOperation( 6559): 	at fhk.a(PG:908)
E/HttpOperation( 6559): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6559): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6559): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6559): 	at ihi.a(PG:22)
E/HttpOperation( 6559): 	at kft.a(PG:91)
E/HttpOperation( 6559): 	at kfv.a(PG:62)
E/HttpOperation( 6559): 	... 12 more
E/HttpOperation( 6559): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6559): 	at gde.c(Unknown Source)
E/HttpOperation( 6559): 	at gde.b(Unknown Source)
E/HttpOperation( 6559): 	at ihi.a(PG:19)
E/HttpOperation( 6559): 	... 14 more
E/EsSyncAdapterService( 6559): Sync failure
E/EsSyncAdapterService( 6559): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6559): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6559): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6559): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6559): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6559): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6559): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6559): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6559): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6559): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6559): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6559): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6559): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6559): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6559): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6559): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6559): 	... 10 more
E/EsSyncAdapterService( 6559): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6559): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6559): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6559): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6559): 	... 12 more
E/EsSyncAdapterService( 6559): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6559): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6559): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6559): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6559): 	... 14 more
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  875): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 149256, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  875): Explicit concurrent mark sweep GC freed 62832(3MB) AllocSpace objects, 23(628KB) LOS objects, 30% free, 36MB/52MB, paused 2.237ms total 238.306ms
,D/SecContentProvider2(  875): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  875): mCursor = null
,E/SQLiteLog( 1670): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  286): DCD ON
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,V/AlarmManager(  875): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  875): SIOP:: AP = 310, PST = 347, CUR = 300
,V/AlarmManager(  875): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6593): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6593): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6593): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,I/PowerManagerService(  875): [PWL] Off : 75s ago
,E/SMD     (  286): DCD ON
,E/Watchdog(  875): !@Sync 5
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 310, PST = 342, CUR = 300,
,E/SMD     (  286): DCD ON
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 310, PST = 337, CUR = 300
,V/AlarmManager(  875): waitForAlarm result :4
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  875): stay LED for fully charged
D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
I/MotionRecognitionService(  875): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7258): Starting books sync, d
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1670): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1670): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1670): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1670): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7258): Authentication error
E/BooksAccountManager( 7258): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7258): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7258): null auth token
,I/qtaguid ( 7258): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7258, getuid(): 10082
,I/qtaguid ( 7258): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7258, getuid(): 10082
,I/qtaguid ( 7258): Untagging socket 34
,W/ApiaryClient( 7258): Error response from books API: {
W/ApiaryClient( 7258):  "error": {
W/ApiaryClient( 7258):   "errors": [
W/ApiaryClient( 7258):    {
W/ApiaryClient( 7258):     "domain": "global",
W/ApiaryClient( 7258):     "reason": "required",
W/ApiaryClient( 7258):     "message": "Login Required",
W/ApiaryClient( 7258):     "locationType": "header",
W/ApiaryClient( 7258):     "location": "Authorization"
W/ApiaryClient( 7258):    }
W/ApiaryClient( 7258):   ],
W/ApiaryClient( 7258):   "code": 401,
W/ApiaryClient( 7258):   "message": "Login Required"
W/ApiaryClient( 7258):  }
W/ApiaryClient( 7258): }
,W/ApiaryClient( 7258): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7258): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4734580487883002511&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7258): Headers suppressed
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  875): waitForAlarm result :4
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GoogleURLConnFactory( 1670): Using platform SSLCertificateSocketFactory
,I/VacuumService( 1670): Vacuum at: now=1453102583627 tag=VacuumService
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1670): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Uploader( 1670): No account for auth token provided
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1670): Explicit concurrent mark sweep GC freed 44974(2MB) AllocSpace objects, 19(1409KB) LOS objects, 39% free, 18MB/30MB, paused 6.700ms total 127.655ms
,I/System.out( 1670): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1670): (HTTPLog)-Static: isShipBuild true
,D/Finsky  ( 6593): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
I/System.out( 1670): (HTTPLog)-Thread-203-4059467: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/Finsky  ( 6593): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6593): [1] 5.onFinished: Giving up after 6 failures.
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 1670): Tagging socket 37 with tag 120100000000{4609,0} uid -1, pid: 1670, getuid(): 10012
,D/ResourcesManager( 1670): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
D/SecContentProvider2(  875): mCursor = null
,D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,I/qtaguid ( 1670): Tagging socket 63 with tag 120100000000{4609,0} uid -1, pid: 1670, getuid(): 10012
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1670): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1670): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1670): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1670): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7258): Authentication error
E/BooksAccountManager( 7258): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7258): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpHelper( 7258): null auth token
,I/qtaguid ( 7258): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7258, getuid(): 10082
,I/qtaguid ( 7258): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7258, getuid(): 10082
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/SMD     (  286): DCD ON
,I/qtaguid ( 7258): Untagging socket 34
,W/ApiaryClient( 7258): Error response from books API: {
W/ApiaryClient( 7258):  "error": {
W/ApiaryClient( 7258):   "errors": [
W/ApiaryClient( 7258):    {
W/ApiaryClient( 7258):     "domain": "global",
W/ApiaryClient( 7258):     "reason": "required",
W/ApiaryClient( 7258):     "message": "Login Required",
W/ApiaryClient( 7258):     "locationType": "header",
W/ApiaryClient( 7258):     "location": "Authorization"
W/ApiaryClient( 7258):    }
W/ApiaryClient( 7258):   ],
W/ApiaryClient( 7258):   "code": 401,
W/ApiaryClient( 7258):   "message": "Login Required"
W/ApiaryClient( 7258):  }
W/ApiaryClient( 7258): }
,W/ApiaryClient( 7258): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7258): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4734580487883002511&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7258): Headers suppressed
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Uploader( 1670): No account for auth token provided
,I/qtaguid ( 1670): Tagging socket 37 with tag 120100000000{4609,0} uid -1, pid: 1670, getuid(): 10012
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
,D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,E/Uploader( 1670): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1670): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1670): ,	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1670): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1670): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1670): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1670): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1670): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1670): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1670): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1670): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1670): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1670): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/qtaguid ( 1670): Tagging socket 37 with tag 120100000000{4609,0} uid -1, pid: 1670, getuid(): 10012
,W/Uploader( 1670): No account for auth token provided
,I/qtaguid ( 1670): Tagging socket 37 with tag 120100000000{4609,0} uid -1, pid: 1670, getuid(): 10012
,W/Uploader( 1670):  no longer exists, so no auth token.
,I/qtaguid ( 1670): Tagging socket 37 with tag 120100000000{4609,0} uid -1, pid: 1670, getuid(): 10012
,E/SQLiteLog( 1670): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/GLSActivity( 1670): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1670): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1670): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1670): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7258): Authentication error
E/BooksAccountManager( 7258): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7258): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7258): null auth token
,I/qtaguid ( 7258): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7258, getuid(): 10082
,I/qtaguid ( 7258): Untagging socket 34
,W/ApiaryClient( 7258): Error response from books API: {
W/ApiaryClient( 7258):  "error": {
W/ApiaryClient( 7258):   "errors": [
W/ApiaryClient( 7258):    {
W/ApiaryClient( 7258):     "domain": "global",
W/ApiaryClient( 7258):     "reason": "required",
W/ApiaryClient( 7258):     "message": "Login Required",
W/ApiaryClient( 7258):     "locationType": "header",
W/ApiaryClient( 7258):     "location": "Authorization"
W/ApiaryClient( 7258):    }
W/ApiaryClient( 7258):   ],
W/ApiaryClient( 7258):   "code": 401,
W/ApiaryClient( 7258):   "message": "Login Required"
W/ApiaryClient( 7258):  }
W/ApiaryClient( 7258): }
,W/ApiaryClient( 7258): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7258): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4734580487883002511&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7258): Headers suppressed
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/BooksSync( 7258): Soft error
E/BooksSync( 7258): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7258): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4734580487883002511&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7258): Headers suppressed
E/BooksSync( 7258): 
E/BooksSync( 7258): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7258): Sync error
E/BooksSync( 7258): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7258): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4734580487883002511&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7258): Headers suppressed
E/BooksSync( 7258): 
E/BooksSync( 7258): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7258): Finished books sync
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  875): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 157099, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  875): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  875): mCursor = null
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1670): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6559): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6559): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6559): 	at kfv.a(PG:65)
E/HttpOperation( 6559): 	at kff.u(PG:385)
E/HttpOperation( 6559): 	at kfb.a(PG:29)
E/HttpOperation( 6559): 	at kff.l(PG:132)
E/HttpOperation( 6559): 	at dsf.a(PG:807)
E/HttpOperation( 6559): 	at fhk.a(PG:1126)
E/HttpOperation( 6559): 	at fhk.a(PG:908)
E/HttpOperation( 6559): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6559): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6559): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6559): 	at ihi.a(PG:22)
E/HttpOperation( 6559): 	at kft.a(PG:91)
E/HttpOperation( 6559): 	at kfv.a(PG:62)
E/HttpOperation( 6559): 	... 8 more
E/HttpOperation( 6559): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6559): 	at gde.c(Unknown Source)
E/HttpOperation( 6559): 	at gde.b(Unknown Source)
E/HttpOperation( 6559): 	at ihi.a(PG:19)
E/HttpOperation( 6559): 	... 10 more
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
D/SecContentProvider2(  875): mCursor = null
,D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6559): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6559): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6559): 	at kfv.a(PG:65)
E/HttpOperation( 6559): 	at kff.u(PG:385)
E/HttpOperation( 6559): 	at kfb.a(PG:29)
E/HttpOperation( 6559): 	at kff.l(PG:132)
E/HttpOperation( 6559): 	at ieo.a(PG:43)
E/HttpOperation( 6559): 	at iep.a(PG:93)
E/HttpOperation( 6559): 	at fhn.a(PG:59)
E/HttpOperation( 6559): 	at lex.a(PG:85)
E/HttpOperation( 6559): 	at lex.b(PG:132)
E/HttpOperation( 6559): 	at fhk.a(PG:1146)
E/HttpOperation( 6559): 	at fhk.a(PG:908)
E/HttpOperation( 6559): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6559): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6559): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6559): 	at ihi.a(PG:22)
E/HttpOperation( 6559): 	at kft.a(PG:91)
E/HttpOperation( 6559): 	at kfv.a(PG:62)
E/HttpOperation( 6559): 	... 12 more
E/HttpOperation( 6559): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6559): 	at gde.c(Unknown Source)
E/HttpOperation( 6559): 	at gde.b(Unknown Source)
E/HttpOperation( 6559): 	at ihi.a(PG:19)
E/HttpOperation( 6559): 	... 14 more
,E/ExperimentLoader( 6559): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6559): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6559): 	at kfv.a(PG:65)
E/ExperimentLoader( 6559): 	at kff.u(PG:385)
E/ExperimentLoader( 6559): 	at kfb.a(PG:29)
E/ExperimentLoader( 6559): 	at kff.l(PG:132)
E/ExperimentLoader( 6559): 	at ieo.a(PG:43)
E/ExperimentLoader( 6559): 	at iep.a(PG:93)
E/ExperimentLoader( 6559): 	at fhn.a(PG:59)
E/ExperimentLoader( 6559): 	at lex.a(PG:85)
E/ExperimentLoader( 6559): 	at lex.b(PG:132)
E/ExperimentLoader( 6559): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6559): 	at fhk.a(PG:908)
E/ExperimentLoader( 6559): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6559): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6559): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6559): 	at ihi.a(PG:22)
E/ExperimentLoader( 6559): 	at kft.a(PG:91)
E/ExperimentLoader( 6559): 	at kfv.a(PG:62)
E/ExperimentLoader( 6559): 	... 12 more
E/ExperimentLoader( 6559): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6559): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6559): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6559): 	at ihi.a(PG:19)
E/ExperimentLoader( 6559): 	... 14 more
D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/SMD     (  286): DCD ON
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6559): [getaccountstatus] Unexpected exception
E/HttpOperation( 6559): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6559): 	at kfv.a(PG:65)
E/HttpOperation( 6559): 	at kff.u(PG:385)
E/HttpOperation( 6559): 	at kfb.a(PG:29)
E/HttpOperation( 6559): 	at ixd.a(PG:248)
E/HttpOperation( 6559): 	at ixd.b(PG:206)
E/HttpOperation( 6559): 	at ixd.a(PG:175)
E/HttpOperation( 6559): 	at fig.a(PG:78)
E/HttpOperation( 6559): 	at lex.a(PG:85)
E/HttpOperation( 6559): 	at lex.b(PG:132)
E/HttpOperation( 6559): 	at fhk.a(PG:1146)
E/HttpOperation( 6559): 	at fhk.a(PG:908)
E/HttpOperation( 6559): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6559): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6559): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6559): 	at ihi.a(PG:22)
E/HttpOperation( 6559): 	at kft.a(PG:91)
E/HttpOperation( 6559): 	at kfv.a(PG:62)
E/HttpOperation( 6559): 	... 12 more
E/HttpOperation( 6559): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6559): 	at gde.c(Unknown Source)
E/HttpOperation( 6559): 	at gde.b(Unknown Source)
E/HttpOperation( 6559): 	at ihi.a(PG:19)
E/HttpOperation( 6559): 	... 14 more
,E/SQLiteLog( 1670): (10) POSIX Error : 11 SQLite Error : 3850
,E/EsSyncAdapterService( 6559): Sync failure
E/EsSyncAdapterService( 6559): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6559): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6559): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6559): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6559): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6559): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6559): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6559): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6559): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6559): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6559): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6559): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6559): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6559): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6559): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6559): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6559): 	... 10 more
E/EsSyncAdapterService( 6559): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6559): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6559): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6559): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6559): 	... 12 more
E/EsSyncAdapterService( 6559): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6559): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6559): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6559): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6559): 	... 14 more
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SyncManager(  875): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 181377, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  875): Explicit concurrent mark sweep GC freed 43050(2MB) AllocSpace objects, 18(743KB) LOS objects, 30% free, 36MB/52MB, paused 1.749ms total 156.990ms
D/SecContentProvider2(  875): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  875): mCursor = null
,E/SQLiteLog( 1670): (10) POSIX Error : 11 SQLite Error : 3850
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:m  (  875): SIOP:: AP = 310, PST = 332, CUR = 300
,E/SMD     (  286): DCD ON
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  875): [PWL] Off : 105s ago
,E/SMD     (  286): DCD ON
,E/Watchdog(  875): !@Sync 6
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 300, PST = 327, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 300, PST = 317, CUR = 300
,V/AlarmManager(  875): waitForAlarm result :4
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  286): DCD ON
,V/AlarmManager(  875): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 300, PST = 311, CUR = 300
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,E/Watchdog(  875): !@Sync 7
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,I/PowerManagerService(  875): [PWL] Off : 140s ago
,D/SSRM:m  (  875): SIOP:: AP = 300, PST = 308, CUR = 300
,E/SMD     (  286): DCD ON
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 300, PST = 306, CUR = 300
,V/AlarmManager(  875): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  875): stay LED for fully charged
,D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
,I/MotionRecognitionService(  875): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7258): Starting books sync, d
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1670): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1670): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1670): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1670): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7258): Authentication error
E/BooksAccountManager( 7258): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7258): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7258): null auth token
,I/qtaguid ( 7258): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7258, getuid(): 10082
,I/qtaguid ( 7258): Untagging socket 34
,W/ApiaryClient( 7258): Error response from books API: {
W/ApiaryClient( 7258):  "error": {
W/ApiaryClient( 7258):   "errors": [
W/ApiaryClient( 7258):    {
W/ApiaryClient( 7258):     "domain": "global",
W/ApiaryClient( 7258):     "reason": "required",
W/ApiaryClient( 7258):     "message": "Login Required",
W/ApiaryClient( 7258):     "locationType": "header",
W/ApiaryClient( 7258):     "location": "Authorization"
W/ApiaryClient( 7258):    }
W/ApiaryClient( 7258):   ],
W/ApiaryClient( 7258):   "code": 401,
W/ApiaryClient( 7258):   "message": "Login Required"
W/ApiaryClient( 7258):  }
W/ApiaryClient( 7258): }
,W/ApiaryClient( 7258): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7258): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8958557425810957178&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7258): Headers suppressed
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1670): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1670): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1670): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1670): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7258): Authentication error
E/BooksAccountManager( 7258): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7258): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7258): null auth token
,I/qtaguid ( 7258): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7258, getuid(): 10082
,I/qtaguid ( 7258): Untagging socket 34
,W/ApiaryClient( 7258): Error response from books API: {
W/ApiaryClient( 7258):  "error": {
W/ApiaryClient( 7258):   "errors": [
W/ApiaryClient( 7258):    {
W/ApiaryClient( 7258):     "domain": "global",
W/ApiaryClient( 7258):     "reason": "required",
W/ApiaryClient( 7258):     "message": "Login Required",
W/ApiaryClient( 7258):     "locationType": "header",
W/ApiaryClient( 7258):     "location": "Authorization"
W/ApiaryClient( 7258):    }
W/ApiaryClient( 7258):   ],
W/ApiaryClient( 7258):   "code": 401,
W/ApiaryClient( 7258):   "message": "Login Required"
W/ApiaryClient( 7258):  }
W/ApiaryClient( 7258): }
,W/ApiaryClient( 7258): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7258): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8958557425810957178&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7258): Headers suppressed
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1670): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1670): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1670): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1670): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7258): Authentication error
E/BooksAccountManager( 7258): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7258): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7258): null auth token
,I/qtaguid ( 7258): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7258, getuid(): 10082
,I/qtaguid ( 7258): Untagging socket 34
,W/ApiaryClient( 7258): Error response from books API: {
W/ApiaryClient( 7258):  "error": {
W/ApiaryClient( 7258):   "errors": [
W/ApiaryClient( 7258):    {
W/ApiaryClient( 7258):     "domain": "global",
W/ApiaryClient( 7258):     "reason": "required",
W/ApiaryClient( 7258):     "message": "Login Required",
W/ApiaryClient( 7258):     "locationType": "header",
W/ApiaryClient( 7258):     "location": "Authorization"
W/ApiaryClient( 7258):    }
W/ApiaryClient( 7258):   ],
W/ApiaryClient( 7258):   "code": 401,
W/ApiaryClient( 7258):   "message": "Login Required"
W/ApiaryClient( 7258):  }
W/ApiaryClient( 7258): }
,W/ApiaryClient( 7258): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7258): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8958557425810957178&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7258): Headers suppressed
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7258): Soft error
E/BooksSync( 7258): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7258): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8958557425810957178&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7258): Headers suppressed
E/BooksSync( 7258): 
E/BooksSync( 7258): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7258): Sync error
E/BooksSync( 7258): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7258): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8958557425810957178&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7258): Headers suppressed
E/BooksSync( 7258): 
E/BooksSync( 7258): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7258): Finished books sync
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  875): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 214529, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  875): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  875): mCursor = null
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  875): SIOP:: AP = 300, PST = 304, CUR = 300
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
,I/MotionRecognitionService(  875): setPowerConnected  = true
,D/BatteryService(  875): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  286): DCD ON
,E/Watchdog(  875): !@Sync 8
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 300, PST = 303, CUR = 300
,E/SMD     (  286): DCD ON
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
,I/MotionRecognitionService(  875): setPowerConnected  = true
,D/BatteryService(  875): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/PowerManagerService(  875): [PWL] Off : 180s ago
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  875): SIOP:: AP = 290, PST = 301, CUR = 300
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/AlarmManager(  875): waitForAlarm result :4
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  875): stay LED for fully charged
D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
I/MotionRecognitionService(  875): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 6559): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6559): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6559): 	at kfv.a(PG:65)
E/HttpOperation( 6559): 	at kff.u(PG:385)
E/HttpOperation( 6559): 	at kfb.a(PG:29)
E/HttpOperation( 6559): 	at kff.l(PG:132)
E/HttpOperation( 6559): 	at dsf.a(PG:807)
E/HttpOperation( 6559): 	at fhk.a(PG:1126)
E/HttpOperation( 6559): 	at fhk.a(PG:908)
E/HttpOperation( 6559): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6559): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6559): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6559): 	at ihi.a(PG:22)
E/HttpOperation( 6559): 	at kft.a(PG:91)
E/HttpOperation( 6559): 	at kfv.a(PG:62)
E/HttpOperation( 6559): 	... 8 more
E/HttpOperation( 6559): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6559): 	at gde.c(Unknown Source)
E/HttpOperation( 6559): 	at gde.b(Unknown Source)
E/HttpOperation( 6559): 	at ihi.a(PG:19)
E/HttpOperation( 6559): 	... 10 more
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
D/SecContentProvider2(  875): mCursor = null
,D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 6559): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6559): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6559): 	at kfv.a(PG:65)
E/HttpOperation( 6559): 	at kff.u(PG:385)
E/HttpOperation( 6559): 	at kfb.a(PG:29)
E/HttpOperation( 6559): 	at kff.l(PG:132)
E/HttpOperation( 6559): 	at ieo.a(PG:43)
E/HttpOperation( 6559): 	at iep.a(PG:93)
E/HttpOperation( 6559): 	at fhn.a(PG:59)
E/HttpOperation( 6559): 	at lex.a(PG:85)
E/HttpOperation( 6559): 	at lex.b(PG:132)
E/HttpOperation( 6559): 	at fhk.a(PG:1146)
E/HttpOperation( 6559): 	at fhk.a(PG:908)
E/HttpOperation( 6559): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6559): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6559): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6559): 	at ihi.a(PG:22)
E/HttpOperation( 6559): 	at kft.a(PG:91)
E/HttpOperation( 6559): 	at kfv.a(PG:62)
E/HttpOperation( 6559): 	... 12 more
E/HttpOperation( 6559): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6559): 	at gde.c(Unknown Source)
E/HttpOperation( 6559): 	at gde.b(Unknown Source)
E/HttpOperation( 6559): 	at ihi.a(PG:19)
E/HttpOperation( 6559): 	... 14 more
,E/ExperimentLoader( 6559): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6559): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6559): 	at kfv.a(PG:65)
E/ExperimentLoader( 6559): 	at kff.u(PG:385)
E/ExperimentLoader( 6559): 	at kfb.a(PG:29)
E/ExperimentLoader( 6559): 	at kff.l(PG:132)
E/ExperimentLoader( 6559): 	at ieo.a(PG:43)
E/ExperimentLoader( 6559): 	at iep.a(PG:93)
E/ExperimentLoader( 6559): 	at fhn.a(PG:59)
E/ExperimentLoader( 6559): 	at lex.a(PG:85)
E/ExperimentLoader( 6559): 	at lex.b(PG:132)
E/ExperimentLoader( 6559): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6559): 	at fhk.a(PG:908)
E/ExperimentLoader( 6559): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6559): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6559): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6559): 	at ihi.a(PG:22)
E/ExperimentLoader( 6559): 	at kft.a(PG:91)
E/ExperimentLoader( 6559): 	at kfv.a(PG:62)
E/ExperimentLoader( 6559): 	... 12 more
E/ExperimentLoader( 6559): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6559): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6559): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6559): 	at ihi.a(PG:19)
E/ExperimentLoader( 6559): 	... 14 more
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 1670): (10) POSIX Error : 11 SQLite Error : 3850
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
D/SecContentProvider2(  875): mCursor = null
,D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6559): [getaccountstatus] Unexpected exception
E/HttpOperation( 6559): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6559): 	at kfv.a(PG:65)
E/HttpOperation( 6559): 	at kff.u(PG:385)
E/HttpOperation( 6559): 	at kfb.a(PG:29)
E/HttpOperation( 6559): 	at ixd.a(PG:248)
E/HttpOperation( 6559): 	at ixd.b(PG:206)
E/HttpOperation( 6559): 	at ixd.a(PG:175)
E/HttpOperation( 6559): 	at fig.a(PG:78)
E/HttpOperation( 6559): 	at lex.a(PG:85)
E/HttpOperation( 6559): 	at lex.b(PG:132)
E/HttpOperation( 6559): 	at fhk.a(PG:1146)
E/HttpOperation( 6559): 	at fhk.a(PG:908)
E/HttpOperation( 6559): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6559): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6559): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6559): 	at ihi.a(PG:22)
E/HttpOperation( 6559): 	at kft.a(PG:91)
E/HttpOperation( 6559): 	at kfv.a(PG:62)
E/HttpOperation( 6559): 	... 12 more
E/HttpOperation( 6559): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6559): 	at gde.c(Unknown Source)
E/HttpOperation( 6559): 	at gde.b(Unknown Source)
E/HttpOperation( 6559): 	at ihi.a(PG:19)
E/HttpOperation( 6559): 	... 14 more
,E/EsSyncAdapterService( 6559): Sync failure
E/EsSyncAdapterService( 6559): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6559): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6559): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6559): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6559): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6559): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6559): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6559): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6559): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6559): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6559): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6559): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6559): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6559): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6559): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6559): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6559): 	... 10 more
E/EsSyncAdapterService( 6559): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6559): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6559): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6559): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6559): 	... 12 more
E/EsSyncAdapterService( 6559): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6559): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6559): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6559): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6559): 	... 14 more
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  875): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 247678, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/ResourcesManager( 2855): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  875): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  875): mCursor = null
,E/SQLiteLog( 1670): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  286): DCD ON
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  286): DCD ON
,V/AlarmManager(  875): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 290, PST = 299, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  875): !@Sync 9
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 290, PST = 297, CUR = 300
,E/SMD     (  286): DCD ON
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 290, PST = 296, CUR = 300
,V/AlarmManager(  875): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 290, PST = 295, CUR = 300
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
,I/MotionRecognitionService(  875): setPowerConnected  = true
,D/BatteryService(  875): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/TimaService(  875): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  875): TimaServiceHandler.handleMessage what =1
,D/TimaService(  875): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  875): initializing...
,I/TLC_TIMA_PKM_initialize(  875): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  875): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  875): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  875): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  875): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  875): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  875): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  875): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  875): App is not loaded in QSEE
,D/QSEECOMAPI: (  875): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  875): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  875): Trustlet response is completed
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  875): [PWL] Off : 225s ago
,I/PowerManagerService(  875): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  875): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  875): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=875, ws=null) (elapsedTime=2352)
,E/SMD     (  286): DCD ON
,E/Watchdog(  875): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  875): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  875): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  875): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  875): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 300, PST = 295, CUR = 300
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
,I/MotionRecognitionService(  875): setPowerConnected  = true
,D/BatteryService(  875): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 290, PST = 294, CUR = 300
,V/AlarmManager(  875): waitForAlarm result :4
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7258): Starting books sync, d
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1670): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1670): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1670): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1670): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7258): Authentication error
E/BooksAccountManager( 7258): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7258): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7258): null auth token
,I/qtaguid ( 7258): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7258, getuid(): 10082
,I/qtaguid ( 7258): Untagging socket 34
,W/ApiaryClient( 7258): Error response from books API: {
W/ApiaryClient( 7258):  "error": {
W/ApiaryClient( 7258):   "errors": [
W/ApiaryClient( 7258):    {
W/ApiaryClient( 7258):     "domain": "global",
W/ApiaryClient( 7258):     "reason": "required",
W/ApiaryClient( 7258):     "message": "Login Required",
W/ApiaryClient( 7258):     "locationType": "header",
W/ApiaryClient( 7258):     "location": "Authorization"
W/ApiaryClient( 7258):    }
W/ApiaryClient( 7258):   ],
W/ApiaryClient( 7258):   "code": 401,
W/ApiaryClient( 7258):   "message": "Login Required"
W/ApiaryClient( 7258):  }
W/ApiaryClient( 7258): }
,W/ApiaryClient( 7258): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7258): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7859654399384308600&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7258): Headers suppressed
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1670): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1670): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1670): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1670): 	at android.os.Binder.execTransact(Binder.java:446)
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,E/BooksAccountManager( 7258): Authentication error
E/BooksAccountManager( 7258): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7258): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7258): null auth token
,I/qtaguid ( 7258): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7258, getuid(): 10082
,I/qtaguid ( 7258): Untagging socket 34
,W/ApiaryClient( 7258): Error response from books API: {
W/ApiaryClient( 7258):  "error": {
W/ApiaryClient( 7258):   "errors": [
W/ApiaryClient( 7258):    {
W/ApiaryClient( 7258):     "domain": "global",
W/ApiaryClient( 7258):     "reason": "required",
W/ApiaryClient( 7258):     "message": "Login Required",
W/ApiaryClient( 7258):     "locationType": "header",
W/ApiaryClient( 7258):     "location": "Authorization"
W/ApiaryClient( 7258):    }
W/ApiaryClient( 7258):   ],
W/ApiaryClient( 7258):   "code": 401,
W/ApiaryClient( 7258):   "message": "Login Required"
W/ApiaryClient( 7258):  }
W/ApiaryClient( 7258): }
,W/ApiaryClient( 7258): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7258): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7859654399384308600&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7258): Headers suppressed
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1670): Explicit concurrent mark sweep GC freed 45602(2MB) AllocSpace objects, 61(4MB) LOS objects, 40% free, 18MB/30MB, paused 812us total 50.261ms
,D/ResourcesManager( 1670): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1670): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
,D/SecContentProvider2(  875): mCursor = null
D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1670): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1670): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1670): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1670): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7258): Authentication error
E/BooksAccountManager( 7258): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7258): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7258): null auth token
,I/qtaguid ( 7258): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7258, getuid(): 10082
,I/qtaguid ( 7258): Untagging socket 34
,W/ApiaryClient( 7258): Error response from books API: {
W/ApiaryClient( 7258):  "error": {
W/ApiaryClient( 7258):   "errors": [
W/ApiaryClient( 7258):    {
W/ApiaryClient( 7258):     "domain": "global",
W/ApiaryClient( 7258):     "reason": "required",
W/ApiaryClient( 7258):     "message": "Login Required",
W/ApiaryClient( 7258):     "locationType": "header",
W/ApiaryClient( 7258):     "location": "Authorization"
W/ApiaryClient( 7258):    }
W/ApiaryClient( 7258):   ],
W/ApiaryClient( 7258):   "code": 401,
W/ApiaryClient( 7258):   "message": "Login Required"
W/ApiaryClient( 7258):  }
W/ApiaryClient( 7258): }
,W/ApiaryClient( 7258): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7258): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7859654399384308600&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7258): Headers suppressed
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  875): waitForAlarm result :4
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0,
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  875): stay LED for fully charged
,D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,I/ActivityManager(  875): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8440 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
I/MotionRecognitionService(  875): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,E/Zygote  ( 8440): MountEmulatedStorage()
E/Zygote  ( 8440): v2
I/libpersona( 8440): KNOX_SDCARD checking this for 10081
I/libpersona( 8440): KNOX_SDCARD not a persona
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,I/SELinux ( 8440): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8440): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8440): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaKeyStoreProvider( 8440): TimaSignature is unavailable
,D/ActivityThread( 8440): Added TimaKeyStore provider
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,E/BooksSync( 7258): Soft error
E/BooksSync( 7258): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7258): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7859654399384308600&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7258): Headers suppressed
E/BooksSync( 7258): 
E/BooksSync( 7258): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7258): Sync error
E/BooksSync( 7258): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7258): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7859654399384308600&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7258): Headers suppressed
E/BooksSync( 7258): 
E/BooksSync( 7258): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7258): Finished books sync
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  875): Killing 7049:com.samsung.helphub/1000 (adj 15): bgCount ##41
,D/SyncManager(  875): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 304957, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ResourcesManager( 2855): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,E/SMD     (  286): DCD ON
,D/ResourcesManager( 2855): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  875): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  875): failed to open /acct/uid_1000/pid_7049/cgroup.procs: No such file or directory
,I/art     (  875): Explicit concurrent mark sweep GC freed 49783(3MB) AllocSpace objects, 58(1513KB) LOS objects, 30% free, 36MB/52MB, paused 1.906ms total 172.944ms
D/SecContentProvider2(  875): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  875): mCursor = null
,V/AlarmManager(  875): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  875): SIOP:: AP = 290, PST = 293, CUR = 300
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  286): DCD ON
,E/Watchdog(  875): !@Sync 11
,D/BatteryService(  875): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  875): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  875): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  875):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  875): Plugged
,I/MotionRecognitionService(  875): setPowerConnected  = true
,D/BatteryService(  875): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  875): SIOP:: AP = 290, PST = 292, CUR = 300
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/jxcore-log( 7423): --= Surplus to requirements =--
I/jxcore-log( 7423): 
,I/jxcore-log( 7423): ****TEST TOOK:  ms ****
I/jxcore-log( 7423): 
,I/jxcore-log( 7423): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7423): 
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/AndroidRuntime( 8505): 
D/AndroidRuntime( 8505): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8505): CheckJNI is OFF
,D/AndroidRuntime( 8505): setted country_code = Germany
,D/AndroidRuntime( 8505): setted countryiso_code = DE
,D/AndroidRuntime( 8505): setted sales_code = DBT
D/AndroidRuntime( 8505): readGMSProperty: start
,D/AndroidRuntime( 8505): readGMSProperty: already setted!!
D/AndroidRuntime( 8505): readGMSProperty: end
D/AndroidRuntime( 8505): addProductProperty: start
,E/AffinityControl( 8505): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8505): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  875): START PACKAGE DELETE: observer{619048708}
D/PackageManager(  875): pkg{<packageName>}
D/PackageManager(  875): user{0}
D/PackageManager(  875): caller{2000}
D/PackageManager(  875): flags{3}
,D/PersonaManagerService(  875): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  875): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  875): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  875): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  875): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  875): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  875): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  875): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  875): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  875): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  875): !@killApplicatoin: 10200, uninstall pkg
,I/ActivityManager(  875): Force stopping com.test.thalitest appid=10200 user=-1: uninstall pkg
,I/ActivityManager(  875): Killing 7423:com.test.thalitest/u0a200 (adj 0): stop com.test.thalitest
,I/ActivityManager(  875):   Force finishing activity ActivityRecord{a8f7812 u0 com.test.thalitest/.MainActivity t18}
,W/ActivityManager(  875): mDVFSHelper.acquire()
,I/WindowState(  875): WIN DEATH: Window{a5eec28 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  875): Client connection lost with reason: 4
,I/SurfaceFlinger(  248): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
,I/SurfaceFlinger(  248): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/SurfaceFlinger(  248): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/ActivityManager(  875): Force stopping com.test.thalitest appid=10200 user=0: pkg removed
,I/ActivityManager(  875):   Force finishing activity ActivityRecord{a8f7812 u0 com.test.thalitest/.MainActivity t18 f}
W/ActivityManager(  875): Duplicate finish request for ActivityRecord{a8f7812 u0 com.test.thalitest/.MainActivity t18 f}
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,I/art     ( 4500): Explicit concurrent mark sweep GC freed 5023(278KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 498us total 28.618ms
,I/art     ( 1551): Explicit concurrent mark sweep GC freed 54193(3MB) AllocSpace objects, 0(0B) LOS objects, 25% free, 16MB/21MB, paused 401us total 46.195ms
,I/DBG_DM  ( 3824): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
,D/FocusedStackFrame(  875): Set to : 0
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3824): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 62
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/DBG_DM  ( 3824): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/DBG_DM  ( 3824): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/InputReader(  875): Reconfiguring input devices.  changes=0x00000010
,I/DBG_DM  ( 3824): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 62
,E/SamsungIME( 1857): mOCRHelper is null
,I/DBG_DM  ( 3824): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,W/GeofencerStateMachine( 2231): Ignoring removeGeofence because network location is disabled.
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3824): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3824): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/KLMS-2.4.503: ( 7625): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7625): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1453102754672
,D/SecContentProvider2(  875): uri = 14 selection = getSealedState
D/SecContentProvider2(  875): mCursor = null
,D/SecContentProvider2(  875): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  875): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/art     (  875): Explicit concurrent mark sweep GC freed 15230(1384KB) AllocSpace objects, 10(160KB) LOS objects, 30% free, 36MB/52MB, paused 3.434ms total 189.781ms
,I/DBG_DM  ( 3824): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 62
D/ResourcesManager(  875): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     (  875): WaitForGcToComplete blocked for 126.796ms for cause Explicit
,I/KLMS-2.4.503: ( 7625): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.503: ( 7625): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,I/DBG_DM  ( 3824): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 3824): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/DBG_DM  ( 3824): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3824): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 3824): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager(  875): post active user change for 0
D/KnoxTimeoutHandler(  875): postActiveUserChange for user 0
,I/DBG_DM  ( 3824): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/SurfaceFlinger(  248): id=17 createSurf (1080x1920),2 flag=404, com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/StatusBarManagerService(  875): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/SurfaceWidgetView( 1484): destroyHardwareResources():349679288
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,V/WindowOrientationListener(  875): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  875): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  875): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  875): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  875): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/SecContentProvider2(  875): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  875): mCursor = null
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/Launcher( 1484): onRestart, Launcher: 63177930
,D/Launcher( 1484): onStart, Launcher: 63177930
D/Launcher.HomeView( 1484): onStart
D/ResourcesManager(  875): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/RegisteredServicesCache( 1471): empty dynamic service
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2011): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/Launcher.HomeView( 1484): onStop
,D/SurfaceWidget.Renderer( 2011): [237392/6] SurfaceWidget drawing first frame
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/SurfaceFlinger(  248): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/StatusBarManagerService(  875): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/StatusBarManagerService(  875): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
E/Zygote  ( 8537): MountEmulatedStorage()
E/Zygote  ( 8537): v2
I/libpersona( 8537): KNOX_SDCARD checking this for 10104
I/libpersona( 8537): KNOX_SDCARD not a persona
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,I/ActivityManager(  875): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8537 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/InputMethodManagerService(  875): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,I/SELinux ( 8537): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8537): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8537): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/SurfaceFlinger(  248): id=17 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (6/9)
,I/SurfaceFlinger(  248): id=17 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/9)
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,W/InputMethodManagerService(  875): Got RemoteException sending setActive(false) notification to pid 7423 uid 10200
D/ResourcesManager(  875): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/ContextImpl(  875): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/Timeline( 3824): Timeline: Activity_idle id: android.os.BinderProxy@366b1877 time:352055
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/TimaKeyStoreProvider( 8537): TimaSignature is unavailable
,D/ActivityThread( 8537): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/EnterpriseDeviceManagerService(  875): Package has changed for user 0
D/EnterpriseDeviceManagerService(  875): Admin package name: com.google.android.gms
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ResourcesManager( 8537): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/RCPManagerService(  875): PackageReceiver onReceive()
I/HarmonyEASService(  875): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/KnoxMUMContainerPolicy(  875): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/ActivityManager(  875): mDVFSHelper.release()
I/Timeline(  875): Timeline: Activity_windows_visible id: ActivityRecord{33634381 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t15} time:352113
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/BackupManagerService(  875): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  875): Receieved: android.intent.action.PACKAGE_REMOVED
W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,V/EnterpriseBillingPolicy(  875): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  875): uID is 10200
V/EnterpriseBillingPolicy(  875): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  875): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  875): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  875): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  875): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  875): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage(  875): getBillingProfileForVpnEngine - end - null
,I/art     (  875): Explicit concurrent mark sweep GC freed 10338(602KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 2.198ms total 258.515ms
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/KnoxTimeoutHandler(  875): handleActiveUserChange for user 0
D/TaskPersister(  875): removeObsoleteFile: deleting file=18_task.xml
,D/TaskPersister(  875): removeObsoleteFile: deleting file=17_task.xml
,D/elm:14451( 8537): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 8537): ELMEngine.ELMEngine( context ).
,D/elm:14451( 8537): MDMBridge.setEnterpriseBridge()
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/Books/Books.apk
,D/elm:14451( 8537): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 8010): onReceive()
,I/com.sec.android.service.health.upgrade.UninstallReceiver( 8010): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8010): onReceive() : package name is not s health. Return !!!
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/elm:14451( 8537): ElmAgentService : onCreate()
D/elm:14451( 8537): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,D/elm:14451( 8537): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8537): MDMBridge.getInstance()
D/elm:14451( 8537): MDMBridge.getAllLicenseInfoFromSDK()
,I/PCWCLIENTTRACE_PushUtil( 6777): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6777): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6777): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6777): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/elm:14451( 8537): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14451( 8537): ElmAgentService : onDestroy().
,D/PackageManager(  875): delete codoeFile: 
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/PackageManager(  875): result of delete: 1{619048708}
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 8505): Shutting down VM
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 8557): MountEmulatedStorage()
I/libpersona( 8557): KNOX_SDCARD checking this for 10038
E/Zygote  ( 8557): v2
I/libpersona( 8557): KNOX_SDCARD not a persona
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/ActivityManager(  875): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8557 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  875): Killing 7083:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  875): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  875): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/art     (  313): Explicit concurrent mark sweep GC freed 8715(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 271us total 12.052ms
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 8.017ms
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 254us total 7.534ms
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  875): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  875): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/SELinux ( 8557): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/ResourcesManager(  875): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/SELinux ( 8557): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  875): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,E/SELinux ( 8557): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  875): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ConnectivityService(  875): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 8557): TimaSignature is unavailable
D/ActivityThread( 8557): Added TimaKeyStore provider
D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/libprocessgroup(  875): failed to open /acct/uid_10166/pid_7083/cgroup.procs: No such file or directory
,D/ResourcesManager( 8557): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  875): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  875): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  875): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  875): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  875): onPackageRemoved : com.test.thalitest
D/ResourcesManager( 7969): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 7969): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 7969): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,E/SPPClientService( 8557): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 8557): [PushClientApplication] Push log off : This is Ship build version
,W/ResourcesManager( 7969): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/SPPClientService( 8557): PushLog.txt file is not deleted.
,D/SPPClientService( 8557): PushLog.txt file is not deleted.
D/SPPClientService( 8557): ============PushLog. stop!
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 7969): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 7969): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 7969): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 7969): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/Zygote  ( 8573): MountEmulatedStorage()
E/Zygote  ( 8573): v2
I/libpersona( 8573): KNOX_SDCARD checking this for 10042
I/libpersona( 8573): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8573 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager(  875): Killing 6638:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,I/SELinux ( 8573): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8573): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
E/SELinux ( 8573): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 7969): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 7969): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/TimaKeyStoreProvider( 8573): TimaSignature is unavailable
,D/ActivityThread( 8573): Added TimaKeyStore provider
W/ResourcesManager( 7969): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  875): failed to open /acct/uid_10012/pid_6638/cgroup.procs: No such file or directory
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 7969): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7969): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 8573): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,W/ResourcesManager( 8573): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8573): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7969): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/ResourcesManager( 7969): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/FileUtils( 8573): Failed to chmod(/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/SQLiteLog( 8573): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 8573): (3850) statement aborts at 68: [UPDATE DEVICES SET network_mode='OFF', device_priority=((16777215 & device_priority) | 67108864) WHERE transport_type='SLINK';] disk I/O error
,D/AndroidRuntime( 8573): Shutting down VM
,E/AndroidRuntime( 8573): FATAL EXCEPTION: main
E/AndroidRuntime( 8573): Process: com.samsung.android.sdk.samsunglink, PID: 8573
E/AndroidRuntime( 8573): java.lang.RuntimeException: Unable to get provider com.mfluent.asp.datamodel.ASPMediaStoreProvider: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 8573): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5456)
E/AndroidRuntime( 8573): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
E/AndroidRuntime( 8573): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
E/AndroidRuntime( 8573): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8573): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/AndroidRuntime( 8573): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8573): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 8573): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/AndroidRuntime( 8573): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8573): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8573): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 8573): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 8573): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 8573): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 8573): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 8573): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 8573): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 8573): 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1797)
E/AndroidRuntime( 8573): 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1726)
E/AndroidRuntime( 8573): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:464)
E/AndroidRuntime( 8573): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/AndroidRuntime( 8573): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/AndroidRuntime( 8573): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
E/AndroidRuntime( 8573): 	... 11 more
,V/ApplicationPolicy(  875): isApplicationStateBlocked userId 0 pkgname com.samsung.android.sdk.samsunglink
I/Process ( 8573): Sending signal. PID: 8573 SIG: 9
I/SA      ( 6816): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
I/SA      ( 6816): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10200 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
E/lowmemorykiller(  245): Error writing /proc/8573/oom_score_adj; errno=22
E/DropBoxManagerService(  875): Can't write: system_app_crash
E/DropBoxManagerService(  875): java.io.FileNotFoundException: /data/system/dropbox/drop185.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  875): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  875): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  875): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  875): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  875): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  875): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:14540)
E/DropBoxManagerService(  875): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  875): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  875): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  875): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  875): 	... 5 more
I/ActivityManager(  875): Killing 7100:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): bgCount ##41
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/SharedPreferencesImpl( 6024): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,E/Zygote  ( 8594): MountEmulatedStorage()
E/Zygote  ( 8594): v2
I/libpersona( 8594): KNOX_SDCARD checking this for 10050
I/libpersona( 8594): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageReceiver: pid=8594 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/ActivityManager(  875): Process com.samsung.android.sdk.samsunglink (pid 8573)(adj 11) has died(105,572)
,W/libprocessgroup(  875): failed to open /acct/uid_10170/pid_7100/cgroup.procs: No such file or directory
,I/SELinux ( 8594): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8594): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8594): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8594): TimaSignature is unavailable
,D/ActivityThread( 8594): Added TimaKeyStore provider
,D/ResourcesManager( 8594): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8594): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8594): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8594): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8594): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8594): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ContextImpl( 8594): Unable to create files subdir /data/data/com.android.mms/cache
E/ActivityThread( 8594): Unable to setupGraphicsSupport due to missing cache directory
,I/EventHub(  875): Removing device '/dev/input/event4' due to inotify event
,F/libc    ( 8594): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7429da62 in tid 8594 (com.android.mms)
,E/audit_log( 2139): File locking failed. error= Bad file number
,F/libc    ( 8594): Failed while talking to debuggerd: Broken pipe
E/audit_log( 2139): File locking failed. error= Bad file number
,I/ActivityManager(  875): Process com.android.mms (pid 8594)(adj 0) has died(105,572)
,I/EventHub(  875): Removing device '/dev/input/event5' due to inotify event
,I/TactileAssist(  875): enable value -1
I/TactileAssist(  875): internal enable value -1
I/TactileAssist(  875): intensity value -1
I/TactileAssist(  875): saveAppList value true
,I/TactileAssist(  875): List of disabled apps :
I/TactileAssist(  875): de.zalando.mobile
E/SharedPreferencesImpl(  875): Couldn't create directory for SharedPreferences file /data/data/com.android.settings/shared_prefs/com.android.settings_tactileassist.xml
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8609): MountEmulatedStorage()
E/Zygote  ( 8609): v2
I/libpersona( 8609): KNOX_SDCARD checking this for 10058
I/libpersona( 8609): KNOX_SDCARD not a persona
,I/Zygote  (  313): Process 8594 exited due to signal (7)
,I/ActivityManager(  875): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=8609 uid=10058 gids={50058, 9997, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 8609): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8609): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8609): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8609): TimaSignature is unavailable
,D/ActivityThread( 8609): Added TimaKeyStore provider
,D/ResourcesManager( 8609): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,W/ResourcesManager( 8609): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ContextImpl( 8609): Unable to create files subdir /data/data/com.sec.android.app.soundalive/cache
,E/ActivityThread( 8609): Unable to setupGraphicsSupport due to missing cache directory
,I/EventHub(  875): Removing device '/dev/input/event6' due to inotify event
,E/SMD     (  286): DCD ON
,D/AndroidRuntime( 8609): Shutting down VM
,F/libc    ( 8609): Fatal signal 7 (SIGBUS), code 2, fault addr 0x74585fa4 in tid 8609 (.app.soundalive)
,F/libc    ( 8609): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2139): File locking failed. error= Bad file number
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,I/UpdateIcingCorporaServi( 1551): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,E/Zygote  ( 8625): MountEmulatedStorage()
E/Zygote  ( 8625): v2
I/libpersona( 8625): KNOX_SDCARD checking this for 10003
I/libpersona( 8625): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=8625 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,I/EventHub(  875): Removing device '/dev/input/event7' due to inotify event
,I/SELinux ( 8625): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  875): Process com.sec.android.app.soundalive (pid 8609)(adj 9) has died(105,572)
,I/SELinux ( 8625): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8625): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Zygote  (  313): Process 8609 exited due to signal (7)
,D/TimaKeyStoreProvider( 8625): TimaSignature is unavailable
,D/ActivityThread( 8625): Added TimaKeyStore provider
,E/SQLiteLog( 1551): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 1551): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,F/libc    ( 1551): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7875d228 in tid 8624 (IntentService[U)
,F/libc    ( 1551): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2139): File locking failed. error= Bad file number
,I/EventHub(  875): Removing device '/dev/input/event8' due to inotify event
,D/ResourcesManager( 8625): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,W/ContextImpl( 8625): Unable to create files subdir /data/data/com.samsung.android.intelligenceservice/cache
E/ActivityThread( 8625): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 8625): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7429da62 in tid 8625 (lligenceservice)
,F/libc    ( 8625): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2139): File locking failed. error= Bad file number
,I/ActivityManager(  875): Process com.samsung.android.intelligenceservice (pid 8625)(adj 0) has died(113,572)
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  875): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8640): MountEmulatedStorage()
E/Zygote  ( 8640): v2
I/libpersona( 8640): KNOX_SDCARD checking this for 1000
I/libpersona( 8640): KNOX_SDCARD not a persona
,I/ActivityManager(  875): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=8640 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/EventHub(  875): Removing device '/dev/input/event9' due to inotify event
,I/Zygote  (  313): Process 8625 exited due to signal (7)
,I/EventHub(  875): Removing device '/dev/input/event10' due to inotify event
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,I/SELinux ( 8640): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/Zygote  (  313): Process 1551 exited due to signal (7)
,I/SELinux ( 8640): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/WifiService(  875): Client connection lost with reason: 4
E/SELinux ( 8640): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  875): Process com.google.android.googlequicksearchbox:search (pid 1551)(adj 1) has died(121,572)
,F/libc    (  875): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa0c99810 in tid 1231 (Binder_4)
F/libc    (  875): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2139): File locking failed. error= Bad file number
,I/ServiceManager(  246): service 'sec_analytics' died
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
I/ServiceManager(  246): service 'application_policy' died
I/ServiceManager(  246): service 'wifi_policy' died
I/ServiceManager(  246): service 'phone_restriction_policy' died
I/ServiceManager(  246): service 'remoteinjection' died
I/ServiceManager(  246): service 'mum_container_policy' died
I/ServiceManager(  246): service 'enterprise_billing_policy' died
I/ServiceManager(  246): service 'knox_timakeystore_policy' died
I/ServiceManager(  246): service 'wifi' died
I/ServiceManager(  246): service 'msapwifi' died
I/ServiceManager(  246): service 'wifiscanner' died
I/ServiceManager(  246): service 'rttmanager' died
I/ServiceManager(  246): service 'audio' died
I/ServiceManager(  246): service 'DockObserver' died
I/ServiceManager(  246): service 'usb' died
I/ServiceManager(  246): service 'serial' died
I/ServiceManager(  246): service 'uimode' died
I/ServiceManager(  246): service 'jobscheduler' died
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
I/ServiceManager(  246): service 'wallpaper' died
I/ServiceManager(  246): service 'wifip2p' died
I/ServiceManager(  246): service 'context_aware' died
I/ServiceManager(  246): service 'scontext' died
I/ServiceManager(  246): service 'barbeam' died
I/ServiceManager(  246): service 'multiwindow_facade' died
I/ServiceManager(  246): service 'window' died
I/ServiceManager(  246): service 'input' died
I/ServiceManager(  246): service 'input_method' died
I/ServiceManager(  246): service 'accessibility' died
I/ServiceManager(  246): service 'motion_recognition' died
I/ServiceManager(  246): service 'cover' died
I/ServiceManager(  246): service 'backup' died
I/ServiceManager(  246): service 'appwidget' died
I/ServiceManager(  246): service 'voiceinteraction' died
I/ServiceManager(  246): service 'SecExternalDisplayService' died
I/ServiceManager(  246): service 'diskstats' died
I/ServiceManager(  246): service 'spengestureservice' died
W/Sensors ( 1302): sensorservice died [0x9d3212c0]
I/ServiceManager(  246): service 'quickconnect' died
I/ServiceManager(  246): service 'samplingprofiler' died
W/Sensors ( 1171): sensorservice died [0xaee7f0c0]
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
I/ServiceManager(  246): service 'mount' died
I/ServiceManager(  246): service 'lock_settings' died
I/ServiceManager(  246):, service 'device_policy' died
I/ServiceManager(  246): service 'harmony_eas_service' died
E/WifiManager( 1302): Channel connection lost
E/WifiManager( 1171): Channel connection lost
I/ServiceManager(  246): service 'sdp' died
I/ServiceManager(  246): service 'log_manager_service' died
I/ServiceManager(  246): service 'enterprise_license_policy' died
I/ServiceManager(  246): service 'tactileassist' died
I/ServiceManager(  246): service 'bluetooth_manager' died
I/ServiceManager(  246): service 'bluetooth_secure_mode_manager' died
I/ServiceManager(  246): service 'rcp' died
I/ServiceManager(  246): service 'package' died
I/ServiceManager(  246): service 'permission' died
I/ServiceManager(  246): service 'dbinfo' died
I/ServiceManager(  246): service 'usagestats' died
I/ServiceManager(  246): service 'scheduling_policy' died
I/ServiceManager(  246): service 'batterystats' died
I/ServiceManager(  246): service 'appops' died
I/ServiceManager(  246): service 'power' died
I/ServiceManager(  246): service 'display' died
I/ServiceManager(  246): service 'persona_policy' died
I/ServiceManager(  246): service 'SEAMService' died
I/ServiceManager(  246): service 'persona' died
I/ServiceManager(  246): service 'account' died
I/ServiceManager(  246): service 'content' died
I/ServiceManager(  246): service 'DirEncryptService' died
I/ServiceManager(  246): service 'ReactiveService' died
I/ServiceManager(  246): service 'sedenial' died
I/ServiceManager(  246): service 'vibrator' died
I/ServiceManager(  246): service 'tw_toolbox' died
I/ServiceManager(  246): service 'tima' died
I/ServiceManager(  246): service 'cepproxyks' died
I/ServiceManager(  246): service 'CustomFrequencyManagerService' died
I/ServiceManager(  246): service 'samsung.smartfaceservice' died
I/ServiceManager(  246): service 'consumer_ir' died
I/ServiceManager(  246): service 'alarm' died
I/ServiceManager(  246): service 'telephony.registry' died
I/ServiceManager(  246): service 'user' died
I/ServiceManager(  246): service 'cpuinfo' died
I/ServiceManager(  246): service 'hardware' died
I/ServiceManager(  246): service 'procstats' died
I/ServiceManager(  246): service 'edmnativehelper' died
I/ServiceManager(  246): service 'webviewupdate' died
I/ServiceManager(  246): service 'entropy' died
I/ServiceManager(  246): service 'meminfo' died
I/ServiceManager(  246): service 'activity' died
I/ServiceManager(  246): service 'gfxinfo' died
I/ServiceManager(  246): service 'battery' died
I/ServiceManager(  246): service 'sensorservice' died
I/ServiceManager(  246): service 'mdm.remotedesktop' died
W/Sensors ( 1484): sensorservice died [0xaee653c0]
I/SurfaceFlinger(  248): restart the boot-animation @ binderDied
W/Sensors ( 1460): sensorservice died [0xaeebfbc0]
D/SurfaceFlinger(  248): Set power mode=2, type=0 flinger=0xb6962000
D/qdhwcomposer(  248): hwc_blank: Unblanking display: 0
E/WifiManager( 2231): Channel connection lost
I/SurfaceFlinger(  248): id=2 Removed FocusedStackFrame (4/8)
I/SurfaceFlinger(  248): id=3 Removed DimLayer (0/7)
I/SurfaceFlinger(  248): id=4 Removed DimLayer (0/6)
I/SurfaceFlinger(  248): id=5 Removed DimLayer (0/5)
I/SurfaceFlinger(  248): id=6 Removed DimLayer (2/4)
I/SurfaceFlinger(  248): id=2 Removed FocusedStackFrame (-2/4)
I/SurfaceFlinger(  248): id=3 Removed DimLayer (-2/4)
I/SurfaceFlinger(  248): id=4 Removed DimLayer (-2/4)
W/Sensors ( 6024): sensorservice died [0xaeefa600]
W/Sensors ( 1478): sensorservice died [0xaeed6380]
W/Sensors ( 2231): sensorservice died [0xaee70ec0]
I/SurfaceFlinger(  248): id=5 Removed DimLayer (-2/4)
I/SurfaceFlinger(  248): id=6 Removed DimLayer (-2/4)
W/Sensors ( 2266): sensorservice died [0xaeebfc00]
I/SurfaceFlinger(  248): id=7 Removed com.android.systemui.ImageWallpaper (0/3)
I/SurfaceFlinger(  248): id=7 Removed com.android.systemui.ImageWallpaper (-2/3)
I/SurfaceFlinger(  248): id=14 Removed ColorFade (2/2)
I/SurfaceFlinger(  248): id=14 Removed ColorFade (-2/2)
I/SurfaceFlinger(  248): id=18 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (0/1)
I/SurfaceFlinger(  248): id=9 Removed StatusBar (0/0)
I/SurfaceFlinger(  248): id=18 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/0)
I/SurfaceFlinger(  248): id=9 Removed StatusBar (-2/0)
E/WifiManager( 1478): Channel connection lost
W/AudioFlinger(  292): power manager service died !!!
W/AudioFlinger(  292): power manager service died !!!
E/WifiManager( 5616): Channel connection lost
F/libc    ( 8640): Fatal signal 7 (SIGBUS), code 2, fault addr 0x759acd71 in tid 8640 (p.assistantmenu)
F/libc    ( 8640): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2139): File locking failed. error= Bad file number
,I/Zygote  (  313): Process 8640 exited due to signal (7)
,E/installd(  295): eof
E/installd(  295): failed to read size
I/installd(  295): closing connection
,I/qdhwcomposer(  248): handle_blank_event: dpy:0 panel power state: 1
,F/libc    (  248): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb6b13268 in tid 248 (surfaceflinger)
F/libc    (  248): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2139): File locking failed. error= Bad file number
,I/ServiceManager(  246): service 'SurfaceFlinger' died
I/ServiceManager(  246): service 'display.qservice' died
W/SurfaceComposerClient( 3824): ComposerService remote (surfaceflinger) died [0xaeec71c0]
W/SurfaceComposerClient( 1484): ComposerService remote (surfaceflinger) died [0xaee65200]
W/SurfaceComposerClient( 2011): ComposerService remote (surfaceflinger) died [0xaee68ac0]
W/SurfaceComposerClient( 6703): ComposerService remote (surfaceflinger) died [0xaeecc800]
W/SurfaceComposerClient( 1171): ComposerService remote (surfaceflinger) died [0xaee7f380]
,W/SurfaceComposerClient( 5616): ComposerService remote (surfaceflinger) died [0xaed26440]
,E/DisplayEventReceiver( 1171): Display event receiver pipe was closed or an error occurred.  events=0x9
,E/DisplayEventReceiver( 1484): Display event receiver pipe was closed or an error occurred.  events=0x9
E/OpenGLRenderer( 1171): Display event receiver pipe was closed or an error occurred.  events=0x9
E/OpenGLRenderer( 1484): Display event receiver pipe was closed or an error occurred.  events=0x9
E/DisplayEventReceiver( 6703): Display event receiver pipe was closed or an error occurred.  events=0x9
E/DisplayEventReceiver( 3824): Display event receiver pipe was closed or an error occurred.  events=0x9
,E/DisplayEventReceiver( 2011): Display event receiver pipe was closed or an error occurred.  events=0x9
E/DisplayEventReceiver( 5616): Display event receiver pipe was closed or an error occurred.  events=0x9

```
