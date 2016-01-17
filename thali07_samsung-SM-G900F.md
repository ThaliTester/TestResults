#### Test 56151093c886730_thali07_samsung-SM-G900F Logs


```
--------- beginning of main,
E/SMD     (  287): DCD ON
--------- beginning of system
V/AlarmManager(  844): waitForAlarm result :4
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7402): MountEmulatedStorage()
E/Zygote  ( 7402): v2
I/libpersona( 7402): KNOX_SDCARD checking this for 10179
I/libpersona( 7402): KNOX_SDCARD not a persona
I/ActivityManager(  844): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler: pid=7402 uid=10179 gids={50179, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
I/SELinux ( 7402): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/BatteryService(  844): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  844): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
I/SELinux ( 7402): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/BatteryService(  844): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  844): stay LED for fully charged
D/MotionRecognitionService(  844):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  844): Plugged
I/MotionRecognitionService(  844): setPowerConnected  = true
E/SELinux ( 7402): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
I/art     (  319): Explicit concurrent mark sweep GC freed 8706(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 511us total 43.705ms
D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3234): Disconnected process message: 10
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 1.329ms total 59.936ms
I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 485us total 21.169ms
D/AndroidRuntime( 7399): 
D/AndroidRuntime( 7399): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7399): CheckJNI is OFF
D/AndroidRuntime( 7399): setted country_code = Germany
D/AndroidRuntime( 7399): setted countryiso_code = DE
D/AndroidRuntime( 7399): setted sales_code = DBT
D/AndroidRuntime( 7399): readGMSProperty: start
D/AndroidRuntime( 7399): readGMSProperty: already setted!!
D/AndroidRuntime( 7399): readGMSProperty: end
D/AndroidRuntime( 7399): addProductProperty: start
D/TimaKeyStoreProvider( 7402): TimaSignature is unavailable
D/ActivityThread( 7402): Added TimaKeyStore provider
I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 1679): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_google_search.png
V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  844): uri = 14 selection = getSealedState
D/SecContentProvider2(  844): mCursor = null
D/SecContentProvider2(  844): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  844): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  844): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/ResourcesManager( 7402): creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
W/Search.LoginHelper( 1544): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
W/ResourcesManager( 7402): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/UMC:Core( 7402): onCreate(): 
D/USER_AGENT( 7402): UMC/1.1.39 (SM-G900F) SAFE-5.3 KNOX-2.3
E/AffinityControl( 7399): AffinityControl: registerfunction enter
D/AndroidRuntime( 7399): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  844): inState():  stateMachine is null !!
D/SSRM:m  (  844): SIOP:: AP = 360, PST = 425, CUR = 300
V/ApplicationPolicy(  844): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  844): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  844): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  844): mDVFSHelper.acquire()
D/[SAMSUNG SMARCART NATIVE]( 7402): initialize...
D/[SAMSUNG SMARCART NATIVE]( 7402): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
I/CSTORAGE( 7402): ================================================
I/CSTORAGE( 7402):  CSTORAGE_SKM_LIB v1.0.8
I/CSTORAGE( 7402): ================================================
I/TZ_CCM_C_GetFunctionList: ( 7402): TZ_CCM_C_GetFunctionList was called
D/[SAMSUNG SMARCART NATIVE]( 7402): FINISHED: initialize rv:0
D/FocusedStackFrame(  844): Set to : 0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7452): MountEmulatedStorage()
E/Zygote  ( 7452): v2
I/libpersona( 7452): KNOX_SDCARD checking this for 10200
I/libpersona( 7452): KNOX_SDCARD not a persona
I/ActivityManager(  844): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7452 uid=10200 gids={50200, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SELinux ( 7452): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SELinux ( 7452): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7452): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 7399): Shutting down VM
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/TimaKeyStoreProvider( 7452): TimaSignature is unavailable
D/ActivityThread( 7452): Added TimaKeyStore provider
V/WindowOrientationListener(  844): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  844): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  844): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  844): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  844): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  844): Display changed displayId=0
D/SurfaceWidgetView( 1492): destroyHardwareResources():755621454
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/UMC:SecurityUtils( 7402): Loaded server certificates: 0
D/UMC:SecurityUtils( 7402): Loaded server certificates: 0
D/UMC:SecurityUtils( 7402): timaVersion on the device: 3.0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/UMC:CloudMDMSecurity( 7402): New Flow
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/TimaService(  844): TIMA3: in ccmRegisterForDefaultCertificate
D/TimaService(  844): TIMA: in getTimaVersion
I/        (  844): CCM JNI: In ccm_register_for_default_cert
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/        (  844): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: (  844): DEBUG_CONTAINER_PROBLEM Enter TZ_CCM_C_Initialize_TLC!
I/TZ_CCM_C_Initialize: (  844): pInitArgs 0x9264a814 has not called C_Init before.
I/TZ_CCM_C_Initialize: (  844): &ctx = 0xa00b3c1c
I/TLC_TZ_CCM: (  844): creating new ccm context...
I/TLC_TZ_CCM: (  844): initializing ccm context...
I/TLC_TZ_CCM: (  844): root = /firmware/image, root_strlen = 15
I/TLC_TZ_CCM: (  844): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  844): input max_sendmsg_size = 19420
I/TZ: client_server_communication(  844): input max_recvmsg_size = 19420
I/TZ: client_server_communication(  844): root = /firmware/image, root_len = 15
I/TZ: client_server_communication(  844): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  844): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication(  844): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication(  844): Client_Server_Open was called
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2143): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/TZ: client_server_communication(  844): IClientServer::IClientServer()
I/TZ: client_server_communication(  844): BpClientServer::BpClientServer()
I/TZ: client_server_communication(  844): IClientServer::~IClientServer()
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (6/8)
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
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/8)
D/QSEECOMAPI: ( 1077): App is not loaded in QSEE
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/Launcher( 1492): onTrimMemory. Level: 20
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7452): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/QSEECOMAPI: ( 1077): Loaded image: APP id = 3
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SQLiteSecureOpenHelper( 3554): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3554): getDatabaseLocked(b,b,pwd)...
I/TZ: qc_tlc_communication( 1077): TIMA: path = /firmware/image, fname = tz_ccm, tzapp is loaded
I/TZ: client_server_communication(  844): OpenSWConn(CCM) is successful
I/TZ: client_server_communication(  844): Client_Server_Open succeeded, serverName = CCM
I/TZ_CCM_C_Initialize: (  844): ctx = 0x9525f450, comm = 0x96e9c940, sendmsg = 0x976b0000, recvmsg = 0x976b4c00
I/TZ_init: (  844): TZ_init: sending initialization request...
I/TZ: client_server_communication(  844): Cmd id = 2, len = 19456
I/TZ: client_server_communication(  844): Calling Communicate()
I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1077): COMM
I/TZ_init: (  844): TZ_init: successful initialization
I/TLC_TZ_COMMON: key_db_init: (  844): Exercising TZ_DB_INIT in TLC
I/TZ: client_server_communication(  844): Cmd id = 17, len = 19456
I/TZ: client_server_communication(  844): Calling Communicate()
I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1077): COMM
I/TZ_COMMON: tlc_key_db_util: (  844): DB Operation suceeded
I/TLC_TZ_CCM: register for default cert: (  844): Exercising TZ_CCM_register_default_TLC
I/TZ: client_server_communication(  844): Cmd id = 25, len = 19456
I/TZ: client_server_communication(  844): Calling Communicate()
I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1077): COMM
I/TLC_TZ_CCM: register for default cert: (  844): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: (  844): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
I/TZ_CCM_C_Finalize: (  844): DEBUG_CONTAINER_PROBLEM Exercising TZ_CCM_C_Finalize_TLC
I/TZ: client_server_communication(  844): Cmd id = 41, len = 19456
I/TZ: client_server_communication(  844): Calling Communicate()
I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1077): COMM
I/TZ: client_server_communication(  844): Client_Server_Close was called
I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(1) 16
I/TZ_CCM_SERVER( 1077): CLOSESWCONN
D/QSEECOMAPI: ( 1077): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1077): QSEECom_shutdown_app, app_id = 3
I/TZ: client_server_communication(  844): Client_Server_Close succeeded
D/UMC:CloudMDMSecurity( 7402): ccmRegisterForDefaultCertificate: 0
D/UMC:CloudMDMSecurity( 7402): TIMA service call for password change success!!
D/UMC:AdminManager( 7402): init - start
D/UMC:AdminManager( 7402): loadAdmins
,D/UMC:AdminManager( 7402): startPolicyHandlers
,I/UMC:TestPolicyHandler( 7402): Setup is called in testpolicyhandler
,D/UMC:AdminManager( 7402): init - end
,V/UMC:AlarmHandler( 7402): Enter loadList
,D/GSLBManager( 7402): migrateStoredUrlFromOldPref
,D/GSLBManager( 7402): migrateStoredUrlFromOldPref : Migration Not Needed
,D/UMC:UMCAdmin( 7402): deactivateUMCAdminIfNotRequired : -1
,E/UMC:Utils( 7402): Admin not found in package com.samsung.knoxpb.mdm
D/UMC:UMCAdmin( 7402): deactivateUMCAdmin : -1
,D/UMC:UMCAdmin( 7402): isContainer : 0
,W/LicenseLogService(  844): log() failed
,D/EnterpriseDeviceManagerService(  844): isManagedProfileUser(): userId = 0
,E/UMC:UMCAdmin( 7402): No active admin owned by uid 10179
D/UMC:UMCAdmin( 7402): isContainer : 0
,D/UMC:UMCAdmin( 7402): deactivateUMCAdmin - UMC App Admin deactivated
,V/UMC:AlarmHandler( 7402): onReceive :Intent { flg=0x14 cmp=com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler (has extras) }
,D/QuickStartReceiver( 7402): Msg Id : 2
D/QuickStartReceiver( 7402): model : SM-G900F
D/QuickStartReceiver( 7402): id : 100
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WebViewFactory( 7452): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7452): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/Finsky  ( 6586): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6586): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6586): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  844): Killing 5911:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,I/LibraryLoader( 7452): Loading: webviewchromium
,I/LibraryLoader( 7452): Time to load native libraries: 3 ms (timestamps 8899-8902)
,I/LibraryLoader( 7452): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7452): Binding Chromium to main looper Looper (main, tid 1) {3b53c0b5}
,I/LibraryLoader( 7452): Expected native library version number "",actual native library version number ""
,I/chromium( 7452): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7452): Initializing chromium process, renderers=0
,W/art     ( 7452): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7452): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7452): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7452): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/libprocessgroup(  844): failed to open /acct/uid_1000/pid_5911/cgroup.procs: No such file or directory
,I/Adreno-EGL( 7452): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7452): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7452): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7452): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7452): Remote Branch: 
I/Adreno-EGL( 7452): Local Patches: 
I/Adreno-EGL( 7452): Reconstruct Branch: 
,W/ActivityManager(  844): Activity pause timeout for ActivityRecord{5f6e885 u0 com.test.thalitest/.MainActivity t17}
,W/chromium( 7452): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7452): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7452): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7452): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7452): CordovaWebView is running on device made by: samsung
,W/art     ( 7452): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7452): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 7452): performCreate Call secproduct feature valuefalse
D/Activity( 7452): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 7452): Render dirty regions requested: true
,D/ActivityManager(  844): post active user change for 0
,D/KnoxTimeoutHandler(  844): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  844): handleActiveUserChange for user 0
,I/SurfaceFlinger(  249): id=14 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/StatusBarManagerService(  844): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  844): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/OpenGLRenderer( 7452): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7452): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7452): Enabling debug mode 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/InputMethodManagerService(  844): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  844): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,W/IInputConnectionWrapper( 7452): showStatusIcon on inactive InputConnection
I/Timeline( 7452): Timeline: Activity_idle id: android.os.BinderProxy@26ce511c time:99573
W/ActivityManager(  844): mDVFSHelper.release()
I/Timeline(  844): Timeline: Activity_windows_visible id: ActivityRecord{5f6e885 u0 com.test.thalitest/.MainActivity t17} time:99576
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,W/ContextImpl(  844): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/chromium( 7452): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7452): 
,D/JsMessageQueue( 7452): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7452): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1259381504
,D/JX-Cordova( 7452): jxcore cordova android initializing
,E/SMD     (  287): DCD ON
,W/jxcore-log( 7452): Initializing JXcore engine
,W/jxcore-log( 7452): JXcore engine is ready
,W/jxcore-log( 7452): Starting JXcore engine
,E/auditd  ( 2154): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  844): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  844): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  844): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7532): MountEmulatedStorage()
E/Zygote  ( 7532): v2
I/libpersona( 7532): KNOX_SDCARD checking this for 1000
I/libpersona( 7532): KNOX_SDCARD not a persona
I/ActivityManager(  844): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7532 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7532): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7532): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7532): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7532): TimaSignature is unavailable
,D/ActivityThread( 7532): Added TimaKeyStore provider
,D/ResourcesManager( 7532): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7532):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7532):  SeDenialReceiver : File path = null
,I/ActivityManager(  844): Killing 6265:com.sec.providers.settingsearch/u0a168 (adj 15): bgCount ##41
,W/jxcore-log( 7452): Platform android
W/jxcore-log( 7452): 
W/jxcore-log( 7452): Process ARCH arm
W/jxcore-log( 7452): 
,W/libprocessgroup(  844): failed to open /acct/uid_10168/pid_6265/cgroup.procs: No such file or directory
,I/jxcore-log( 7452): JXcore Cordova bridge is ready!
I/jxcore-log( 7452): 
W/jxcore-log( 7452): JXcore engine is started
,I/jxcore-log( 7452): Toggling radios to true
I/jxcore-log( 7452): 
,D/BluetoothAdapter( 7452): enable()
,D/BluetoothAdapter( 7452): enable(): BT is already enabled..!
,D/WifiService(  844): New client listening to asynchronous messages
,I/WifiManager( 7452): packageName : com.test.thalitest
,D/SecContentProvider(  844): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  844): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  844): mCursor = null
,D/WifiService(  844): setWifiEnabled: true pid=7452, uid=10200
,E/WifiService(  844): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  844): Permission Denial: getCurrentUser() from pid=7452, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  844): Failed getting userId using ActivityManagerNative
W/WifiService(  844): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7452, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  844): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  844): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  844): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  844): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  844): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  844): name = wifi_on
,I/WifiService(  844): disconnect: pid=7452, uid=10200
,I/wpa_supplicant( 1290): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7452): Radios toggled
I/jxcore-log( 7452): 
,I/jxcore-log( 7452): My device name is: samsung-SM-G900F
I/jxcore-log( 7452): 
,I/wpa_supplicant( 1290): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1290): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1290): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1290): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  844): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1290): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1290): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1290): Disconnected - do not scan
I/wpa_supplicant( 1290): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  844): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
,E/WifiStateMachine(  844): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  844): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  844): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  844): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  844): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  844): do suspend true
,D/WifiP2pService(  844): InactiveState{ what=143375 }
,D/WifiP2pService(  844): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  282): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1679): Read error: ssl=0xaf11b600: I/O error during system call, Connection timed out
,V/NativeCrypto( 1679): SSL shutdown failed: ssl=0xaf11b600: I/O error during system call, Broken pipe
,E/WifiStateMachine(  844): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  844): updateNetworkInfo()
,D/ConnectivityService(  844): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  844): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,E/WifiConfigStore(  844): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  844): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  844): DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  844): Forcing reevaluation
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  844): EvaluatingState{ when=-5ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  844): Validated
,E/WifiStateMachine(  844): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1290): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1290): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1290): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1290): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1290): First Scan Start
,I/wpa_supplicant( 1290): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine(  844): ConnectModeState: Network connection lost 
E/WifiStateMachine(  844): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
E/WifiStateMachine(  844): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  844): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/native  (  844): do suspend true,
,D/WifiP2pService(  844): InactiveState{ what=143375 }
D/WifiP2pService(  844): P2pEnabledState{ what=143375 }
,I/WifiTrafficPoller(  844): evaluateTrafficStatsPolling
,I/CLocInfoService(  844): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/Hs20UtilService( 1304): Starting #6
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 1304): Message received 5007
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/CommandListener(  282): Clearing all IP addresses on wlan0
,D/ConnectivityService(  844): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  844): calling update connectivity
D/ConnectivityService(  844):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  844):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,E/WifiStateMachine(  844): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/EntConnectivity(  844): Not allowed due to - mEnabled false
D/ConnectivityService(  844): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  844): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/WifiStateMachine(  844): updateConfiguredNetworkExpiration - currTime: 1453034302383
D/WifiStateMachine(  844): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  844): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  844): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  844): Disconnected - quitting
I/WifiTrafficPoller(  844): evaluateTrafficStatsPolling
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,E/WifiStateMachine(  844): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  844): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524292
,D/ConnectivityService(  844): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/CLocInfoService(  844): External Intent Received android.net.wifi.STATE_CHANGE
D/ConnectivityService(  844): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  844): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
E/WifiStateMachine(  844): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
E/WifiStateMachine(  844): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/CSLegacyTypeTracker(  844): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory( 1478): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker(  844): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/ConnectivityService(  844): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/WifiStateMachine(  844): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  844): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  844): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  844): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  844): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  844): setDetailed state send new extra info"NG700"
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/SecContentProvider2(  844): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  844): mCursor = null
,D/ConnectivityService(  844): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,E/ConnectivityService(  844): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,E/ConnectivityService(  844): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/SmartBondingService(  844): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,V/NetworkStats(  844): updateIfacesLocked()
D/NtpTrustedTime(  844): currentTimeMillis() cache hit
V/NetworkStats(  844): performPollLocked(flags=0x1)
,D/SmartBondingService(  844): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  844): getSBEnabled() enabled =false
D/SmartBondingService(  844): getSBEnabled() enabled =false
D/SmartBondingService(  844): getSBEnabled() enabled =false
,D/NetworkStatsFactory(  844): UpdateStatsForKnox
D/NtpTrustedTime(  844): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): 0
D/ConnectivityService(  844): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1170): updateDataNetType()
D/StatusBar.NetworkController( 1170): NoService, mRoamingIconId = 0
,D/SmartBondingService(  844): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  844): currentTimeMillis() cache hit
D/NtpTrustedTime(  844): currentTimeMillis() cache hit
V/NetworkStats(  844): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  844): currentTimeMillis() cache hit
,D/SecContentProvider2(  844): uri = 20 selection = getPromptCredentialsEnabled
,D/StatusBar.NetworkController( 1170): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/SecContentProvider2(  844): mCursor = null
V/NetworkStats(  844): performPollLocked() took 8ms
D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/NtpTrustedTime(  844): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,I/Hs20UtilService( 1304): Starting #7
,I/Hs20UtilService( 1304): Message received 5007
,D/NtpTrustedTime(  844): currentTimeMillis() cache hit
,D/NtpTrustedTime(  844): currentTimeMillis() cache hit
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  844): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
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
,I/PowerManagerService(  844): [PWL] Off : 15s ago
I/PowerManagerService(  844): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  844): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  844): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=844, ws=null) (elapsedTime=278)
,D/ConnectivityService(  844): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  844): updateDataUsageMap
,D/Tethering(  844): MasterInitialState.processMessage what=3
,D/SmartBondingService(  844): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  844): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  844): getSBEnabled() enabled =false
D/SmartBondingService(  844): getSBEnabled() enabled =false
D/SmartBondingService(  844): getSBEnabled() enabled =false
D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  844): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  844): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  844): CLoinfo wifi false
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5371): type=WIFI subType= reason=null isConnected=false
,I/PCWCLIENTTRACE_PushUtil( 6772): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6772): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 6772): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6772): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6772): noConnectivity : true
,W/SLocation(  844): No Active Data Connection
,I/DBG_DM  ( 3793): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/SystemBroadcastReceiver( 7150): [#DCM#] [DCM_Performance] onReceive completed in time  1175 microsec. 
,I/SystemBroadcastReceiver( 7150): [#DCM#] Calling notifyListeners. 
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3793): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/accuweather( 2143): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,E/SMD     (  287): DCD ON
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,I/DCMController( 7150): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7150): [#DCM#] setIsConnectedForExtractors 
,E/Zygote  ( 7598): MountEmulatedStorage()
I/libpersona( 7598): KNOX_SDCARD checking this for 10002
E/Zygote  ( 7598): v2
I/libpersona( 7598): KNOX_SDCARD not a persona
,I/ActivityManager(  844): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7598 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7598): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7598): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7598): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7598): TimaSignature is unavailable
,D/ActivityThread( 7598): Added TimaKeyStore provider
,D/ResourcesManager( 7598): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,E/Watchdog(  844): !@Sync 3
,I/ActivityManager(  844): Killing 6734:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7616): MountEmulatedStorage()
E/Zygote  ( 7616): v2
I/libpersona( 7616): KNOX_SDCARD checking this for 1000
I/libpersona( 7616): KNOX_SDCARD not a persona
,I/ActivityManager(  844): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7616 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7616): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7616): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7616): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7616): TimaSignature is unavailable
,D/ActivityThread( 7616): Added TimaKeyStore provider
,D/ResourcesManager( 7616): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,W/libprocessgroup(  844): failed to open /acct/uid_10015/pid_6734/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 7616): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7616): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7616): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7616): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7616): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7616): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/wpa_supplicant( 1290): nl80211: Received scan results (6 BSSes)
I/wpa_supplicant( 1290): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1290): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1290): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1290): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  844): [1,453,034,303,409 ms] noteScanEnd no scan source
,E/WifiStateMachine(  844): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3c6e787c sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  844): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  844): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  844): setDetailed state send new extra info0x
,D/SecContentProvider2(  844): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  844): mCursor = null
,I/CLocInfoService(  844): External Intent Received android.net.wifi.SCAN_RESULTS
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7636): MountEmulatedStorage()
E/Zygote  ( 7636): v2
I/libpersona( 7636): KNOX_SDCARD checking this for 10011
I/libpersona( 7636): KNOX_SDCARD not a persona
,I/ActivityManager(  844): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7636 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant( 1290): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1290): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1290): Associated with C0.AA.48
,E/WifiStateMachine(  844): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  844): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,I/SELinux ( 7636): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7636): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7636): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2(  844): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  844): mCursor = null
,I/wpa_supplicant( 1290): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1290): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  844): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  844): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  844): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  844): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  844): mCursor = null
,D/TimaKeyStoreProvider( 7636): TimaSignature is unavailable
,D/ActivityThread( 7636): Added TimaKeyStore provider
,I/wpa_supplicant( 1290): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1290): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1290): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1290): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1290): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1290): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1290): Blacklist: Clear (temp) 
I/wpa_supplicant( 1290): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  844): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  844): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  844): Network connection established
,D/WifiNative-HAL(  844): callSECApiVoid - ID [50]
,E/WifiStateMachine(  844): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,D/ResourcesManager( 7636): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,E/WifiStateMachine(  844): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  844): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  844): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  844): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  844): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  844): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  844): Got NetworkAgent Messenger
D/ConnectivityService(  844): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  844): updateNetworkInfo()
D/ConnectivityService(  844): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  844): NetworkAgent connected
,E/WifiStateMachine(  844): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  844): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  844): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  844): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  282): Setting iface cfg
E/WifiStateMachine(  844): Start Dhcp Watchdog 2
,D/SecContentProvider2(  844): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  844): mCursor = null
,E/WifiStateMachine(  844): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  844): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  844): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/ActivityManager(  844): Killing 6755:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,I/FOTA_Client( 7636): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7636): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7636): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7636): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7636): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7655): MountEmulatedStorage()
,E/Zygote  ( 7655): v2
I/libpersona( 7655): KNOX_SDCARD checking this for 10019
I/libpersona( 7655): KNOX_SDCARD not a persona
,I/ActivityManager(  844): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7655 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  844): Killing 6455:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,E/WifiStateMachine(  844): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  844): do suspend false
,D/SecContentProvider2(  844): uri = 20 selection = getPromptCredentialsEnabled
,D/WifiP2pService(  844): InactiveState{ what=143375 }
,D/WifiP2pService(  844): P2pEnabledState{ what=143375 }
D/SecContentProvider2(  844): mCursor = null
,I/SELinux ( 7655): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  844): failed to open /acct/uid_10016/pid_6755/cgroup.procs: No such file or directory
,I/SELinux ( 7655): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7655): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7655): TimaSignature is unavailable
,D/ActivityThread( 7655): Added TimaKeyStore provider
,D/ResourcesManager( 7655): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7655): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/libprocessgroup(  844): failed to open /acct/uid_10034/pid_6455/cgroup.procs: No such file or directory
,I/KLMS-2.4.503: ( 7655): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453034303721
,I/KLMS-2.4.503: ( 7655): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7655): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7655): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  844): Killing 4723:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7670): MountEmulatedStorage()
E/Zygote  ( 7670): v2
I/libpersona( 7670): KNOX_SDCARD checking this for 10037
I/libpersona( 7670): KNOX_SDCARD not a persona
,I/ActivityManager(  844): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7670 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7670): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7670): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7670): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7670): TimaSignature is unavailable
,D/ActivityThread( 7670): Added TimaKeyStore provider
,D/ResourcesManager( 7670): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,W/libprocessgroup(  844): failed to open /acct/uid_10035/pid_4723/cgroup.procs: No such file or directory
,I/SO_AGENT( 7670): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5265): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6814): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6814): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6814): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6814): [SLFUCHKMGR] constructor called
,I/SA      ( 6814): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6814): [OR] == isSIMCardReady false ==
,I/SA      ( 6814): [SCU] == networkStateCheck == false
,E/SPPClientService( 5265): [[SystemStateMonitorService]] No Active Internet
,I/SA      ( 6814): [OR] onReceive END
,E/dhcpcd  ( 7687): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/ActivityManager(  844): Killing 6081:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/dhcpcd  ( 7687): version 5.5.6 starting
,E/dhcpcd  ( 7687): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  844): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7691 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,E/Zygote  ( 7691): MountEmulatedStorage()
,E/Zygote  ( 7691): v2
I/libpersona( 7691): KNOX_SDCARD checking this for 10071
I/libpersona( 7691): KNOX_SDCARD not a persona
,I/dhcpcd  ( 7687): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7687): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7687): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7687): bssid match
,I/dhcpcd  ( 7687): wlan0: rebinding lease of 192.168.1.135
,I/SELinux ( 7691): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7691): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7691): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  844): failed to open /acct/uid_10042/pid_6081/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7691): TimaSignature is unavailable
,D/ActivityThread( 7691): Added TimaKeyStore provider
,D/ResourcesManager( 7691): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7691): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7691): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7691): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/comsamsunglog( 7691): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7691): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7691): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7691): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7691): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7691): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7691): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7691): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  844): name = aw_daemon_service_key_agree_popup_check
,D/SettingsProvider(  844): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  844): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  844): selectionArgs: false
D/SettingsProvider(  844): selectionArgs: 10071
D/SecContentProvider(  844): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  844): ret = -1
,D/daemonapp( 1345): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7691): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7691): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7691): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
D/accuweather( 7691): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7691): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7691): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1345): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7691): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1345): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7691): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1345): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7691): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7691): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7711): MountEmulatedStorage()
E/Zygote  ( 7711): v2
I/libpersona( 7711): KNOX_SDCARD checking this for 1000
I/libpersona( 7711): KNOX_SDCARD not a persona
,I/ActivityManager(  844): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7711 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  844): Killing 5709:com.android.mms/u0a50 (adj 15): bgCount ##41
,I/SELinux ( 7711): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/CountryDetector(  844): No listener is left
I/SELinux ( 7711): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7711): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7711): TimaSignature is unavailable
,D/ActivityThread( 7711): Added TimaKeyStore provider
,D/ResourcesManager( 7711): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/libprocessgroup(  844): failed to open /acct/uid_10050/pid_5709/cgroup.procs: No such file or directory
,W/ResourcesManager( 7711): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7711): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7711): premStatus:2
,I/KnoxUsageLogPro( 7711): isEulaShown : false
I/KnoxUsageLogPro( 7711): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7726): MountEmulatedStorage()
,E/Zygote  ( 7726): v2
I/libpersona( 7726): KNOX_SDCARD checking this for 10088
I/libpersona( 7726): KNOX_SDCARD not a persona
,I/ActivityManager(  844): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7726 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  844): Killing 6835:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,I/SELinux ( 7726): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7726): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7726): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  844): failed to open /acct/uid_10051/pid_6835/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7726): TimaSignature is unavailable
,D/ActivityThread( 7726): Added TimaKeyStore provider
,D/ResourcesManager( 7726): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/ActivityManager(  844): Killing 6851:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,D/Headlines( 5512): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5512): getCountryCode(): countryCode = DE
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,D/Headlines( 5512): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5512): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 5512): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5512): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5512): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5512): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5512): requestUpdateNewsWelcomeCard !!! no welcome card
,E/Zygote  ( 7742): MountEmulatedStorage()
,E/Zygote  ( 7742): v2
I/libpersona( 7742): KNOX_SDCARD checking this for 10128
I/libpersona( 7742): KNOX_SDCARD not a persona
,I/ActivityManager(  844): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7742 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  319): Explicit concurrent mark sweep GC freed 8730(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 272us total 12.146ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 8.079ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.679ms
,I/SELinux ( 7742): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  844): failed to open /acct/uid_10058/pid_6851/cgroup.procs: No such file or directory
,I/SELinux ( 7742): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7742): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7742): TimaSignature is unavailable
,D/ActivityThread( 7742): Added TimaKeyStore provider
,D/ResourcesManager( 7742): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7742): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7742): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7742): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7742): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7742): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7742): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7742): Loading: webviewchromium
,I/LibraryLoader( 7742): Time to load native libraries: 5 ms (timestamps 5163-5168)
,I/LibraryLoader( 7742): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7742): Binding Chromium to main looper Looper (main, tid 1) {2901627b}
,I/LibraryLoader( 7742): Expected native library version number "",actual native library version number ""
,I/chromium( 7742): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7742): Initializing chromium process, renderers=0
,W/art     ( 7742): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7742): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7742): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7742): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7742): Requires BLUETOOTH permission
,I/Adreno-EGL( 7742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7742): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7742): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7742): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7742): Remote Branch: 
I/Adreno-EGL( 7742): Local Patches: 
I/Adreno-EGL( 7742): Reconstruct Branch: 
,I/NSApplication( 7742): Starting up...
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7801): MountEmulatedStorage()
,E/Zygote  ( 7801): v2
I/libpersona( 7801): KNOX_SDCARD checking this for 10138
I/libpersona( 7801): KNOX_SDCARD not a persona
,I/ActivityManager(  844): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7801 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  844): Killing 6282:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/jxcore-log( 7452): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7452): 
,I/SELinux ( 7801): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7801): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7801): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7801): TimaSignature is unavailable
,D/ActivityThread( 7801): Added TimaKeyStore provider
,D/ResourcesManager( 7801): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7801): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7801): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7801): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup(  844): failed to open /acct/uid_1000/pid_6282/cgroup.procs: No such file or directory
,D/QuickConnect( 7801): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7801): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7801): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7817): MountEmulatedStorage()
,E/Zygote  ( 7817): v2
I/libpersona( 7817): KNOX_SDCARD checking this for 10163
I/libpersona( 7817): KNOX_SDCARD not a persona
,I/ActivityManager(  844): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7817 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/dhcpcd  ( 7687): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,I/ActivityManager(  844): Killing 6874:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,I/SELinux ( 7817): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7817): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7817): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/dhcpcd  ( 7687): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  844): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  844): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  844): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/TimaKeyStoreProvider( 7817): TimaSignature is unavailable
,D/ActivityThread( 7817): Added TimaKeyStore provider
,D/ResourcesManager( 7817): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7817): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7817): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7817): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7817): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  844): failed to open /acct/uid_10098/pid_6874/cgroup.procs: No such file or directory
,D/RCPManagerService(  844): exchangeData() failure , invalid userId
,D/RCPManagerService(  844): exchangeData() failure , invalid userId
D/RCPManagerService(  844): exchangeData() failure , invalid userId
,D/RCPManagerService(  844): exchangeData() failure , invalid userId
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7861): MountEmulatedStorage()
,E/Zygote  ( 7861): v2
I/libpersona( 7861): KNOX_SDCARD checking this for 10078
I/libpersona( 7861): KNOX_SDCARD not a persona
,I/ActivityManager(  844): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7861 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,I/SELinux ( 7861): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7861): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/WifiStateMachine(  844): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  844): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/SELinux ( 7861): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
E/native  (  844): do suspend true
,D/RCPManagerService(  844): exchangeData() failure , invalid userId
,D/WifiP2pService(  844): InactiveState{ what=143375 }
,D/WifiP2pService(  844): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  844): WifiStateMachine DHCP successful
,E/WifiStateMachine(  844): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  844): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
D/ConnectivityService(  844): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  844): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  844): Not connected state, yet.
E/WifiStateMachine(  844): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiStateMachine(  844): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  844): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  844): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  844): callSECApiInt - ID [210]
E/WifiStateMachine(  844): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  844): updateNetworkInfo()
V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/ConnectivityService(  844): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  844): Adding iface wlan0 to network 503
,I/CLocInfoService(  844): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  844): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger(  844): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  844): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  844): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  844): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/TimaKeyStoreProvider( 7861): TimaSignature is unavailable
,D/ActivityThread( 7861): Added TimaKeyStore provider
,D/RCPManagerService(  844): exchangeData() failure , invalid userId
,E/WifiStateMachine(  844): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  844): Now, connected state.
E/WifiStateMachine(  844): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/ActivityManager(  844): Killing 6927:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,I/jxcore-log( 7452): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7452): 
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
I/jxcore-log( 7452): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7452): 
,D/ConnectivityService(  844): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  844): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  844): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  844): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  844): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  844): updateSourceRoutes : add src route for:192.168.1.135
,V/        (  282): QcRouteController
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7532): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7532): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7532): StateMachine : Current State = 1
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,E/WifiStateMachine(  844): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  844): evaluateTrafficStatsPolling
,I/CLocInfoService(  844): External Intent Received android.net.wifi.STATE_CHANGE
,V/        (  282): QcRouteController
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  844): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  844): evaluateTrafficStatsPolling
V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,I/WifiTrafficPoller(  844): mBoosterFLAG : 0
I/WifiTrafficPoller(  844): current booster mode : FullMode
D/WifiNative-HAL(  844): callSECApiVoid - ID [212]
,I/CLocInfoService(  844): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,V/        (  282): QcRouteController
,E/WifiStateMachine(  844): ConnectedState Enter  mScreenOn=false scanperiod=20000
I/WifiStateMachine(  844): REQUEST_POWER_SAVE_ON
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
V/        (  282): QcRouteController
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/        (  282): QcRouteController
,W/libprocessgroup(  844): failed to open /acct/uid_10033/pid_6927/cgroup.procs: No such file or directory
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,I/jxcore-log( 7452): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7452): 
,V/        (  282): QcRouteController
V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/        (  282): QcRouteController
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/        (  282): QcRouteController
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,I/jxcore-log( 7452): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7452): 
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,I/jxcore-log( 7452): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7452): 
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,D/ConnectivityService(  844): Setting Dns servers for network 503 to [/192.168.1.1]
V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,D/Nat464Xlat(  844): requiresClat: netType=1, connected=false, hasIPv4Address=true
I/jxcore-log( 7452): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7452): 
D/ConnectivityService(  844): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  844): updateNetworkInfo()
D/ConnectivityService(  844): calling update connectivity
E/ConnectivityService(  844): updateNetworkInfo()
D/ConnectivityService(  844): ignoring duplicate network state non-change
D/ConnectivityService(  844): ignoring duplicate network state non-change
D/ConnectivityService(  844): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  844): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  844): calling update connectivity
D/ConnectivityService(  844): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  844):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  844):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  844):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  844): currentScore = 0, newScore = 60
D/ConnectivityService(  844):    accepting network in place of null
D/ConnectivityService(  844): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  844): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  844): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  844): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  844): Validated
,D/TelephonyNetworkFactory( 1478): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/CSLegacyTypeTracker(  844): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  844): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  844): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
D/ConnectivityService(  844): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  844): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  844): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  844): getSBEnabled() enabled =false
D/SmartBondingService(  844): getSBEnabled() enabled =false
D/SmartBondingService(  844): getSBEnabled() enabled =false
V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
V/NetworkStats(  844): updateIfacesLocked()
D/NtpTrustedTime(  844): currentTimeMillis() cache hit
V/NetworkStats(  844): performPollLocked(flags=0x1)
V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
D/ConnectivityService(  844): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/NetworkStatsFactory(  844): UpdateStatsForKnox
D/ConnectivityService(  844): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
D/ConnectivityService(  844): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/EntConnectivity(  844): Not allowed due to - mEnabled false
D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  844): calling update connectivity
D/ConnectivityService(  844):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NtpTrustedTime(  844): currentTimeMillis() cache hit
D/ConnectivityService(  844):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkStats(  844): performPollLocked() took 2ms
D/ConnectivityService(  844): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): 0
D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524290
D/StatusBar.NetworkController( 1170): updateDataNetType()
D/StatusBar.NetworkController( 1170): NoService, mRoamingIconId = 0
D/ConnectivityService(  844): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  844): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  844):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  844):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  844): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  844): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  844): calling update connectivity
D/ConnectivityService(  844):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  844):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  844): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
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
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
V/BitmapFactory( 7817): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
D/ConnectivityService(  844): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524290
D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1170): updateDataNetType()
D/StatusBar.NetworkController( 1170): NoService, mRoamingIconId = 0
D/StatusBar.NetworkController( 1170): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/art     (  844): Explicit concurrent mark sweep GC freed 64454(3MB) AllocSpace objects, 10(225KB) LOS objects, 30% free, 36MB/52MB, paused 1.981ms total 162.597ms
D/SmartBondingService(  844): getNetworkEnabled : wifi : true mobile : true
D/NtpTrustedTime(  844): currentTimeMillis() cache hit
D/NtpTrustedTime(  844): currentTimeMillis() cache hit
D/NtpTrustedTime(  844): currentTimeMillis() cache hit
D/NtpTrustedTime(  844): currentTimeMillis() cache hit
D/NtpTrustedTime(  844): currentTimeMillis() cache hit
V/NetworkStats(  844): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  844): currentTimeMillis() cache hit
D/SecurityLogAgent( 7532): StateMachine : Changed Current State = 1
D/ResourcesManager( 7861): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
I/ActivityManager(  844): Killing 6897:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
D/com.peel.receiver.ConnectivityActionReceiver( 5616): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): last run: 1453023874109 -- System.currentTimeMillis()-last_run: 10431393
D/com.peel.receiver.ConnectivityActionReceiver( 5616): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): ... skip last_72_check
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7896): MountEmulatedStorage()
E/Zygote  ( 7896): v2
I/libpersona( 7896): KNOX_SDCARD checking this for 10178
I/libpersona( 7896): KNOX_SDCARD not a persona
,D/BadgeProvider( 7861): onCreate
,D/BadgeProvider( 7861): DatabaseHelper
,I/ActivityManager(  844): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7896 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7896): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7896): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7896): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,W/ActivityManager(  844): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/BadgeProvider( 7861): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 7896): TimaSignature is unavailable
,D/Launcher.Model( 1492): reloadBadges entered.
D/BadgeProvider( 7861): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7861): sendNotify, [notify] : null
D/BadgeProvider( 7861): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7861): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7861): update, [UpdateCount] : 1
,D/ActivityThread( 7896): Added TimaKeyStore provider
,D/ResourcesManager( 7896): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,W/libprocessgroup(  844): failed to open /acct/uid_10099/pid_6897/cgroup.procs: No such file or directory
,I/ActivityManager(  844): Killing 6960:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2438): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2438): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7127): notifyNetworkActivated
,W/libprocessgroup(  844): failed to open /acct/uid_10020/pid_6960/cgroup.procs: No such file or directory
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 7127): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  844): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  844): uri = 14 selection = getSealedState
D/SecContentProvider2(  844): mCursor = null
,D/SecContentProvider2(  844): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  844): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  844): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2438): [AccountUtils] Account not ready
W/Kids    ( 2438): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2438): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2438): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2438): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2438): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2438): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2438): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2438): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2438): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2438): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2438): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2438): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/Hs20UtilService( 1304): Starting #8
,D/hcjo    ( 7127): AutoUpdateManager:IDLE:execute
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  844): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,D/InitializeManagerStateMachine( 7127): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7127): exit::IDLE
D/InitializeManagerStateMachine( 7127): entry::NETWORK_CHECK
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7127): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7127): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7127): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7127): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7127): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7127): entry::SUCCESS
D/hcjo    ( 7127): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7127): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7127): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/Hs20UtilService( 1304): Starting #9
,D/InitializeManagerStateMachine( 7127): exit::SUCCESS
D/InitializeManagerStateMachine( 7127): entry::IDLE
I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1304): Starting #10
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1304): Starting #11
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,I/jxcore-log( 7452): Test app app.js loaded
I/jxcore-log( 7452): 
,I/WifiStateMachine(  844): callSECApi what=220
,D/WifiStateMachine(  844): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/chromium( 7452): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PowerManagerService(  844): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=844
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  844): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Tethering(  844): MasterInitialState.processMessage what=3
D/SmartBondingService(  844): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  844): SmartBondingReceiver: wifi is connected
,D/SmartBondingService(  844): SmartBondingReceiver: wifi ap is not changed
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  844): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  844): CLocinfo wifi true 
,D/SmartBondingService(  844): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  844): getSBEnabled() enabled =false
D/SmartBondingService(  844): getSBEnabled() enabled =false
D/SmartBondingService(  844): getSBEnabled() enabled =false
D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  844): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  844): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2143): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7150): [#DCM#] [DCM_Performance] onReceive completed in time  217 microsec. 
,I/DBG_DM  ( 3793): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3793): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
I/SystemBroadcastReceiver( 7150): [#DCM#] Calling notifyListeners. 
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2205): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2205): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/DCMController( 7150): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7150): [#DCM#] setIsConnectedForExtractors 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
I/NetworkMonitor( 5371): type=WIFI subType= reason=null isConnected=true
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/SMD     (  287): DCD ON
,I/PCWCLIENTTRACE_PushUtil( 6772): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6772): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 6772): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6772): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DatabaseRebuilderTask( 7150): [#DCM#] postDBrebuildIntent rebuildLocation =  true
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FrameworkService( 7150): [#DCM#] onCreate FrameworkService 
,I/FrameworkService( 7150): [#DCM#] onCreate FrameworkService end 
,I/DCMConfig( 7150): [#DCM#] getSuccessState = true
I/FrameworkService( 7150): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
I/IntentHandler( 7150): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,I/DIAGMON_AGENT( 7616): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7616): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SecContentProvider2(  844): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  844): mCursor = null
,I/chromium( 7452): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/SystemUtils( 7150): [#DCM#] LM: false,AM:677089280
,I/DCMThreadPoolExecutor( 7150): [#DCM#] Task being added DatabaseRebuilderTask
,I/DCMThreadPoolExecutor( 7150): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@2956394c is submitted
I/FrameworkService( 7150): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 26673 mirosec. 
,I/FOTA_Client( 7636): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7636): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7636): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7636): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7636): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7655): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7655): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453034306091
,I/KLMS-2.4.503: ( 7655): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7655): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7655): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7655): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7655): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7670): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5265): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6814): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6814): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6814): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6814): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6814): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6814): [SCU] == networkStateCheck == true
,I/SA      ( 6814): [DM] getCountryCodeFromCSC : DE
I/SA      ( 6814): isChinaCountryCode : false
I/SA      ( 6814): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6814): [OR] == networkStateCheck true ==
,I/SA      ( 6814): [OR] GetMyCountryZoneTask
,I/SA      ( 6814): [OR] onReceive END
,I/SA      ( 6814): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6814): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,D/accuweather( 7691): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7691): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
I/SA      ( 6814): [SSP] query invoked
,I/SA      ( 6814): [TPMU] GetMccFromDB : null
I/SA      ( 6814): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6814): [TPM] isNoProxy(default) : true
,I/KnoxUsageLogPro( 7711): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7711): premStatus:2
,I/KnoxUsageLogPro( 7711): isEulaShown : false
I/KnoxUsageLogPro( 7711): KnoxUsageReceiver onReceive : not Processible, just return
,E/File    ( 6814): fail readDirectory() errno=2
,D/Headlines( 5512): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 5512): getCountryCode(): countryCode = DE
,D/Headlines( 5512): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5512): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5512): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5512): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5512): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5512): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5512): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7801): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7801): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7801): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/RCPManagerService(  844): exchangeData() failure , invalid userId
,D/RCPManagerService(  844): exchangeData() failure , invalid userId
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7532): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7532): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7532): StateMachine : Current State = 1
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7532): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 5616): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): last run: 1453023874109 -- System.currentTimeMillis()-last_run: 10432142
D/com.peel.receiver.ConnectivityActionReceiver( 5616): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): ... skip last_72_check
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2438): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2438): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7127): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7127): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7127): exit::IDLE
D/InitializeManagerStateMachine( 7127): entry::NETWORK_CHECK
D/ConnectivityService(  844): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7127): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7127): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7127): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7127): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7127): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 7127): entry::SUCCESS
D/hcjo    ( 7127): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7127): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 7127): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7127): exit::SUCCESS
D/InitializeManagerStateMachine( 7127): entry::IDLE
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  844): uri = 14 selection = getSealedState
D/SecContentProvider2(  844): mCursor = null
,D/SecContentProvider2(  844): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  844): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  844): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/Kids    ( 2438): [AccountUtils] Account not ready
W/Kids    ( 2438): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2438): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2438): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2438): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2438): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2438): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2438): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2438): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2438): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2438): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2438): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2438): 	at java.lang.Thread.run(Thread.java:818)
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,D/ConnectivityService(  844): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/SA      ( 6814): [RC New] Execute method=[GET] start
,I/SA      ( 6814): [RC New] Security=[true]
,I/System.out( 6814): Thread-1115(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6814): Thread-1115(ApacheHTTPLog):isShipBuild true
,I/System.out( 6814): Thread-1115(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/Atfwd_Sendcmd(  336): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  336): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/WifiStateMachine(  844): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  844): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  844): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  844): identical MTU - not setting
,D/ConnectivityService(  844): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  844): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
,V/        (  282): QcRouteController
,E/WifiStateMachine(  844): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/SmartBondingService(  844): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  844): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  844): getSBEnabled() enabled =false
,D/SmartBondingService(  844): getSBEnabled() enabled =false
,D/SmartBondingService(  844): getSBEnabled() enabled =false
,I/SA      ( 6814): [RC New] [v2liruge] api execute + 703
,I/SA      ( 6814): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6814): AsyncTask #1 calls detatch()
,V/        (  282): QcRouteController
,I/SA      ( 6814): [ODM] saveOpenData( GEO_IP, PL )
,W/NetworkManagementService(  844): route cmd failed: 
W/NetworkManagementService(  844): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  844): '
W/NetworkManagementService(  844): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  844): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  844): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  844): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  844): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  844): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  844): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  844): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  844): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  844): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  844): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  844): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  844): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  844): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  844): calling update connectivity
D/ConnectivityService(  844):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  844):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  844): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  844): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  844): calling update connectivity
D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524295
D/ConnectivityService(  844):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  844):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  844): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524295
,I/SA      ( 6814): [OCP] update openData : PL
,I/SA      ( 6814): [TPMU] getNetworkMcc : 
,I/SA      ( 6814): [SCU] saveMccToPreferece Start
,I/SA      ( 6814): [SCU] RegionMCC : 260
I/SA      ( 6814): [SSP] query invoked
,I/SA      ( 6814): [TPMU] GetMccFromDB : null
,I/SA      ( 6814): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6814): [SCU] saveMccToPreferece End
,I/SA      ( 6814): [RC New] executeRequest [v2liruge] end. 753
I/SA      ( 6814): [RC New] Execute end
I/SA      ( 6814): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6814): [OR] GetMyCountryZoneTask Success
,D/SSRM:m  (  844): SIOP:: AP = 410, PST = 423, CUR = 300
,I/dhcpcd  ( 7687): wlan0: sending IPv6 Router Solicitation
,D/PackageManager(  844): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager(  844): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  844): Reconfiguring input devices.  changes=0x00000010
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
E/Zygote  ( 7963): MountEmulatedStorage()
E/Zygote  ( 7963): v2
I/libpersona( 7963): KNOX_SDCARD checking this for 10034
I/libpersona( 7963): KNOX_SDCARD not a persona
,I/ActivityManager(  844): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7963 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,I/SELinux ( 7963): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7963): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7963): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/RegisteredServicesCache( 1465): empty dynamic service
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager( 1492): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 1492): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1492): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1492): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 7963): TimaSignature is unavailable
,D/ActivityThread( 7963): Added TimaKeyStore provider
,D/ResourcesManager( 1492): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 1492): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1492): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/SecContentProvider2(  844): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  844): mCursor = null
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/FeatureConfig( 7963): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService(  844): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  844): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  844): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(  844): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,I/WifiStateMachine(  844): REQUEST_POWER_SAVE_ON
,D/ResourcesManager(  844): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,E/WifiStateMachine(  844): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 7963): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7963): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7963): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 7963): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 7963): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7963): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7963): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 7963): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7963): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 7963): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7963): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 7963): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7963): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 7963): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 7963): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7963): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7963): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7963): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 7963): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7963): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 7963): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7963): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 7963): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7993): MountEmulatedStorage()
E/Zygote  ( 7993): v2
,I/libpersona( 7993): KNOX_SDCARD checking this for 10035
I/libpersona( 7993): KNOX_SDCARD not a persona
E/SMD     (  287): DCD ON
,I/ActivityManager(  844): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=7993 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 7993): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7993): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7993): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7993): TimaSignature is unavailable
,D/ActivityThread( 7993): Added TimaKeyStore provider
,D/ResourcesManager( 7993): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): checkState() : APP TYPE = Full
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8026): MountEmulatedStorage()
E/Zygote  ( 8026): v2
I/libpersona( 8026): KNOX_SDCARD checking this for 10017
I/libpersona( 8026): KNOX_SDCARD not a persona
,I/ActivityManager(  844): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=8026 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,I/SELinux ( 8026): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8026): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8026): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8026): TimaSignature is unavailable
,D/ActivityThread( 8026): Added TimaKeyStore provider
,D/ResourcesManager( 8026): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/SurfaceFlinger(  249): id=15 Removed Toast (8/9)
,I/SurfaceFlinger(  249): id=15 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PowerManagerService(  844): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 844) eventTime = 109871
,D/PowerManagerService(  844): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=844 (0x0)
,D/PowerManagerService(  844): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=844, ws=WorkSource{10059}) (elapsedTime=3480)
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/BluetoothManager( 7993): getConnectedDevices
,D/-----SIC-----( 7993): ------------------skip uv
,D/-----SIC-----( 7993): ------------------skip SPO2
,D/-----SIC-----( 7993): ------------------skip TGH
,I/SecureStorage( 8026): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  357): [INFO]: SPID(0x00000005)Credentials: uid 10017, gid 10017, pid 8026
I/SecureStorage(  357): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7993): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7993): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,V/MediaPlayer( 7993): decode(36, 19359868, 4230)
,V/MediaPlayerService(  292): decode(30, 19359868, 4230)
,V/MediaPlayerService(  292): player type = 3
,V/AwesomePlayer(  292): setDefault
,V/AwesomePlayer(  292): constructor
,V/AwesomePlayer(  292): setDefault
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
,V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
,V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(30, 19359868, 4230)
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0909060, 8, 0, 0)
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
,I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
,V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/AdaptiveEventManager( 1170): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1170): M updateContainers()
D/AdaptiveEventContainerSmall( 1170): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1170): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1170): pedoEvent == null
D/AdaptiveEventManager( 1170): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1170): M updateContainers()
D/AdaptiveEventContainerSmall( 1170): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1170): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1170): pedoEvent == null
I/GAV4    ( 7742): Thread[GAThread,5,main]: No campaign data found.
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0909060, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0909060, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0909060, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/ActivityManager(  844): Killing 6969:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0909060, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
I/AudioPlayer(  292): First fillBuffer call!!
V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0909060, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0909060, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0909060, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x74, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 7993): decode(38, 19213040, 15440)
V/MediaPlayerService(  292): decode(30, 19213040, 15440)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
,V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(30, 19213040, 15440)
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0522b00, 8, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService(  292): prepare
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
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0522b00, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0522b00, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0522b00, 1, 0, 0)
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
V/AudioCache(  292): notify(0xb0522b00, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
,V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
,E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,I/UpdateIcingCorporaServi( 1544): Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0522b00, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0522b00, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
,V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): addBatteryData
,V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
E/Zygote  ( 8075): MountEmulatedStorage()
I/libpersona( 8075): KNOX_SDCARD checking this for 10075
E/Zygote  ( 8075): v2
I/libpersona( 8075): KNOX_SDCARD not a persona
,V/AudioCache(  292): notify(0xb0522b00, 8, 0, 0)
I/ActivityManager(  844): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=8075 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x75, OMX_CommandStateSet, OMX_StateIdle)
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
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7993): decode(39, 19257568, 9226)
,I/SELinux ( 8075): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,V/MediaPlayerService(  292): decode(30, 19257568, 9226)
,I/SELinux ( 8075): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8075): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/MediaPlayerService(  292): player type = 3
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,V/AwesomePlayer(  292): setDefault
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
,V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(30, 19257568, 9226)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb2ac7880, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
,I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
,V/MediaPlayerService(  292): wait for prepare
,I/ActivityManager(  844): Killing 6990:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
,I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
,V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb2ac7880, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb2ac7880, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb2ac7880, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
,V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,D/TimaKeyStoreProvider( 8075): TimaSignature is unavailable
,D/ActivityThread( 8075): Added TimaKeyStore provider
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb2ac7880, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
,V/MediaPlayerService(  292): wait for playback complete
,I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
,E/DatabaseUtils(  844): Writing exception to parcel
E/DatabaseUtils(  844): java.lang.NullPointerException: key == null
E/DatabaseUtils(  844): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils(  844): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils(  844): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils(  844): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/DatabaseUtils(  844): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils(  844): 	at android.os.Binder.execTransact(Binder.java:446)
,W/libprocessgroup(  844): failed to open /acct/uid_10003/pid_6969/cgroup.procs: No such file or directory
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb2ac7880, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb2ac7880, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb2ac7880, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x76, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 7993): decode(40, 19364180, 4890)
V/MediaPlayerService(  292): decode(30, 19364180, 4890)
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
V/StagefrightPlayer(  292): setDataSource(30, 19364180, 4890)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d290, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
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
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
,V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xafa0d290, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d290, 5, 0, 0)
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d290, 1, 0, 0)
V/AudioCache(  292): prepared
,V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
,D/ResourcesManager( 8075): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(1)
,I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,I/AudioPlayer(  292): First fillBuffer call!!
V/AudioCache(  292): notify(0xafa0d290, 6, 0, 0)
V/AudioCache(  292): ignored
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  292): addBatteryData
,V/MediaPlayerService(  292): wait for playback complete
I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d290, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d290, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d290, 8, 0, 0)
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
,V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/MediaPlayer( 7993): decode(41, 19290344, 17329)
V/MediaPlayerService(  292): decode(30, 19290344, 17329)
V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
,V/AwesomePlayer(  292): reset_l(),
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(30, 19290344, 17329)
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d0b0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
,V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
,V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
,V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xafa0d0b0, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d0b0, 5, 0, 0)
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d0b0, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
,V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d0b0, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
,I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/UpdateIcingCorporaServi( 1544): UpdateCorporaTask done [took 155 ms] updated apps [took 154 ms] 
,D/FileShare-Server( 8075): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,W/libprocessgroup(  844): failed to open /acct/uid_1000/pid_6990/cgroup.procs: No such file or directory
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
V/AwesomePlayer(  292): postAudioEOS delayUs (0)
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d0b0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d0b0, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d0b0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x78, OMX_CommandStateSet, OMX_StateIdle)
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
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
,V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7993): decode(34, 19190536, 6644)
,V/MediaPlayerService(  292): decode(30, 19190536, 6644)
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
I/libpersona( 8104): KNOX_SDCARD checking this for 1000
V/AwesomePlayer(  292): setListener
I/libpersona( 8104): KNOX_SDCARD not a persona
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(30, 19190536, 6644)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d100, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
E/Zygote  ( 8104): MountEmulatedStorage()
E/Zygote  ( 8104): v2
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
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/ActivityManager(  844): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=8104 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  844): Killing 7011:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/SELinux ( 8104): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xafa0d100, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d100, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d100, 1, 0, 0)
V/AudioCache(  292): prepared
,V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/SELinux ( 8104): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8104): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(1)
,I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d100, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
,V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): First fillBuffer call!!
,I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
,E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
,V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d100, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d100, 7, 0, 0)
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
,V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d100, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x79, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
,I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
,I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
,V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7993): decode(33, 19266876, 23389)
,V/MediaPlayerService(  292): decode(31, 19266876, 23389)
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
V/StagefrightPlayer(  292): setDataSource(31, 19266876, 23389)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0909060, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(29) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
D/TimaKeyStoreProvider( 8104): TimaSignature is unavailable
D/ActivityThread( 8104): Added TimaKeyStore provider
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
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0909060, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0909060, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0909060, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,W/libprocessgroup(  844): failed to open /acct/uid_10112/pid_7011/cgroup.procs: No such file or directory
I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(2)
,I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,I/AudioPlayer(  292): First fillBuffer call!!
V/AudioCache(  292): notify(0xb0909060, 6, 0, 0)
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
,D/ResourcesManager( 8104): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0909060, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0909060, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0909060, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event ,
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1,
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
,I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
,I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted,
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
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear,
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0),
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/MediaPlayer( 7993): decode(42, 19156232, 8154)
V/MediaPlayerService(  292): decode(30, 19156232, 8154)
V/MediaPlayerService(  292): player type = 3
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault,
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0),
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
,V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
,V/StagefrightPlayer(  292): setDataSource(30, 19156232, 8154)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0522b00, 8, 0, 0)
V/AudioCache(  292): ignored,
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted,
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
,I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
,I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
,V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
,I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
,V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
,V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
,V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache(  292): notify(0xb0522b00, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0522b00, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0522b00, 1, 0, 0),
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
,V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
,V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  292): Audio channels(1)
,I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0),
V/AudioCache(  292): notify(0xb0522b00, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
,I/AudioPlayer(  292): First fillBuffer call!!
V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
,V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0522b00, 2, 0, 0)
,V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0522b00, 7, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset,
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0522b00, 8, 0, 0)
V/AudioCache(  292): ignored,
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
,I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
I/AudioPlayer(  292): reset out
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
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
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear,
V/MediaPlayer( 7993): decode(38, 19129712, 4804)
V/MediaPlayerService(  292): decode(30, 19129712, 4804)
V/MediaPlayerService(  292): player type = 3
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
,V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(30, 19129712, 4804)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb2ac7880, 8, 0, 0)
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
,V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
,I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
,V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
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
V/AudioCache(  292): notify(0xb2ac7880, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb2ac7880, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb2ac7880, 1, 0, 0)
,V/AudioCache(  292): prepared
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
V/AudioCache(  292): notify(0xb2ac7880, 6, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb2ac7880, 2, 0, 0)
,V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb2ac7880, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
,V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb2ac7880, 8, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
,I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
,I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7993): decode(43, 19099164, 9400)
V/MediaPlayerService(  292): decode(30, 19099164, 9400)
D/ShortcutReceiver( 8104):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
,V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(30, 19099164, 9400)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d290, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/MediaPlayer( 7993): decode(49, 19172584, 4112)
,V/MediaPlayerService(  292): decode(33, 19172584, 4112)
V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
,V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(33, 19172584, 4112)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d0b0, 8, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(34) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
,V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
,V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
,V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
,V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
,V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xafa0d290, 200, 973, 0)
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d290, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d290, 1, 0, 0)
V/AudioCache(  292): prepared
,V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xafa0d0b0, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d0b0, 5, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d0b0, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
,V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  292): Audio channels(1)
,I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d290, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d0b0, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): First fillBuffer call!!
,I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
,V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d0b0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d0b0, 7, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d0b0, 8, 0, 0)
,V/AudioCache(  292): ignored
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
I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
,V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 4194367, value : -2140176274
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 4194367, value : -2140176274
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d290, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d290, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d290, 8, 0, 0)
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
V/MediaPlayer( 7993): decode(44, 19307764, 52024)
,V/MediaPlayerService(  292): decode(30, 19307764, 52024)
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
V/StagefrightPlayer(  292): setDataSource(30, 19307764, 52024)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d100, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
,V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
V/MediaPlayerService(  292): wait for prepare
,D/PackageBroadcastService( 2438): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/PeopleContactsSync( 2438): CP2 sync disabled
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xafa0d100, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d100, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d100, 1, 0, 0)
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
V/AudioCache(  292): notify(0xafa0d100, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
,V/MediaPlayerService(  292): wait for playback complete
,I/SecureStorage(  357): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
I/SecureStorage(  357): [INFO]: SPID(0x00000005)PID: 8026, TID: 8037
,I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
,I/ActivityManager(  844): Killing 7032:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d100, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d100, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
,V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d100, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
,I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
,V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/MediaPlayer( 7993): decode(45, 19172584, 4112)
V/MediaPlayerService(  292): decode(31, 19172584, 4112)
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
,V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(31, 19172584, 4112)
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0909060, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(29) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService(  292): prepare
W/libprocessgroup(  844): failed to open /acct/uid_10118/pid_7032/cgroup.procs: No such file or directory
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0909060, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0909060, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0909060, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
,V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
,I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0909060, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/MediaPlayerService(  292): wait for playback complete
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0909060, 2, 0, 0)
,V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0909060, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0909060, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
,I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
,I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7993): decode(46, 19235660, 21825)
V/MediaPlayerService(  292): decode(31, 19235660, 21825)
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
,V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(31, 19235660, 21825)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0522b00, 8, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(32) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
,I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
,I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0522b00, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0522b00, 5, 0, 0)
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0522b00, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
,V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
,I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0522b00, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
I/AudioPlayer(  292): First fillBuffer call!!
,I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
V/MediaPlayerService(  292): wait for playback complete
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0522b00, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0522b00, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0522b00, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
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
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7993): decode(47, 19134596, 21552)
V/MediaPlayerService(  292): decode(31, 19134596, 21552)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
,V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(31, 19134596, 21552)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb2ac7880, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(29) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
,I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
,I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb2ac7880, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb2ac7880, 5, 0, 0)
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb2ac7880, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
,V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb2ac7880, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
I/AudioPlayer(  292): First fillBuffer call!!
V/MediaPlayerService(  292): wait for playback complete
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb2ac7880, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
,V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb2ac7880, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb2ac7880, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
,I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
,I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7993): decode(48, 19228560, 7017)
V/MediaPlayerService(  292): decode(30, 19228560, 7017)
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
,V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(30, 19228560, 7017)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xafa0d0b0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
,V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
,V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xafa0d0b0, 200, 973, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d0b0, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d0b0, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
,V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d0b0, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
,I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
V/MediaPlayerService(  292): wait for playback complete
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xafa0d0b0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xafa0d0b0, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xafa0d0b0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
,I/OggExtractor(  292): ~OggExtractor --
I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
,V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
,I/SecureStorage( 8026): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 8026): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
,I/SecSQLiteOpenHelper( 7993): getWritableDatabase(pwd)
,I/SecSQLiteOpenHelper( 7993): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper( 7993): Open platform.db in secure mode
,D/SecSQLiteDatabase( 7993): Android Version: 5.0
,D/SecSQLiteDatabase( 7993): Load library secsqlite.so for Android 5.0
,I/SecSQLiteDatabase( 7993): openSecureDatabase...
,I/SecSQLiteDatabase( 7993): private openSecureDatabase...
,I/SecSQLiteConnectionPool( 7993): OpenSecure
I/SecSQLiteConnectionPool( 7993): OpenSecure with password
I/SecSQLiteConnectionPool( 7993): openSecureConnectionLocked
,I/SecSQLiteDatabase( 7993): ...private openSecureDatabase
I/SecSQLiteDatabase( 7993): ...openSecureDatabase
,I/SecSQLiteOpenHelper( 7993): ...getDatabaseLocked(b,b,pwd)
,D/SecSQLiteOpenHelper( 7993): ...getDatabaseLocked(b,b,pwd)
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7993): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,W/System.err( 7993): java.lang.NumberFormatException: Invalid int: "null"
,W/System.err( 7993): 	at java.lang.Integer.invalidInt(Integer.java:138)
W/System.err( 7993): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err( 7993): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err( 7993): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:449)
W/System.err( 7993): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1173)
W/System.err( 7993): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7993): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7993): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/AlarmManager(  844): waitForAlarm result :4
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  844): level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  844): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  844): stay LED for fully charged
,D/BatteryService(  844): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  844):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  844): Plugged
I/MotionRecognitionService(  844): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6772): mConnectivityHandler : connected
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6772): [hasSamungAccount] - No Samsung Account
,D/GCM     ( 1679): Connected
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CSTORAGE( 6772): ================================================
,I/CSTORAGE( 6772):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
,I/CSTORAGE( 6772): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6772): [GetString-S]
,E/art     ( 6772): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI( 6772): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1679): Message class com.google.f.a.a.p
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6772): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6772): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6772): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6772): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 6772): [ensureRegistration] - No Samsung account
,W/ContextImpl(  844): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,I/dhcpcd  ( 7687): wlan0: sending IPv6 Router Solicitation
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/GAV3    ( 7993): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  287): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/PreloadUpdateManagerStateMachine( 7127): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7127): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7127): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7127): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7127): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7127): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7127): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7127): entry::IDLE
,I/dhcpcd  ( 7687): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7687): wlan0: no IPv6 Routers available
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/PreloadUpdateManagerStateMachine( 7127): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7127): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7127): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7127): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7127): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7127): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7127): entry::IDLE
,D/FactoryTest( 6702): Not factory mode
,D/FactoryTest( 6702): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6702): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6702): still no open session command from host, so toast
,W/ContextImpl( 6702): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6702): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6702): Timeline: Activity_launch_request id:com.android.settings time:117202
,E/PersonaManagerService(  844): inState():  stateMachine is null !!
,V/ApplicationPolicy(  844): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  844): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  844): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/MTPRx   ( 6702): started activity for popup
,I/SQLiteSecureOpenHelper( 3554): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3554): getDatabaseLocked(b,b,pwd)...
,V/AlarmManager(  844): waitForAlarm result :4
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6702): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6702): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6702): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6702): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6702): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6702): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6702): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6702): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6702): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/InputMethodManagerService(  844): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  844): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@12fe0f94 attribute=null, token = android.os.BinderProxy@3e3164f4
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6702): dev.kiessupport is : TRUE
,D/Activity( 6702): performCreate Call secproduct feature valuefalse
D/Activity( 6702): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ActivityManager(  844): post active user change for 0
D/KnoxTimeoutHandler(  844): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  844): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/Timeline( 7452): Timeline: Activity_idle id: android.os.BinderProxy@26ce511c time:117590
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 1
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  844): [PWL] Off : 30s ago
,V/AlarmManager(  844): waitForAlarm result :4
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  844): SIOP:: AP = 380, PST = 413, CUR = 300
,E/SMD     (  287): DCD ON
,V/AlarmManager(  844): waitForAlarm result :4
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6586): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6586): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6586): [1] 5.onFinished: Scheduling replication attempt 3.
,W/ActivityManager(  844): mDVFSHelper.release()
,D/BatteryService(  844): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  844): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  844): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  844):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  844): Plugged
,I/MotionRecognitionService(  844): setPowerConnected  = true
,D/BatteryService(  844): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,I/ActivityManager(  844): Waited long enough for: ServiceRecord{312e920 u0 com.samsung.dcm/.framework.FrameworkService}
,I/ActivityManager(  844): Waited long enough for: ServiceRecord{d532d9 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:m  (  844): SIOP:: AP = 340, PST = 398, CUR = 300
,D/X       (  844): broadcastSiopLevelIntent:: currentSiopLevel = -1
,I/SystemBroadcastReceiver( 7150): [#DCM#] [DCM_Performance] onReceive completed in time  895 microsec. 
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,D/ContentApp( 1223):  LEVEL : -1
,E/Zygote  ( 8230): MountEmulatedStorage()
,E/Zygote  ( 8230): v2
,I/libpersona( 8230): KNOX_SDCARD checking this for 10054
,I/libpersona( 8230): KNOX_SDCARD not a persona
,I/SystemBroadcastReceiver( 7150): [#DCM#] Calling notifyListeners. 
,I/ActivityManager(  844): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=8230 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,I/DCMPolicyManager( 7150): [#DCM#] onReceive action = EVENT_SIOP
,I/SELinux ( 8230): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8230): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8230): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8230): TimaSignature is unavailable
,D/ActivityThread( 8230): Added TimaKeyStore provider
,D/ResourcesManager( 8230): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8230): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8230): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8230): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8230): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8230): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/TranscodeReceiver( 8230): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 8230): core_num = 4
,W/linker  ( 8230): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 8230): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 8230): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
,D/videowall-Global( 8230): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 8230):  SIOP_LEVEL: -1
,I/ActivityManager(  844): Killing 7048:com.samsung.helphub/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  844): failed to open /acct/uid_1000/pid_7048/cgroup.procs: No such file or directory
,E/SMD     (  287): DCD ON
,W/ContextImpl(  844): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,E/Watchdog(  844): !@Sync 4
,E/SMD     (  287): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/PowerManagerService(  844): [PWL] Off : 50s ago
,D/SSRM:m  (  844): SIOP:: AP = 330, PST = 382, CUR = 300
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,V/AlarmManager(  844): waitForAlarm result :4
,E/SMD     (  287): DCD ON
,D/BatteryService(  844): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  844): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  844): stay LED for fully charged
D/BatteryService(  844): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  844):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  844): Plugged
,I/MotionRecognitionService(  844): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6586): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6586): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6586): [1] 5.onFinished: Scheduling replication attempt 4.
,I/art     (  844): Explicit concurrent mark sweep GC freed 69580(4MB) AllocSpace objects, 16(386KB) LOS objects, 30% free, 36MB/52MB, paused 1.237ms total 102.909ms
,V/AlarmManager(  844): waitForAlarm result :8
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD ON,
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  844): SIOP:: AP = 330, PST = 370, CUR = 300
,E/SMD     (  287): DCD ON
,W/ContextImpl(  844): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  844): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  844): uri = 14 selection = getSealedState
D/SecContentProvider2(  844): mCursor = null
,D/SecContentProvider2(  844): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  844): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  844): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6555): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6555): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6555): 	at kfv.a(PG:65)
E/HttpOperation( 6555): 	at kff.u(PG:385)
E/HttpOperation( 6555): 	at kfb.a(PG:29)
E/HttpOperation( 6555): 	at kff.l(PG:132)
E/HttpOperation( 6555): 	at dsf.a(PG:807)
E/HttpOperation( 6555): 	at fhk.a(PG:1126)
E/HttpOperation( 6555): 	at fhk.a(PG:908)
E/HttpOperation( 6555): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6555): 	at ihi.a(PG:22)
E/HttpOperation( 6555): 	at kft.a(PG:91)
E/HttpOperation( 6555): 	at kfv.a(PG:62)
E/HttpOperation( 6555): 	... 8 more
E/HttpOperation( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6555): 	at gde.c(Unknown Source)
E/HttpOperation( 6555): 	at gde.b(Unknown Source)
E/HttpOperation( 6555): 	at ihi.a(PG:19)
E/HttpOperation( 6555): 	... 10 more
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  844): uri = 14 selection = getSealedState
,D/SecContentProvider2(  844): mCursor = null
,D/SecContentProvider2(  844): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  844): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  844): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6555): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6555): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6555): 	at kfv.a(PG:65)
E/HttpOperation( 6555): 	at kff.u(PG:385)
E/HttpOperation( 6555): 	at kfb.a(PG:29)
E/HttpOperation( 6555): 	at kff.l(PG:132)
E/HttpOperation( 6555): 	at ieo.a(PG:43)
E/HttpOperation( 6555): 	at iep.a(PG:93)
E/HttpOperation( 6555): 	at fhn.a(PG:59)
E/HttpOperation( 6555): 	at lex.a(PG:85)
E/HttpOperation( 6555): 	at lex.b(PG:132)
E/HttpOperation( 6555): 	at fhk.a(PG:1146)
E/HttpOperation( 6555): 	at fhk.a(PG:908)
E/HttpOperation( 6555): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6555): 	at ihi.a(PG:22)
E/HttpOperation( 6555): 	at kft.a(PG:91)
E/HttpOperation( 6555): 	at kfv.a(PG:62)
E/HttpOperation( 6555): 	... 12 more
E/HttpOperation( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6555): 	at gde.c(Unknown Source)
E/HttpOperation( 6555): 	at gde.b(Unknown Source)
E/HttpOperation( 6555): 	at ihi.a(PG:19)
E/HttpOperation( 6555): 	... 14 more
I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/ExperimentLoader( 6555): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6555): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6555): 	at kfv.a(PG:65)
E/ExperimentLoader( 6555): 	at kff.u(PG:385)
E/ExperimentLoader( 6555): 	at kfb.a(PG:29)
E/ExperimentLoader( 6555): 	at kff.l(PG:132)
E/ExperimentLoader( 6555): 	at ieo.a(PG:43)
E/ExperimentLoader( 6555): 	at iep.a(PG:93)
E/ExperimentLoader( 6555): 	at fhn.a(PG:59)
E/ExperimentLoader( 6555): 	at lex.a(PG:85)
E/ExperimentLoader( 6555): 	at lex.b(PG:132)
E/ExperimentLoader( 6555): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6555): 	at fhk.a(PG:908)
E/ExperimentLoader( 6555): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6555): 	at ihi.a(PG:22)
E/ExperimentLoader( 6555): 	at kft.a(PG:91)
E/ExperimentLoader( 6555): 	at kfv.a(PG:62)
E/ExperimentLoader( 6555): 	... 12 more
E/ExperimentLoader( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6555): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6555): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6555): 	at ihi.a(PG:19)
E/ExperimentLoader( 6555): 	... 14 more
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  844): uri = 14 selection = getSealedState
D/SecContentProvider2(  844): mCursor = null
,D/SecContentProvider2(  844): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  844): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  844): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6555): [getaccountstatus] Unexpected exception
E/HttpOperation( 6555): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6555): 	at kfv.a(PG:65)
E/HttpOperation( 6555): 	at kff.u(PG:385)
E/HttpOperation( 6555): 	at kfb.a(PG:29)
E/HttpOperation( 6555): 	at ixd.a(PG:248)
E/HttpOperation( 6555): 	at ixd.b(PG:206)
E/HttpOperation( 6555): 	at ixd.a(PG:175)
E/HttpOperation( 6555): 	at fig.a(PG:78)
E/HttpOperation( 6555): 	at lex.a(PG:85)
E/HttpOperation( 6555): 	at lex.b(PG:132)
E/HttpOperation( 6555): 	at fhk.a(PG:1146)
E/HttpOperation( 6555): 	at fhk.a(PG:908)
E/HttpOperation( 6555): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6555): 	at ihi.a(PG:22)
E/HttpOperation( 6555): 	at kft.a(PG:91)
E/HttpOperation( 6555): 	at kfv.a(PG:62)
E/HttpOperation( 6555): 	... 12 more
E/HttpOperation( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6555): 	at gde.c(Unknown Source)
E/HttpOperation( 6555): 	at gde.b(Unknown Source)
E/HttpOperation( 6555): 	at ihi.a(PG:19)
E/HttpOperation( 6555): 	... 14 more
,E/EsSyncAdapterService( 6555): Sync failure
E/EsSyncAdapterService( 6555): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6555): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6555): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6555): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6555): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6555): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6555): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6555): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6555): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6555): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6555): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6555): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6555): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6555): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6555): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6555): 	... 10 more
E/EsSyncAdapterService( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6555): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6555): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6555): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6555): 	... 12 more
E/EsSyncAdapterService( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6555): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6555): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6555): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6555): 	... 14 more
,D/PanelView( 1170): There is/are notification(s) 
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  844): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 154060, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  844): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  844): mCursor = null
,E/SQLiteLog( 1679): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  287): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/SSRM:m  (  844): SIOP:: AP = 320, PST = 361, CUR = 300
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,V/AlarmManager(  844): waitForAlarm result :4
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  287): DCD ON
,I/art     ( 1679): Explicit concurrent mark sweep GC freed 37943(2MB) AllocSpace objects, 26(2MB) LOS objects, 40% free, 17MB/29MB, paused 880us total 113.125ms
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6586): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6586): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6586): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 4
,I/PowerManagerService(  844): [PWL] Off : 75s ago
,E/SMD     (  287): DCD ON
,E/Watchdog(  844): !@Sync 5
,D/BatteryService(  844): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  844): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  844): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  844):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  844): Plugged
,I/MotionRecognitionService(  844): setPowerConnected  = true
,D/BatteryService(  844): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  844): SIOP:: AP = 320, PST = 355, CUR = 300
,E/SMD     (  287): DCD ON
,W/ContextImpl(  844): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  844): SIOP:: AP = 310, PST = 348, CUR = 300
,V/AlarmManager(  844): waitForAlarm result :4
,D/BatteryService(  844): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  844): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  844): stay LED for fully charged
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  844): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/MotionRecognitionService(  844):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  844): Plugged
,I/MotionRecognitionService(  844): setPowerConnected  = true
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1679): Vacuum at: now=1453034380480 tag=VacuumService
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GoogleURLConnFactory( 1679): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  844): uri = 14 selection = getSealedState
D/SecContentProvider2(  844): mCursor = null
,D/SecContentProvider2(  844): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  844): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  844): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/Uploader( 1679): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1679): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1679): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1679): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1679): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1679): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1679): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1679): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1679): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1679): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/System.out( 1679): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1679): (HTTPLog)-Static: isShipBuild true
I/System.out( 1679): (HTTPLog)-Thread-203-228753251: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1679): Tagging socket 53 with tag 120100000000{4609,0} uid -1, pid: 1679, getuid(): 10012
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 1679): Tagging socket 61 with tag 120100000000{4609,0} uid -1, pid: 1679, getuid(): 10012
,D/Finsky  ( 6586): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6586): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6586): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1679): No account for auth token provided
,I/qtaguid ( 1679): Tagging socket 53 with tag 120100000000{4609,0} uid -1, pid: 1679, getuid(): 10012
,E/SMD     (  287): DCD ON
,W/Uploader( 1679): No account for auth token provided
,I/qtaguid ( 1679): Tagging socket 53 with tag 120100000000{4609,0} uid -1, pid: 1679, getuid(): 10012
,W/Uploader( 1679): No account for auth token provided
,I/qtaguid ( 1679): Tagging socket 53 with tag 120100000000{4609,0} uid -1, pid: 1679, getuid(): 10012
,W/Uploader( 1679):  no longer exists, so no auth token.
,I/qtaguid ( 1679): Tagging socket 53 with tag 120100000000{4609,0} uid -1, pid: 1679, getuid(): 10012
,E/SQLiteLog( 1679): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,V/AlarmManager(  844): waitForAlarm result :4
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7284): Starting books sync, d
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1679): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  844): uri = 14 selection = getSealedState
,D/SecContentProvider2(  844): mCursor = null
D/SecContentProvider2(  844): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  844): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  844): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7284): Authentication error
E/BooksAccountManager( 7284): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7284): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7284): null auth token
,I/qtaguid ( 7284): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7284, getuid(): 10082
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/qtaguid ( 7284): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7284, getuid(): 10082
,I/qtaguid ( 7284): Untagging socket 34,
,W/ApiaryClient( 7284): Error response from books API: {
W/ApiaryClient( 7284):  "error": {,
W/ApiaryClient( 7284):   "errors": [
W/ApiaryClient( 7284):    {
W/ApiaryClient( 7284):     "domain": "global",,
W/ApiaryClient( 7284):     "reason": "required",
W/ApiaryClient( 7284):     "message": "Login Required",
W/ApiaryClient( 7284):     "locationType": "header",
W/ApiaryClient( 7284):     "location": "Authorization"
W/ApiaryClient( 7284):    }
W/ApiaryClient( 7284):   ],
W/ApiaryClient( 7284):   "code": 401,
W/ApiaryClient( 7284):   "message": "Login Required"
W/ApiaryClient( 7284):  }
W/ApiaryClient( 7284): }
W/ApiaryClient( 7284): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7284): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5758109531603221277&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7284): Headers suppressed
D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  844): uri = 14 selection = getSealedState
,D/SecContentProvider2(  844): mCursor = null
D/SecContentProvider2(  844): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  844): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  844): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7284): Authentication error
E/BooksAccountManager( 7284): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7284): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7284): null auth token
,I/qtaguid ( 7284): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7284, getuid(): 10082
,I/qtaguid ( 7284): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7284, getuid(): 10082
,I/qtaguid ( 7284): Untagging socket 34
,W/ApiaryClient( 7284): Error response from books API: {
W/ApiaryClient( 7284):  "error": {
W/ApiaryClient( 7284):   "errors": [
W/ApiaryClient( 7284):    {
W/ApiaryClient( 7284):     "domain": "global",
W/ApiaryClient( 7284):     "reason": "required",
W/ApiaryClient( 7284):     "message": "Login Required",
W/ApiaryClient( 7284):     "locationType": "header",
W/ApiaryClient( 7284):     "location": "Authorization"
W/ApiaryClient( 7284):    }
W/ApiaryClient( 7284):   ],
W/ApiaryClient( 7284):   "code": 401,
W/ApiaryClient( 7284):   "message": "Login Required"
W/ApiaryClient( 7284):  }
W/ApiaryClient( 7284): }
,W/ApiaryClient( 7284): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7284): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5758109531603221277&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7284): Headers suppressed
D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  844): uri = 14 selection = getSealedState
,D/SecContentProvider2(  844): mCursor = null
D/SecContentProvider2(  844): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  844): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  844): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:446)
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/BooksAccountManager( 7284): Authentication error
E/BooksAccountManager( 7284): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7284): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7284): null auth token
,I/qtaguid ( 7284): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7284, getuid(): 10082
,I/qtaguid ( 7284): Untagging socket 34
,W/ApiaryClient( 7284): Error response from books API: {
W/ApiaryClient( 7284):  "error": {
W/ApiaryClient( 7284):   "errors": [
W/ApiaryClient( 7284):    {
W/ApiaryClient( 7284):     "domain": "global",
W/ApiaryClient( 7284):     "reason": "required",
W/ApiaryClient( 7284):     "message": "Login Required",
W/ApiaryClient( 7284):     "locationType": "header",
W/ApiaryClient( 7284):     "location": "Authorization"
W/ApiaryClient( 7284):    }
W/ApiaryClient( 7284):   ],
W/ApiaryClient( 7284):   "code": 401,
W/ApiaryClient( 7284):   "message": "Login Required"
W/ApiaryClient( 7284):  }
W/ApiaryClient( 7284): }
,W/ApiaryClient( 7284): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7284): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5758109531603221277&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7284): Headers suppressed
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 5
,E/BooksSync( 7284): Soft error
E/BooksSync( 7284): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7284): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5758109531603221277&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7284): Headers suppressed
E/BooksSync( 7284): 
E/BooksSync( 7284): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7284): Sync error
E/BooksSync( 7284): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7284): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5758109531603221277&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7284): Headers suppressed
E/BooksSync( 7284): 
E/BooksSync( 7284): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7284): Finished books sync
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  844): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 157377, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  844): SIOP:: AP = 310, PST = 341, CUR = 300
,I/art     (  844): Explicit concurrent mark sweep GC freed 43161(2MB) AllocSpace objects, 23(823KB) LOS objects, 30% free, 36MB/52MB, paused 3.296ms total 145.729ms
,D/SecContentProvider2(  844): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  844): mCursor = null
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1679): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  844): uri = 14 selection = getSealedState
,D/SecContentProvider2(  844): mCursor = null
D/SecContentProvider2(  844): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  844): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  844): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6555): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6555): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6555): 	at kfv.a(PG:65)
E/HttpOperation( 6555): 	at kff.u(PG:385)
E/HttpOperation( 6555): 	at kfb.a(PG:29)
E/HttpOperation( 6555): 	at kff.l(PG:132)
E/HttpOperation( 6555): 	at dsf.a(PG:807)
E/HttpOperation( 6555): 	at fhk.a(PG:1126)
E/HttpOperation( 6555): 	at fhk.a(PG:908)
E/HttpOperation( 6555): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6555): 	at ihi.a(PG:22)
E/HttpOperation( 6555): 	at kft.a(PG:91)
E/HttpOperation( 6555): 	at kfv.a(PG:62)
E/HttpOperation( 6555): 	... 8 more
E/HttpOperation( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6555): 	at gde.c(Unknown Source)
E/HttpOperation( 6555): 	at gde.b(Unknown Source)
E/HttpOperation( 6555): 	at ihi.a(PG:19)
E/HttpOperation( 6555): 	... 10 more
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  844): uri = 14 selection = getSealedState
D/SecContentProvider2(  844): mCursor = null
D/SecContentProvider2(  844): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  844): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  844): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6555): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6555): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6555): 	at kfv.a(PG:65)
E/HttpOperation( 6555): 	at kff.u(PG:385)
E/HttpOperation( 6555): 	at kfb.a(PG:29)
E/HttpOperation( 6555): 	at kff.l(PG:132)
E/HttpOperation( 6555): 	at ieo.a(PG:43)
E/HttpOperation( 6555): 	at iep.a(PG:93)
E/HttpOperation( 6555): 	at fhn.a(PG:59)
E/HttpOperation( 6555): 	at lex.a(PG:85)
E/HttpOperation( 6555): 	at lex.b(PG:132)
E/HttpOperation( 6555): 	at fhk.a(PG:1146)
E/HttpOperation( 6555): 	at fhk.a(PG:908)
E/HttpOperation( 6555): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6555): 	at ihi.a(PG:22)
E/HttpOperation( 6555): 	at kft.a(PG:91)
E/HttpOperation( 6555): 	at kfv.a(PG:62)
E/HttpOperation( 6555): 	... 12 more
E/HttpOperation( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6555): 	at gde.c(Unknown Source)
E/HttpOperation( 6555): 	at gde.b(Unknown Source)
E/HttpOperation( 6555): 	at ihi.a(PG:19)
E/HttpOperation( 6555): 	... 14 more
E/ExperimentLoader( 6555): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6555): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6555): 	at kfv.a(PG:65)
E/ExperimentLoader( 6555): 	at kff.u(PG:385)
E/ExperimentLoader( 6555): 	at kfb.a(PG:29)
E/ExperimentLoader( 6555): 	at kff.l(PG:132)
E/ExperimentLoader( 6555): 	at ieo.a(PG:43)
E/ExperimentLoader( 6555): 	at iep.a(PG:93)
E/ExperimentLoader( 6555): 	at fhn.a(PG:59)
E/ExperimentLoader( 6555): 	at lex.a(PG:85)
E/ExperimentLoader( 6555): 	at lex.b(PG:132)
E/ExperimentLoader( 6555): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6555): 	at fhk.a(PG:908)
E/ExperimentLoader( 6555): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6555): 	at ihi.a(PG:22)
E/ExperimentLoader( 6555): 	at kft.a(PG:91)
E/ExperimentLoader( 6555): 	at kfv.a(PG:62)
E/ExperimentLoader( 6555): 	... 12 more
E/ExperimentLoader( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6555): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6555): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6555): 	at ihi.a(PG:19)
E/ExperimentLoader( 6555): 	... 14 more
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  844): uri = 14 selection = getSealedState
D/SecContentProvider2(  844): mCursor = null
,D/SecContentProvider2(  844): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  844): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  844): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6555): [getaccountstatus] Unexpected exception
E/HttpOperation( 6555): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6555): 	at kfv.a(PG:65)
E/HttpOperation( 6555): 	at kff.u(PG:385)
E/HttpOperation( 6555): 	at kfb.a(PG:29)
E/HttpOperation( 6555): 	at ixd.a(PG:248)
E/HttpOperation( 6555): 	at ixd.b(PG:206)
E/HttpOperation( 6555): 	at ixd.a(PG:175)
E/HttpOperation( 6555): 	at fig.a(PG:78)
E/HttpOperation( 6555): 	at lex.a(PG:85)
E/HttpOperation( 6555): 	at lex.b(PG:132)
E/HttpOperation( 6555): 	at fhk.a(PG:1146)
E/HttpOperation( 6555): 	at fhk.a(PG:908)
E/HttpOperation( 6555): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6555): 	at ihi.a(PG:22)
E/HttpOperation( 6555): 	at kft.a(PG:91)
E/HttpOperation( 6555): 	at kfv.a(PG:62)
E/HttpOperation( 6555): 	... 12 more
E/HttpOperation( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6555): 	at gde.c(Unknown Source)
E/HttpOperation( 6555): 	at gde.b(Unknown Source)
E/HttpOperation( 6555): 	at ihi.a(PG:19)
E/HttpOperation( 6555): 	... 14 more
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/EsSyncAdapterService( 6555): Sync failure
E/EsSyncAdapterService( 6555): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6555): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6555): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6555): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6555): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6555): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6555): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6555): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6555): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6555): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6555): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6555): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6555): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6555): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6555): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6555): 	... 10 more
E/EsSyncAdapterService( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6555): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6555): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6555): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6555): 	... 12 more
E/EsSyncAdapterService( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6555): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6555): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6555): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6555): 	... 14 more
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  844): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 185454, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  844): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  844): mCursor = null
,E/SQLiteLog( 1679): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  287): DCD ON
,D/BatteryService(  844): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  844): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  844): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  844):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  844): Plugged
,I/MotionRecognitionService(  844): setPowerConnected  = true
,D/BatteryService(  844): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  844): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  844): [PWL] Off : 105s ago
,E/SMD     (  287): DCD ON
,E/Watchdog(  844): !@Sync 6
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  844): SIOP:: AP = 310, PST = 336, CUR = 300
,E/SMD     (  287): DCD ON
,V/AlarmManager(  844): waitForAlarm result :8
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  844): SIOP:: AP = 310, PST = 326, CUR = 300
,E/SMD     (  287): DCD ON
,W/ContextImpl(  844): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  336): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  336): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD ON
,V/AlarmManager(  844): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/BatteryService(  844): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  844): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  844): stay LED for fully charged
,D/BatteryService(  844): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/MotionRecognitionService(  844):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  844): Plugged
I/MotionRecognitionService(  844): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  844): SIOP:: AP = 310, PST = 319, CUR = 300
,E/SMD     (  287): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,E/Watchdog(  844): !@Sync 7
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/BatteryService(  844): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  844): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  844): Sending ACTION_BATTERY_CHANGED.
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/MotionRecognitionService(  844):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  844): Plugged
,I/MotionRecognitionService(  844): setPowerConnected  = true
,D/BatteryService(  844): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 1
,I/PowerManagerService(  844): [PWL] Off : 140s ago
,D/SSRM:m  (  844): SIOP:: AP = 300, PST = 315, CUR = 300
,E/SMD     (  287): DCD ON
,W/ContextImpl(  844): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/BatteryService(  844): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  844): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  844): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  844):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  844): Plugged
,I/MotionRecognitionService(  844): setPowerConnected  = true
,D/BatteryService(  844): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  844): SIOP:: AP = 300, PST = 312, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,V/AlarmManager(  844): waitForAlarm result :4
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7284): Starting books sync, d
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  844): uri = 14 selection = getSealedState
,D/SecContentProvider2(  844): mCursor = null
D/SecContentProvider2(  844): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  844): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  844): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7284): Authentication error
E/BooksAccountManager( 7284): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7284): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7284): null auth token
,I/qtaguid ( 7284): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7284, getuid(): 10082
,I/qtaguid ( 7284): Untagging socket 34
,W/ApiaryClient( 7284): Error response from books API: {
W/ApiaryClient( 7284):  "error": {
W/ApiaryClient( 7284):   "errors": [
W/ApiaryClient( 7284):    {
W/ApiaryClient( 7284):     "domain": "global",
W/ApiaryClient( 7284):     "reason": "required",
W/ApiaryClient( 7284):     "message": "Login Required",
W/ApiaryClient( 7284):     "locationType": "header",
W/ApiaryClient( 7284):     "location": "Authorization"
W/ApiaryClient( 7284):    }
W/ApiaryClient( 7284):   ],
W/ApiaryClient( 7284):   "code": 401,
W/ApiaryClient( 7284):   "message": "Login Required"
W/ApiaryClient( 7284):  }
W/ApiaryClient( 7284): }
,W/ApiaryClient( 7284): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7284): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1819181158286563700&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7284): Headers suppressed
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  844): uri = 14 selection = getSealedState
,D/SecContentProvider2(  844): mCursor = null
D/SecContentProvider2(  844): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  844): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  844): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7284): Authentication error
E/BooksAccountManager( 7284): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7284): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7284): null auth token
,I/qtaguid ( 7284): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7284, getuid(): 10082
,I/qtaguid ( 7284): Untagging socket 34
,W/ApiaryClient( 7284): Error response from books API: {
W/ApiaryClient( 7284):  "error": {
W/ApiaryClient( 7284):   "errors": [
W/ApiaryClient( 7284):    {
W/ApiaryClient( 7284):     "domain": "global",
W/ApiaryClient( 7284):     "reason": "required",
W/ApiaryClient( 7284):     "message": "Login Required",
W/ApiaryClient( 7284):     "locationType": "header",
W/ApiaryClient( 7284):     "location": "Authorization"
W/ApiaryClient( 7284):    }
W/ApiaryClient( 7284):   ],
W/ApiaryClient( 7284):   "code": 401,
W/ApiaryClient( 7284):   "message": "Login Required"
W/ApiaryClient( 7284):  }
W/ApiaryClient( 7284): }
,W/ApiaryClient( 7284): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7284): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1819181158286563700&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7284): Headers suppressed
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  287): DCD ON
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  844): uri = 14 selection = getSealedState
,D/SecContentProvider2(  844): mCursor = null
D/SecContentProvider2(  844): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  844): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  844): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7284): Authentication error
E/BooksAccountManager( 7284): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7284): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7284): null auth token
,I/qtaguid ( 7284): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7284, getuid(): 10082
,I/qtaguid ( 7284): Untagging socket 34
,W/ApiaryClient( 7284): Error response from books API: {
W/ApiaryClient( 7284):  "error": {
W/ApiaryClient( 7284):   "errors": [
W/ApiaryClient( 7284):    {
W/ApiaryClient( 7284):     "domain": "global",
W/ApiaryClient( 7284):     "reason": "required",
W/ApiaryClient( 7284):     "message": "Login Required",
W/ApiaryClient( 7284):     "locationType": "header",
W/ApiaryClient( 7284):     "location": "Authorization"
W/ApiaryClient( 7284):    }
W/ApiaryClient( 7284):   ],
W/ApiaryClient( 7284):   "code": 401,
W/ApiaryClient( 7284):   "message": "Login Required"
W/ApiaryClient( 7284):  }
W/ApiaryClient( 7284): }
,W/ApiaryClient( 7284): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7284): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1819181158286563700&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7284): Headers suppressed
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/BooksSync( 7284): Soft error
E/BooksSync( 7284): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7284): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1819181158286563700&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7284): Headers suppressed
E/BooksSync( 7284): 
E/BooksSync( 7284): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7284): Sync error
E/BooksSync( 7284): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7284): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1819181158286563700&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7284): Headers suppressed
E/BooksSync( 7284): 
E/BooksSync( 7284): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7284): Finished books sync
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/SyncManager(  844): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 219438, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  844): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  844): mCursor = null
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  844): SIOP:: AP = 300, PST = 309, CUR = 300
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/ContextImpl(  844): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD ON
,E/Watchdog(  844): !@Sync 8
,D/BatteryService(  844): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  844): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  844): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  844):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  844): Plugged
,I/MotionRecognitionService(  844): setPowerConnected  = true
,D/BatteryService(  844): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  844): SIOP:: AP = 300, PST = 307, CUR = 300
,E/SMD     (  287): DCD ON
,V/AlarmManager(  844): waitForAlarm result :8
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/PowerManagerService(  844): [PWL] Off : 180s ago
,E/SMD     (  287): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/SSRM:m  (  844): SIOP:: AP = 300, PST = 305, CUR = 300
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/ContextImpl(  844): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD ON
,V/AlarmManager(  844): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/BatteryService(  844): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  844): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  844): stay LED for fully charged
,D/BatteryService(  844): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/MotionRecognitionService(  844):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  844): Plugged
I/MotionRecognitionService(  844): setPowerConnected  = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  844): uri = 14 selection = getSealedState
D/SecContentProvider2(  844): mCursor = null
,D/SecContentProvider2(  844): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  844): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  844): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6555): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6555): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6555): 	at kfv.a(PG:65)
E/HttpOperation( 6555): 	at kff.u(PG:385)
E/HttpOperation( 6555): 	at kfb.a(PG:29)
E/HttpOperation( 6555): 	at kff.l(PG:132)
E/HttpOperation( 6555): 	at dsf.a(PG:807)
E/HttpOperation( 6555): 	at fhk.a(PG:1126)
E/HttpOperation( 6555): 	at fhk.a(PG:908)
E/HttpOperation( 6555): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6555): 	at ihi.a(PG:22)
E/HttpOperation( 6555): 	at kft.a(PG:91)
E/HttpOperation( 6555): 	at kfv.a(PG:62)
E/HttpOperation( 6555): 	... 8 more
E/HttpOperation( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6555): 	at gde.c(Unknown Source)
E/HttpOperation( 6555): 	at gde.b(Unknown Source)
E/HttpOperation( 6555): 	at ihi.a(PG:19)
E/HttpOperation( 6555): 	... 10 more
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  844): uri = 14 selection = getSealedState
D/SecContentProvider2(  844): mCursor = null
,D/SecContentProvider2(  844): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  844): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  844): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6555): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6555): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6555): 	at kfv.a(PG:65)
E/HttpOperation( 6555): 	at kff.u(PG:385)
E/HttpOperation( 6555): 	at kfb.a(PG:29)
E/HttpOperation( 6555): 	at kff.l(PG:132)
E/HttpOperation( 6555): 	at ieo.a(PG:43)
E/HttpOperation( 6555): 	at iep.a(PG:93)
E/HttpOperation( 6555): 	at fhn.a(PG:59)
E/HttpOperation( 6555): 	at lex.a(PG:85)
E/HttpOperation( 6555): 	at lex.b(PG:132)
E/HttpOperation( 6555): 	at fhk.a(PG:1146)
E/HttpOperation( 6555): 	at fhk.a(PG:908)
E/HttpOperation( 6555): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6555): 	at ihi.a(PG:22)
E/HttpOperation( 6555): 	at kft.a(PG:91)
E/HttpOperation( 6555): 	at kfv.a(PG:62)
E/HttpOperation( 6555): 	... 12 more
E/HttpOperation( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6555): 	at gde.c(Unknown Source)
E/HttpOperation( 6555): 	at gde.b(Unknown Source)
E/HttpOperation( 6555): 	at ihi.a(PG:19)
E/HttpOperation( 6555): 	... 14 more
,E/ExperimentLoader( 6555): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6555): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6555): 	at kfv.a(PG:65)
E/ExperimentLoader( 6555): 	at kff.u(PG:385)
E/ExperimentLoader( 6555): 	at kfb.a(PG:29)
E/ExperimentLoader( 6555): 	at kff.l(PG:132)
E/ExperimentLoader( 6555): 	at ieo.a(PG:43)
E/ExperimentLoader( 6555): 	at iep.a(PG:93)
E/ExperimentLoader( 6555): 	at fhn.a(PG:59)
E/ExperimentLoader( 6555): 	at lex.a(PG:85)
E/ExperimentLoader( 6555): 	at lex.b(PG:132)
E/ExperimentLoader( 6555): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6555): 	at fhk.a(PG:908)
E/ExperimentLoader( 6555): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6555): 	at ihi.a(PG:22)
E/ExperimentLoader( 6555): 	at kft.a(PG:91)
E/ExperimentLoader( 6555): 	at kfv.a(PG:62)
E/ExperimentLoader( 6555): 	... 12 more
E/ExperimentLoader( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6555): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6555): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6555): 	at ihi.a(PG:19)
E/ExperimentLoader( 6555): 	... 14 more
D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/art     ( 1679): Explicit concurrent mark sweep GC freed 50250(2MB) AllocSpace objects, 52(3MB) LOS objects, 40% free, 18MB/30MB, paused 933us total 103.250ms
,E/SQLiteLog( 1679): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1679): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  844): uri = 14 selection = getSealedState
,D/SecContentProvider2(  844): mCursor = null
,D/SecContentProvider2(  844): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  844): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  844): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6555): [getaccountstatus] Unexpected exception
E/HttpOperation( 6555): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6555): 	at kfv.a(PG:65)
E/HttpOperation( 6555): 	at kff.u(PG:385)
E/HttpOperation( 6555): 	at kfb.a(PG:29)
E/HttpOperation( 6555): 	at ixd.a(PG:248)
E/HttpOperation( 6555): 	at ixd.b(PG:206)
E/HttpOperation( 6555): 	at ixd.a(PG:175)
E/HttpOperation( 6555): 	at fig.a(PG:78)
E/HttpOperation( 6555): 	at lex.a(PG:85)
E/HttpOperation( 6555): 	at lex.b(PG:132)
E/HttpOperation( 6555): 	at fhk.a(PG:1146)
E/HttpOperation( 6555): 	at fhk.a(PG:908)
E/HttpOperation( 6555): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6555): 	at ihi.a(PG:22)
E/HttpOperation( 6555): 	at kft.a(PG:91)
E/HttpOperation( 6555): 	at kfv.a(PG:62)
E/HttpOperation( 6555): 	... 12 more
E/HttpOperation( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6555): 	at gde.c(Unknown Source)
E/HttpOperation( 6555): 	at gde.b(Unknown Source)
E/HttpOperation( 6555): 	at ihi.a(PG:19)
E/HttpOperation( 6555): 	... 14 more
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/EsSyncAdapterService( 6555): Sync failure
E/EsSyncAdapterService( 6555): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6555): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6555): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6555): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6555): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6555): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6555): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6555): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6555): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6555): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6555): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6555): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6555): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6555): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6555): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6555): 	... 10 more
E/EsSyncAdapterService( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6555): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6555): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6555): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6555): 	... 12 more
E/EsSyncAdapterService( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6555): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6555): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6555): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6555): 	... 14 more
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  844): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 250112, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2854): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  844): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  844): mCursor = null
,E/SQLiteLog( 1679): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  844): SIOP:: AP = 300, PST = 304, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/Watchdog(  844): !@Sync 9
,D/BatteryService(  844): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  844): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  844): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  844):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  844): Plugged
,I/MotionRecognitionService(  844): setPowerConnected  = true
,D/BatteryService(  844): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  844): SIOP:: AP = 300, PST = 303, CUR = 300
,E/SMD     (  287): DCD ON
,W/ContextImpl(  844): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/BatteryService(  844): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  844): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  844): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  844):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  844): Plugged
,D/BatteryService(  844): stay LED for fully charged
,I/MotionRecognitionService(  844): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  844): SIOP:: AP = 300, PST = 302, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,V/AlarmManager(  844): waitForAlarm result :4
,D/ConnectivityService(  844): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  844): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  844): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  844): stay LED for fully charged
,D/BatteryService(  844): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  844):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  844): Plugged
I/MotionRecognitionService(  844): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  844): SIOP:: AP = 300, PST = 301, CUR = 300
,E/SMD     (  287): DCD ON
,D/TimaService(  844): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  844): TimaServiceHandler.handleMessage what =1
,D/TimaService(  844): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  844): initializing...
,I/TLC_TIMA_PKM_initialize(  844): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  844): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  844): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  844): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  844): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  844): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  844): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  844): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  844): App is not loaded in QSEE
,D/QSEECOMAPI: (  844): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  844): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  844): Trustlet response is completed
,W/ContextImpl(  844): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  844): [PWL] Off : 225s ago
,I/PowerManagerService(  844): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  844): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  844): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=844, ws=null) (elapsedTime=1853)
,E/SMD     (  287): DCD ON
,E/Watchdog(  844): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  844): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  844): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  844): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  844): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  844): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  844): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  844): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  844):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  844): Plugged
,I/MotionRecognitionService(  844): setPowerConnected  = true
,D/BatteryService(  844): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON,
,D/SSRM:m  (  844): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  287): DCD ON
,V/AlarmManager(  844): waitForAlarm result :8
,E/SMD     (  287): DCD ON
,I/Atfwd_Sendcmd(  336): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  336): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/jxcore-log( 7452): --= Surplus to requirements =--
I/jxcore-log( 7452): 
,I/jxcore-log( 7452): ****TEST TOOK:  ms ****
I/jxcore-log( 7452): 
,I/jxcore-log( 7452): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7452): 
,D/SSRM:m  (  844): SIOP:: AP = 300, PST = 300, CUR = 300
,D/AndroidRuntime( 8497): 
D/AndroidRuntime( 8497): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8497): CheckJNI is OFF
,D/AndroidRuntime( 8497): setted country_code = Germany
,D/AndroidRuntime( 8497): setted countryiso_code = DE
,D/AndroidRuntime( 8497): setted sales_code = DBT
,D/AndroidRuntime( 8497): readGMSProperty: start
D/AndroidRuntime( 8497): readGMSProperty: already setted!!
,D/AndroidRuntime( 8497): readGMSProperty: end
D/AndroidRuntime( 8497): addProductProperty: start
,E/AffinityControl( 8497): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8497): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService(  844): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager(  844): START PACKAGE DELETE: observer{634533627}
D/PackageManager(  844): pkg{<packageName>}
D/PackageManager(  844): user{0}
D/PackageManager(  844): caller{2000}
D/PackageManager(  844): flags{3}
D/PersonaManagerService(  844): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  844): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  844): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  844): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  844): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  844): deletePackage- pkg:com.test.thalitest, edmuserId:0
,D/PackageManagerService(  844): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  844): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  844): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  844): !@killApplicatoin: 10200, uninstall pkg
,I/ActivityManager(  844): Force stopping com.test.thalitest appid=10200 user=-1: uninstall pkg
,I/ActivityManager(  844): Killing 7452:com.test.thalitest/u0a200 (adj 0): stop com.test.thalitest
,I/ActivityManager(  844):   Force finishing activity ActivityRecord{5f6e885 u0 com.test.thalitest/.MainActivity t17}
,D/FocusedStackFrame(  844): Set to : 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/SurfaceFlinger(  249): id=14 Removed com.test.thalitest/com.test.thalitest.MainActivity (6/8)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SurfaceFlinger(  249): id=14 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/WifiService(  844): Client connection lost with reason: 4
,I/ActivityManager(  844): Force stopping com.test.thalitest appid=10200 user=0: pkg removed
,D/ConnectivityService(  844): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1544): Explicit concurrent mark sweep GC freed 10466(635KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 16MB/27MB, paused 405us total 18.120ms
,I/art     ( 4587): Explicit concurrent mark sweep GC freed 5023(278KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 333us total 33.054ms
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  844): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,E/SamsungIME( 1854): mOCRHelper is null
,W/GeofencerStateMachine( 2224): Ignoring removeGeofence because network location is disabled.
,D/ResourcesManager( 2854): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,I/KLMS-2.4.503: ( 7655): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7655): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1453034529504
,I/KLMS-2.4.503: ( 7655): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.503: ( 7655): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/art     (  844): Explicit concurrent mark sweep GC freed 58115(3MB) AllocSpace objects, 60(1545KB) LOS objects, 30% free, 36MB/52MB, paused 4.917ms total 230.082ms
,I/art     (  844): WaitForGcToComplete blocked for 134.972ms for cause Explicit
D/ResourcesManager(  844): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/RegisteredServicesCache( 1465): empty dynamic service
,D/ResourcesManager( 2854): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/SecContentProvider2(  844): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  844): mCursor = null
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/EnterpriseDeviceManagerService(  844): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  844): Admin package name: com.google.android.gms
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,E/Zygote  ( 8526): MountEmulatedStorage()
E/Zygote  ( 8526): v2
I/libpersona( 8526): KNOX_SDCARD checking this for 10104
I/libpersona( 8526): KNOX_SDCARD not a persona
,I/ActivityManager(  844): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8526 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/Books/Books.apk
,I/art     (  319): Explicit concurrent mark sweep GC freed 8735(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 276us total 13.374ms
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 260us total 7.899ms
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 256us total 8.277ms
,I/SELinux ( 8526): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,I/SELinux ( 8526): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,E/SELinux ( 8526): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/TimaKeyStoreProvider( 8526): TimaSignature is unavailable
,D/ActivityThread( 8526): Added TimaKeyStore provider
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 8526): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/SurfaceWidgetView( 1492): destroyHardwareResources():755621454
,V/WindowOrientationListener(  844): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
,V/WindowOrientationListener(  844): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,V/WindowManager(  844): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  844): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  844): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/Launcher( 1492): onRestart, Launcher: 933171095
,D/Launcher( 1492): onStart, Launcher: 933171095
D/Launcher.HomeView( 1492): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2143): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2143): [237392/6] SurfaceWidget drawing first frame
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/SurfaceFlinger(  249): id=16 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/StatusBarManagerService(  844): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/StatusBarManagerService(  844): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/RCPManagerService(  844): PackageReceiver onReceive()
I/HarmonyEASService(  844): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  844): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/InputMethodManagerService(  844): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  844): Got RemoteException sending setActive(false) notification to pid 7452 uid 10200
,W/ContextImpl(  844): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/elm:14451( 8526): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 8526): ELMEngine.ELMEngine( context ).
,D/elm:14451( 8526): MDMBridge.setEnterpriseBridge()
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:14451( 8526): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/elm:14451( 8526): ElmAgentService : onCreate()
,D/elm:14451( 8526): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8526): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8526): MDMBridge.getInstance()
D/elm:14451( 8526): MDMBridge.getAllLicenseInfoFromSDK()
,D/BackupManagerService(  844): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  844): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  844): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  844): uID is 10200
V/EnterpriseBillingPolicy(  844): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  844): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  844): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  844): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  844): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  844): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage(  844): getBillingProfileForVpnEngine - end - null
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/elm:14451( 8526): MDMBridge.getAllLicenseInfoFromSDK()
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 8026): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8026): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8026): onReceive() : package name is not s health. Return !!!
,D/TaskPersister(  844): removeObsoleteFile: deleting file=17_task.xml
,D/elm:14451( 8526): ElmAgentService : onDestroy().
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager(  844): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,I/PCWCLIENTTRACE_PushUtil( 6772): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6772): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 6772): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6772): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/art     (  844): Explicit concurrent mark sweep GC freed 14225(709KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 6.751ms total 399.153ms
,I/Timeline(  844): Timeline: Activity_windows_visible id: ActivityRecord{29174f3d u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t15} time:330496
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,E/Zygote  ( 8549): MountEmulatedStorage()
E/Zygote  ( 8549): v2
I/libpersona( 8549): KNOX_SDCARD checking this for 10038
I/libpersona( 8549): KNOX_SDCARD not a persona
,I/ActivityManager(  844): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8549 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8549): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8549): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8549): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  844): Killing 7085:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  844): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  844): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  844): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 8549): TimaSignature is unavailable
,D/ActivityThread( 8549): Added TimaKeyStore provider
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  844): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 8549): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/libprocessgroup(  844): failed to open /acct/uid_10166/pid_7085/cgroup.procs: No such file or directory
,E/SPPClientService( 8549): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 8549): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 8549): PushLog.txt file is not deleted.
D/SPPClientService( 8549): PushLog.txt file is not deleted.
D/SPPClientService( 8549): ============PushLog. stop!
,D/ResourcesManager(  844): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  844): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/PackageManager(  844): delete codoeFile: 
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,D/PackageManager(  844): result of delete: 1{634533627}
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/AndroidRuntime( 8497): Shutting down VM
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,E/Zygote  ( 8565): MountEmulatedStorage()
E/Zygote  ( 8565): v2
I/libpersona( 8565): KNOX_SDCARD checking this for 10042
I/libpersona( 8565): KNOX_SDCARD not a persona
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  844): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,I/ActivityManager(  844): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8565 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  844): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/ActivityManager(  844): Killing 6638:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,W/Resources(  844): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  844): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  844): onPackageRemoved : com.test.thalitest
,I/SELinux ( 8565): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 7963): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
I/SELinux ( 8565): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,W/ResourcesManager( 7963): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7963): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/SELinux ( 8565): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 7963): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7963): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7963): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 7963): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7963): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
W/ResourcesManager( 7963): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 8565): TimaSignature is unavailable
D/ActivityThread( 8565): Added TimaKeyStore provider
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/libprocessgroup(  844): failed to open /acct/uid_10012/pid_6638/cgroup.procs: No such file or directory
,W/ResourcesManager( 7963): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7963): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7963): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7963): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8565): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,W/ResourcesManager( 8565): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8565): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 7963): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7963): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7963): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 7963): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7963): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7963): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 7963): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7963): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7963): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 7963): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7963): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/System.err( 8565): java.lang.NoSuchMethodException: getImeiInCDMAGSMPhone []
,W/System.err( 8565): 	at java.lang.Class.getMethod(Class.java:665)
,W/System.err( 8565): 	at com.sec.pcw.util.c.c(SourceFile:295)
W/System.err( 8565): 	at com.sec.pcw.service.account.a.b(SourceFile:250)
W/System.err( 8565): 	at com.sec.pcw.service.account.a.a(SourceFile:52)
,W/System.err( 8565): 	at com.mfluent.asp.datamodel.Device.r(SourceFile:359)
,W/System.err( 8565): 	at com.mfluent.asp.datamodel.Device.<init>(SourceFile:248)
W/System.err( 8565): 	at com.mfluent.asp.datamodel.t.a(SourceFile:136)
,W/System.err( 8565): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:484)
W/System.err( 8565): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
,W/System.err( 8565): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
W/System.err( 8565): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
,W/System.err( 8565): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
W/System.err( 8565): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
,W/System.err( 8565): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 8565): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 8565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 8565): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 8565): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
,W/System.err( 8565): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 8565): 	at java.lang.reflect.Method.invoke(Method.java:372)
,W/System.err( 8565): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
,W/System.err( 8565): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,F/libc    ( 8565): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb3ccfa70 in tid 8565 (sdk.samsunglink)
,E/audit_log( 2154): File locking failed. error= Bad file number
,F/libc    ( 8565): Failed while talking to debuggerd: Broken pipe
E/audit_log( 2154): File locking failed. error= Bad file number
,I/EventHub(  844): Removing device '/dev/input/event4' due to inotify event
,I/EventHub(  844): Removing device '/dev/input/event5' due to inotify event
,I/ActivityManager(  844): Process com.samsung.android.sdk.samsunglink (pid 8565)(adj 0) has died(168,523)
,I/SA      ( 6814): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6814): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10200 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,F/libc    ( 1781): Fatal signal 7 (SIGBUS), code 2, fault addr 0x77e0044c in tid 1781 (d.process.acore)
,F/libc    ( 1781): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2154): File locking failed. error= Bad file number
,I/EventHub(  844): Removing device '/dev/input/event6' due to inotify event
,I/Zygote  (  319): Process 8565 exited due to signal (7)
,I/ActivityManager(  844): Process android.process.acore (pid 1781)(adj 0) has died(173,523)
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,E/SharedPreferencesImpl( 6040): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml
,I/EventHub(  844): Removing device '/dev/input/event7' due to inotify event
,I/ActivityManager(  844): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageReceiver: pid=8591 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,E/Zygote  ( 8591): MountEmulatedStorage()
E/Zygote  ( 8591): v2
I/libpersona( 8591): KNOX_SDCARD checking this for 10050
I/libpersona( 8591): KNOX_SDCARD not a persona
,I/Zygote  (  319): Process 1781 exited due to signal (7)
,I/EventHub(  844): Removing device '/dev/input/event8' due to inotify event
,E/SMD     (  287): DCD ON
,I/SELinux ( 8591): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,E/SELinux ( 8591): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/EventHub(  844): Removing device '/dev/input/event9' due to inotify event
,I/EventHub(  844): Removing device '/dev/input/event10' due to inotify event
,D/TimaKeyStoreProvider( 8591): TimaSignature is unavailable
,D/ActivityThread( 8591): Added TimaKeyStore provider
,I/EventHub(  844): Removing device '/dev/input/event11' due to inotify event
,D/ResourcesManager( 8591): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8591): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8591): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8591): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8591): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8591): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ContextImpl( 8591): Unable to create files subdir /data/data/com.android.mms/cache
E/ActivityThread( 8591): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 8591): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7429da62 in tid 8591 (com.android.mms)
,F/libc    ( 8591): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2154): File locking failed. error= Bad file number
,I/ActivityManager(  844): Process com.android.mms (pid 8591)(adj 0) has died(173,523)
,I/TactileAssist(  844): enable value -1
I/TactileAssist(  844): internal enable value -1
I/TactileAssist(  844): intensity value -1
I/TactileAssist(  844): saveAppList value true
,I/TactileAssist(  844): List of disabled apps :
I/TactileAssist(  844): de.zalando.mobile
,E/SharedPreferencesImpl(  844): Couldn't create directory for SharedPreferences file /data/data/com.android.settings/shared_prefs/com.android.settings_tactileassist.xml
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  844): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=8611 uid=10058 gids={50058, 9997, 3003, 3002} abi=armeabi-v7a
,E/Zygote  ( 8611): MountEmulatedStorage()
E/Zygote  ( 8611): v2
I/libpersona( 8611): KNOX_SDCARD checking this for 10058
I/libpersona( 8611): KNOX_SDCARD not a persona
,I/Zygote  (  319): Process 8591 exited due to signal (7)
,W/ContextImpl(  844): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SELinux ( 8611): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,E/SELinux ( 8611): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,D/TimaKeyStoreProvider( 8611): TimaSignature is unavailable
,D/ActivityThread( 8611): Added TimaKeyStore provider
,D/ResourcesManager( 8611): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,W/ResourcesManager( 8611): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ContextImpl( 8611): Unable to create files subdir /data/data/com.sec.android.app.soundalive/cache
E/ActivityThread( 8611): Unable to setupGraphicsSupport due to missing cache directory
,D/AndroidRuntime( 8611): Shutting down VM
,F/libc    ( 8611): Fatal signal 7 (SIGBUS), code 2, fault addr 0x74585fa4 in tid 8611 (.app.soundalive)
,F/libc    ( 8611): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2154): File locking failed. error= Bad file number
I/ActivityManager(  844): Killing 7105:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): bgCount ##41
,I/UpdateIcingCorporaServi( 1544): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  844): checkUser: useridlist=null, currentuser=0

```
